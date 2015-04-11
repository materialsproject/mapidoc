

## Example response in JSON

```json
{
    "created_at": "2013-05-13T23:55:57.648", 
    "_icsd": {}, 
    "_materialsproject": {
        "deprecated": {
            "mps_ids": [
                84536
            ]
        }, 
        "snl_id": 127619, 
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
        }, 
        {
            "url": "http://www.materialsproject.org", 
            "description": {
                "fw_id": null, 
                "task_type": "GGA optimize structure (2x)", 
                "task_id": "mp-1234"
            }, 
            "name": "Materials Project structure optimization"
        }
    ]
}
```

