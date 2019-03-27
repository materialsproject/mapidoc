The final relaxed structure in a dict format. This dict follows pymatgen's as_dict() protocol and can be deserialized to a pymatgen Structure object using Structure.from_dict.















































## Example response in JSON

```json
{
    "@class": "Structure",
    "@module": "pymatgen.core.structure",
    "charge": null,
    "lattice": {
        "a": 4.51237418,
        "alpha": 90.0,
        "b": 4.512374178907963,
        "beta": 90.0,
        "c": 5.95989883,
        "gamma": 120.0000000080056,
        "matrix": [
            [
                4.51237418,
                0.0,
                0.0
            ],
            [
                -2.25618709,
                3.90783067,
                0.0
            ],
            [
                0.0,
                0.0,
                5.95989883
            ]
        ],
        "volume": 105.09443753138906
    },
    "sites": [
        {
            "abc": [
                0.26895048,
                0.0,
                0.33333333
            ],
            "label": "Te",
            "properties": {
                "magmom": 0.0
            },
            "species": [
                {
                    "element": "Te",
                    "occu": 1
                }
            ],
            "xyz": [
                1.2136052016506065,
                0.0,
                1.986632923467004
            ]
        },
        {
            "abc": [
                0.0,
                0.26895048,
                0.66666667
            ],
            "label": "Te",
            "properties": {
                "magmom": 0.0
            },
            "species": [
                {
                    "element": "Te",
                    "occu": 1
                }
            ],
            "xyz": [
                -0.6068026008253032,
                1.0510129344552215,
                3.9732659065329963
            ]
        },
        {
            "abc": [
                0.73104952,
                0.73104952,
                0.0
            ],
            "label": "Te",
            "properties": {
                "magmom": 0.0
            },
            "species": [
                {
                    "element": "Te",
                    "occu": 1
                }
            ],
            "xyz": [
                1.649384489174697,
                2.8568177355447784,
                0.0
            ]
        }
    ]
}
```

