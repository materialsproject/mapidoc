# Introduction

This is the public repo for the documentation of the Materials API. The 
Materials API is a simple, flexible and efficient interface to programmatically
query and interact with the [Materials Project](https://www.materialsproject.org)
database based on the REpresentational State Transfer (REST) pattern for the
web. Since its creation in Aug 2012, the Materials API has been the Materials
Project’s de facto platform for data access, supporting not only the Materials
Project’s many collaborative efforts but also enabling new applications and
analyses.

# Using this repo

The usage of this repo is very simple and in fact, follows a REST format. The
primary use of this repo is to explore the Materials Project's document format
and use that info for much more powerful queries with the 
[pymatgen](http://www.pymatgen.org) (Python Materials Genomics) MPRester.query()
method. For more standard queries, the Materials API already has a 
[wiki page](https://materialsproject.org/wiki/index.php/The_Materials_API) and
pymatgen already provides useful high-level functions for them.

1. Start from the docs directory by clicking the docs folder above.
   The nested directory structure follows the MongoDB json-like document schema
   for the Materials Project's materials collection.
2. In each folder, there is a README.md that describes what that key is. For
   example, in docs/final_energy, the README.md informs you that the 
   *final_energy* key refers final calculated energy of the material.
   Similarly, the docs/task_id informs you that the *task_id* key is in fact the
   materials id for the Materials Project.
3. To use this in MPRester, one may use the following code:

	```python
	from pymatgen import MPRester
	m = MPRester()
	data = m.query(criteria={"task_id": "mp-1234"}, properties=["final_energy"])
	print data
	```

   The data obtained is then [{u'final_energy': -26.94736193}]. Note that the
   data returned is always a list of dicts.
4. For a more complicated example, you can try:

	```python
	m.query(criteria={"pretty_formula": "Li2O"}, properties=["spacegroup.symbol"])
	```

   You can identify the appropriate key by going to the docs/spacegroup/symbol
   subfolder. This means that the desired information is in spacegroup.symbol
   (concantenate all subfolders with "." and drop the initial "docs" prefix).
5. One more very complicated example. Let's say you would like to query for the
   tags and icsd_ids of all materials containing Fe and O, and perhaps other
   elements.

    ```python
    m.query(criteria={"elements": {"$all": ["Fe", "O"]}}, properties=["exp.tags", "icsd_id"])
    ```
   
   Note that the criteria follows the format of MongoDB queries. You can refer
   to the [MongoDB documentation](http://docs.mongodb.org/manual/) for more
   information on how to customize queries.

## Tip for efficient querying:

Try to minimize the scope of the properties you are requesting. For example,
if you are only interested in the XRD pattern for Cu K<sub>`&alpha;`</sub>,
do not just use `properties=["xrd"]` which will fetch the computed XRD
patterns for all radiations. This results in a large data transfer and slow
queries. Instead, use `properties=["xrd.Cu"]`. 

# Searching for properties

You can use Github's built-in search box at the top to search this repository
for text that matches your query. For example, you can try searching for the
word "spacegroup" to see the that the "spacegroup" root key exists with
sub-keys such as "number" and "symbol".

Beause this repository's folder structure mirrors a material document's
structure, you can also use the [quick finder](https://github.com/materialsproject/MaterialsAPIDoc/find/master)
to interactively explore the structure.

# Contributing

The initial version of this documentation is brought to you by the Materials
Project development team. But it is our hope that others can contribute as well,
either by cloning and editing this documentation (and sending pull requests)
or just by informing us of any errors or omissions in the doc (e.g., by using
the "Issues" tab).

# Citing the Materials API

If you use the Materials API extensively, you may wish to cite the following 
[publication](http://dx.doi.org/10.1016/j.commatsci.2014.10.037).

	Ong, S. P.; Cholia, S.; Jain, A.; Brafman, M.; Gunter, D.; Ceder, G.; 
	Persson, K. a. The Materials Application Programming Interface (API): A 
	simple, flexible and efficient API for materials data based on
	REpresentational State Transfer (REST) principles, Comput. Mater. Sci.,
	2015, 97, 209–215. doi:10.1016/j.commatsci.2014.10.037.

