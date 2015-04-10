## Example response in JSON

```json
{
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
}
```

## Example response in JSON

```json
{
    "mps_ids": [
        84536
    ]
}
```

