The final relaxed structure in a dict format. This dict follows pymatgen's as_dict() protocol and can be deserialized to a pymatgen Structure object using Structure.from_dict.







































## Example response in JSON

```json
{
    "@class": "Structure",
    "@module": "pymatgen.core.structure",
    "charge": null,
    "lattice": {
        "a": 4.212040679434068,
        "alpha": 59.99999997418664,
        "b": 4.212040676713186,
        "beta": 59.999999995555385,
        "c": 4.21204068,
        "gamma": 59.99999997566818,
        "matrix": [
            [
                3.64773423,
                0.0,
                2.10602034
            ],
            [
                1.21591141,
                3.43911681,
                2.10602034
            ],
            [
                0.0,
                0.0,
                4.21204068
            ]
        ],
        "volume": 52.83998339624193
    },
    "sites": [
        {
            "abc": [
                0.25,
                0.25,
                0.25
            ],
            "label": "P",
            "properties": {
                "magmom": 0.0
            },
            "species": [
                {
                    "element": "P",
                    "occu": 1
                }
            ],
            "xyz": [
                1.21591141,
                0.8597792025,
                2.10602034
            ]
        },
        {
            "abc": [
                0.0,
                0.0,
                0.0
            ],
            "label": "In",
            "properties": {
                "magmom": 0.0
            },
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

