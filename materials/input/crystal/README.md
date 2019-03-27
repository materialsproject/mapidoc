The input structure to the relaxation calculation in pymatgen's 
Structure.as_dict() format.















































## Example response in JSON

```json
{
    "@class": "Structure",
    "@module": "pymatgen.core.structure",
    "lattice": {
        "a": 4.4593,
        "alpha": 90.0,
        "b": 4.459299997318832,
        "beta": 90.0,
        "c": 5.9282,
        "gamma": 120.0000000198893,
        "matrix": [
            [
                4.4593,
                0.0,
                0.0
            ],
            [
                -2.22965,
                3.86186708,
                0.0
            ],
            [
                0.0,
                0.0,
                5.9282
            ]
        ],
        "volume": 102.09085934520921
    },
    "sites": [
        {
            "abc": [
                0.261969,
                0.0,
                0.33333333
            ],
            "label": "Te",
            "species": [
                {
                    "element": "Te",
                    "occu": 1
                }
            ],
            "xyz": [
                1.1681983617,
                0.0,
                1.976066646906
            ]
        },
        {
            "abc": [
                0.0,
                0.261969,
                0.66666667
            ],
            "label": "Te",
            "species": [
                {
                    "element": "Te",
                    "occu": 1
                }
            ],
            "xyz": [
                -0.58409918085,
                1.0116894570805202,
                3.952133353094
            ]
        },
        {
            "abc": [
                0.738031,
                0.738031,
                0.0
            ],
            "label": "Te",
            "species": [
                {
                    "element": "Te",
                    "occu": 1
                }
            ],
            "xyz": [
                1.64555081915,
                2.85017762291948,
                0.0
            ]
        }
    ]
}
```

