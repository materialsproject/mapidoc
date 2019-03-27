The input structure to the relaxation calculation in pymatgen's 
Structure.as_dict() format.







































## Example response in JSON

```json
{
    "@class": "Structure",
    "@module": "pymatgen.core.structure",
    "lattice": {
        "a": 4.157787873394785,
        "alpha": 59.99999993295936,
        "b": 4.157787871573669,
        "beta": 59.99999994744832,
        "c": 4.15778787,
        "gamma": 59.9999999964111,
        "matrix": [
            [
                3.60074992,
                0.0,
                2.07889394
            ],
            [
                1.20024997,
                3.39481958,
                2.07889394
            ],
            [
                0.0,
                0.0,
                4.15778787
            ]
        ],
        "volume": 50.82436788958273
    },
    "sites": [
        {
            "abc": [
                0.25,
                0.25,
                0.25
            ],
            "label": "P",
            "species": [
                {
                    "element": "P",
                    "occu": 1
                }
            ],
            "xyz": [
                1.2002499725,
                0.848704895,
                2.0788939375
            ]
        },
        {
            "abc": [
                0.0,
                0.0,
                0.0
            ],
            "label": "In",
            "species": [
                {
                    "element": "In",
                    "occu": 1
                }
            ],
            "xyz": [
                0.0,
                0.0,
                0.0
            ]
        }
    ]
}
```

