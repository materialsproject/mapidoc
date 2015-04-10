

## Example output in JSON

```json
{
    "elements": [
        "Al", 
        "Lu"
    ], 
    "is_ordered": true, 
    "anonymized_formula": "AB2", 
    "snl_id": 67504, 
    "@module": "mpworks.snl_utils.mpsnl", 
    "chemsystem": "Al-Lu", 
    "snl_timestamp": "2013-05-11T23:59:46.135727", 
    "composition_dict": {
        "Lu": 2.0, 
        "Al": 4.0
    }, 
    "@class": "MPStructureNL", 
    "about": {
        "created_at": "2012-06-26T23:57:12", 
        "_icsd": {}, 
        "_materialsproject": {
            "deprecated": {
                "mps_ids": [
                    84536
                ]
            }, 
            "snl_id": 67504, 
            "spacegroup": {
                "lattice_type": "cubic", 
                "symbol": "Fd-3m", 
                "crystal_system": "cubic", 
                "point_group": "m-3m", 
                "hall": "-F 4vw 2vw 3", 
                "number": 227
            }
        }, 
        "references": "@misc{MaterialsProject,\ntitle = {{Materials Project}},\nurl = {http://www.materialsproject.org}\n}\n\n@article{Haszko1960_243,\ntitle = {{Intermediate phases with the Mg Cu2 structure}},\nauthor = {Haszko, S.E.},\nyear = {1960},\njournal = {Transactions of the American Institute of Mining, Metallurgical and Petroleum Engineers},\nvolume = {218},\npages = {958--958},\n}\n\n@article{Bergerhoff1983,\nauthor = {Bergerhoff, G. and Hundt, R. and Sievers, R. and Brown, ID},\ndoi = {10.1021/ci00038a003},\njournal = {Journal of Chemical Information and Computer Sciences},\nkeywords = {icsd},\nmendeley-tags = {icsd},\nnumber = {2},\npages = {66--69},\npublisher = {ACS Publications},\ntitle = {{The inorganic crystal structure data base}},\nurl = {http://pubs.acs.org/doi/abs/10.1021/ci00038a003},\nvolume = {23},\nyear = {1983}\n}\n@misc{Karlsruhe,\nauthor = {Karlsruhe, FIZ},\ntitle = {{Inorganic Crystal Structure Database}},\nurl = {http://icsd.fiz-karlsruhe.de}\n}\n", 
        "authors": [
            {
                "email": "mpkocher@lbl.gov", 
                "name": "Michael Kocher"
            }, 
            {
                "email": "ajain@lbl.gov", 
                "name": "Anubhav Jain"
            }, 
            {
                "email": "shyue@mit.edu", 
                "name": "Shyue Ping Ong"
            }, 
            {
                "email": "geoffroy.hautier@uclouvain.be", 
                "name": "Geoffroy Hautier"
            }
        ], 
        "remarks": [], 
        "projects": [], 
        "history": [
            {
                "url": "http://icsd.fiz-karlsruhe.de/", 
                "description": {
                    "icsd_id": 608376
                }, 
                "name": "Inorganic Crystal Structure Database (ICSD)"
            }, 
            {
                "url": "http://cctbx.sourceforge.net/", 
                "description": {
                    "sites": [
                        {
                            "abc": [
                                0.625, 
                                0.625, 
                                0.625
                            ], 
                            "name": "Al", 
                            "wyckoff_multiplicity": 16, 
                            "symbol": "Al", 
                            "oxidation_state": 0.0, 
                            "wyckoff": "d", 
                            "occupation": 1.0
                        }, 
                        {
                            "abc": [
                                0.0, 
                                0.0, 
                                0.0
                            ], 
                            "name": "Lu", 
                            "wyckoff_multiplicity": 8, 
                            "symbol": "Lu", 
                            "oxidation_state": 0.0, 
                            "wyckoff": "a", 
                            "occupation": 1.0
                        }
                    ], 
                    "lattice": {
                        "a": 7.742, 
                        "c": 7.742, 
                        "b": 7.742, 
                        "volume": 464.04, 
                        "beta": 90.0, 
                        "lattice_id": 84536, 
                        "alpha": 90.0, 
                        "gamma": 90.0
                    }, 
                    "description": "Applied symmetry operations based on given spacegroup", 
                    "spacegroup": {
                        "space_group_id": 196, 
                        "centering": "F", 
                        "icsd_name": "F d -3 m S", 
                        "cctbx_name": "F d -3 m :1", 
                        "crystal_system": "cubic", 
                        "number": 227, 
                        "hall": "-F 4vw 2vw 3"
                    }
                }, 
                "name": "Computational Crystallography Toolbox (CCTBX)"
            }, 
            {
                "url": "http://www.materialsproject.org", 
                "description": {
                    "crystal_id": 84536
                }, 
                "name": "Materials Project"
            }
        ]
    }, 
    "reduced_cell_formula_abc": "Al2 Lu1", 
    "snlgroup_key": "Al2 Lu1--227", 
    "nelements": 2, 
    "reduced_cell_formula": "LuAl2", 
    "nsites": 6, 
    "sites": [
        {
            "label": "Lu", 
            "xyz": [
                5.531151963349649, 
                3.911115061057823, 
                9.580236224905942
            ], 
            "abc": [
                0.875, 
                0.875, 
                0.875
            ], 
            "species": [
                {
                    "occu": 1.0, 
                    "@module": "pymatgen.core.periodic_table", 
                    "@class": "Element", 
                    "element": "Lu"
                }
            ], 
            "properties": {}
        }, 
        {
            "label": "Al", 
            "xyz": [
                2.370493698578421, 
                0.0, 
                4.10581552495969
            ], 
            "abc": [
                0.5, 
                0.0, 
                0.5
            ], 
            "species": [
                {
                    "occu": 1.0, 
                    "@module": "pymatgen.core.periodic_table", 
                    "@class": "Element", 
                    "element": "Al"
                }
            ], 
            "properties": {}
        }, 
        {
            "label": "Lu", 
            "xyz": [
                0.7901645661928071, 
                0.5587307230082604, 
                1.368605174986563
            ], 
            "abc": [
                0.125, 
                0.125, 
                0.125
            ], 
            "species": [
                {
                    "occu": 1.0, 
                    "@module": "pymatgen.core.periodic_table", 
                    "@class": "Element", 
                    "element": "Lu"
                }
            ], 
            "properties": {}
        }, 
        {
            "label": "Al", 
            "xyz": [
                0.7901645661928071, 
                2.2349228920330417, 
                4.10581552495969
            ], 
            "abc": [
                0.0, 
                0.5, 
                0.5
            ], 
            "species": [
                {
                    "occu": 1.0, 
                    "@module": "pymatgen.core.periodic_table", 
                    "@class": "Element", 
                    "element": "Al"
                }
            ], 
            "properties": {}
        }, 
        {
            "label": "Al", 
            "xyz": [
                3.1606582647712282, 
                2.2349228920330417, 
                5.474420699946252
            ], 
            "abc": [
                0.5, 
                0.5, 
                0.5
            ], 
            "species": [
                {
                    "occu": 1.0, 
                    "@module": "pymatgen.core.periodic_table", 
                    "@class": "Element", 
                    "element": "Al"
                }
            ], 
            "properties": {}
        }, 
        {
            "label": "Al", 
            "xyz": [
                3.1606582647712282, 
                2.2349228920330417, 
                2.7372103499731266
            ], 
            "abc": [
                0.5, 
                0.5, 
                0.0
            ], 
            "species": [
                {
                    "occu": 1.0, 
                    "@module": "pymatgen.core.periodic_table", 
                    "@class": "Element", 
                    "element": "Al"
                }
            ], 
            "properties": {}
        }
    ], 
    "lattice": {
        "a": 5.474420699946252, 
        "c": 5.474420699946252, 
        "b": 5.474420699946252, 
        "matrix": [
            [
                4.740987397156842, 
                0.0, 
                2.7372103499731266
            ], 
            [
                1.5803291323856141, 
                4.4698457840660835, 
                2.7372103499731266
            ], 
            [
                0.0, 
                0.0, 
                5.474420699946252
            ]
        ], 
        "@module": "pymatgen.core.lattice", 
        "volume": 116.01109062200008, 
        "beta": 59.99999999999999, 
        "@class": "Lattice", 
        "alpha": 59.99999999999999, 
        "gamma": 59.99999999999999
    }, 
    "is_valid": true, 
    "formula": "Lu2 Al4"
}
```

