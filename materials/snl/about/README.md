## Example response in JSON

```json
{
    "created_at": {
        "$date": 1308219015000
    }, 
    "_icsd": {
        "icsd_id": 107869, 
        "comments": [
            "Annealed at 1273 K"
        ]
    }, 
    "_materialsproject": {
        "deprecated": {
            "crystal_deprecated": {
                "lattice": {
                    "a": 3.8774999999999995, 
                    "volume": 58.298236734375, 
                    "c": 3.8774999999999995, 
                    "b": 3.8774999999999995, 
                    "alpha": 90.0, 
                    "beta": 90.0, 
                    "gamma": 90.0
                }, 
                "space_group": {
                    "hermann_mauguin": "P 1", 
                    "centering": "P", 
                    "crystal_system": "Triclinic", 
                    "number": 1, 
                    "point_group": "1", 
                    "is_standard": true, 
                    "schoenflies": "C1^1", 
                    "laue": "-1", 
                    "cctbx_name": "P 1", 
                    "hall": " P 1"
                }, 
                "db": {}, 
                "sites": [
                    {
                        "abc": [
                            0.0, 
                            0.0, 
                            0.0
                        ], 
                        "meta": {
                            "type": "atom"
                        }, 
                        "name": "Al", 
                        "occupancy": 1.0, 
                        "label": "Al-0"
                    }, 
                    {
                        "abc": [
                            0.0, 
                            0.5, 
                            0.5
                        ], 
                        "meta": {
                            "type": "atom"
                        }, 
                        "name": "Pt", 
                        "occupancy": 1.0, 
                        "label": "Pt-1"
                    }, 
                    {
                        "abc": [
                            0.5, 
                            0.5, 
                            0.0
                        ], 
                        "meta": {
                            "type": "atom"
                        }, 
                        "name": "Pt", 
                        "occupancy": 1.0, 
                        "label": "Pt-1"
                    }, 
                    {
                        "abc": [
                            -0.5, 
                            0.0, 
                            0.5
                        ], 
                        "meta": {
                            "type": "atom"
                        }, 
                        "name": "Pt", 
                        "occupancy": 1.0, 
                        "label": "Pt-1"
                    }
                ], 
                "transforms": [
                    {
                        "initial_space_group": {
                            "hermann_mauguin": "P m -3 m", 
                            "centering": "P", 
                            "crystal_system": "Cubic", 
                            "number": 221, 
                            "point_group": "m-3m", 
                            "is_standard": true, 
                            "schoenflies": "Oh^1", 
                            "laue": "m-3m", 
                            "cctbx_name": "P m -3 m", 
                            "hall": "-P 4 2 3"
                        }, 
                        "name": "to_niggli"
                    }, 
                    {
                        "initial_space_group": {
                            "hermann_mauguin": "P m -3 m", 
                            "centering": "P", 
                            "crystal_system": "Cubic", 
                            "number": 221, 
                            "point_group": "m-3m", 
                            "is_standard": true, 
                            "schoenflies": "Oh^1", 
                            "laue": "m-3m", 
                            "cctbx_name": "P m -3 m", 
                            "hall": "-P 4 2 3"
                        }, 
                        "name": "to_p1"
                    }
                ]
            }, 
            "original_structure_order": {
                "lattice": {
                    "a": 3.8774999999999995, 
                    "c": 3.8774999999999995, 
                    "b": 3.8774999999999995, 
                    "matrix": [
                        [
                            3.8774999999999995, 
                            0.0, 
                            2.374283981846931e-16
                        ], 
                        [
                            6.235495574121158e-16, 
                            3.8774999999999995, 
                            2.374283981846931e-16
                        ], 
                        [
                            0.0, 
                            0.0, 
                            3.8774999999999995
                        ]
                    ], 
                    "@module": "pymatgen.core.lattice", 
                    "volume": 58.29823673437498, 
                    "beta": 90.0, 
                    "@class": "Lattice", 
                    "alpha": 90.0, 
                    "gamma": 90.0
                }, 
                "sites": [
                    {
                        "label": "Al", 
                        "xyz": [
                            0.0, 
                            0.0, 
                            0.0
                        ], 
                        "abc": [
                            0.0, 
                            0.0, 
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
                    }, 
                    {
                        "label": "Pt", 
                        "xyz": [
                            3.117747787060579e-16, 
                            1.9387499999999998, 
                            1.93875
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
                                "element": "Pt"
                            }
                        ], 
                        "properties": {}
                    }, 
                    {
                        "label": "Pt", 
                        "xyz": [
                            1.93875, 
                            1.9387499999999998, 
                            2.374283981846931e-16
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
                                "element": "Pt"
                            }
                        ], 
                        "properties": {}
                    }, 
                    {
                        "label": "Pt", 
                        "xyz": [
                            1.9387499999999998, 
                            0.0, 
                            1.93875
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
                                "element": "Pt"
                            }
                        ], 
                        "properties": {}
                    }
                ], 
                "@class": "Structure", 
                "@module": "pymatgen.core.structure"
            }, 
            "mps_ids": [
                98764
            ], 
            "crystal_id_deprecated": 98764
        }, 
        "snl_id": 44422, 
        "spacegroup": {
            "lattice_type": "cubic", 
            "symbol": "Pm-3m", 
            "crystal_system": "cubic", 
            "point_group": "m-3m", 
            "hall": "-P 4 2 3", 
            "number": 221
        }
    }, 
    "references": "@misc{MaterialsProject,\ntitle = {{Materials Project}},\nurl = {http://www.materialsproject.org}\n}\n\n@article{Oya1987_235,\ntitle = {{The Pt-Al and Pt-Ga phase diagram with emphasis on the polymorphism of Pt3 Al and Pt3 Ga}},\nauthor = {Oya, Y. and Mishima, Y. and Suzuki, T.},\nyear = {1987},\njournal = {Zeitschrift fuer Metallkunde},\nvolume = {78},\nissue = {3},\npages = {485--490},\n}\n\n@article{Bergerhoff1983,\nauthor = {Bergerhoff, G. and Hundt, R. and Sievers, R. and Brown, ID},\ndoi = {10.1021/ci00038a003},\njournal = {Journal of Chemical Information and Computer Sciences},\nkeywords = {icsd},\nmendeley-tags = {icsd},\nnumber = {2},\npages = {66--69},\npublisher = {ACS Publications},\ntitle = {{The inorganic crystal structure data base}},\nurl = {http://pubs.acs.org/doi/abs/10.1021/ci00038a003},\nvolume = {23},\nyear = {1983}\n}\n@misc{Karlsruhe,\nauthor = {Karlsruhe, FIZ},\ntitle = {{Inorganic Crystal Structure Database}},\nurl = {http://icsd.fiz-karlsruhe.de}\n}\n", 
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
                "icsd_id": 107869
            }, 
            "name": "Inorganic Crystal Structure Database (ICSD)"
        }, 
        {
            "url": "http://cctbx.sourceforge.net/", 
            "description": {
                "sites": [
                    {
                        "abc": [
                            0.0, 
                            0.0, 
                            0.0
                        ], 
                        "name": "Al", 
                        "wyckoff_multiplicity": 1, 
                        "symbol": "Al", 
                        "oxidation_state": 0.0, 
                        "wyckoff": "a", 
                        "occupation": 1.0
                    }, 
                    {
                        "abc": [
                            0.0, 
                            0.5, 
                            0.5
                        ], 
                        "name": "Pt", 
                        "wyckoff_multiplicity": 3, 
                        "symbol": "Pt", 
                        "oxidation_state": 0.0, 
                        "wyckoff": "c", 
                        "occupation": 1.0
                    }
                ], 
                "lattice": {
                    "a": 3.8775, 
                    "c": 3.8775, 
                    "b": 3.8775, 
                    "volume": 58.3, 
                    "beta": 90.0, 
                    "lattice_id": 98764, 
                    "alpha": 90.0, 
                    "gamma": 90.0
                }, 
                "description": "Applied symmetry operations based on given spacegroup", 
                "spacegroup": {
                    "space_group_id": 607, 
                    "centering": "P", 
                    "icsd_name": "P m -3 m", 
                    "cctbx_name": "P m -3 m", 
                    "crystal_system": "cubic", 
                    "number": 221, 
                    "hall": "-P 4 2 3"
                }
            }, 
            "name": "Computational Crystallography Toolbox (CCTBX)"
        }, 
        {
            "url": "http://www.materialsproject.org", 
            "description": {
                "crystal_id": 98764
            }, 
            "name": "Materials Project"
        }
    ]
}
```

## Example response in JSON

```json
{
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
}
```

