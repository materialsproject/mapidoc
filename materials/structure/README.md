The final relaxed structure in a dict format. This dict follows pymatgen's as_dict() protocol and can be deserialized to a pymatgen Structure object using Structure.from_dict.





## Example output in JSON

```json
{
    "lattice": {
        "a": 5.488739045730133, 
        "c": 5.48873905, 
        "b": 5.488739048031658, 
        "matrix": [
            [
                4.75338745, 
                0.0, 
                2.74436952
            ], 
            [
                1.58446248, 
                4.48153667, 
                2.74436952
            ], 
            [
                0.0, 
                0.0, 
                5.48873905
            ]
        ], 
        "volume": 116.92375473740876, 
        "beta": 60.00000003453459, 
        "alpha": 60.0000000484055, 
        "gamma": 60.000000071689925
    }, 
    "sites": [
        {
            "label": "Al", 
            "xyz": [
                3.168924965, 
                2.240768335, 
                5.488739045
            ], 
            "abc": [
                0.5, 
                0.5, 
                0.5
            ], 
            "species": [
                {
                    "occu": 1, 
                    "element": "Al"
                }
            ], 
            "properties": {
                "coordination_no": 10, 
                "forces": [
                    0.0, 
                    0.0, 
                    0.0
                ]
            }
        }, 
        {
            "label": "Al", 
            "xyz": [
                3.168924965, 
                2.240768335, 
                2.74436952
            ], 
            "abc": [
                0.5, 
                0.5, 
                0.0
            ], 
            "species": [
                {
                    "occu": 1, 
                    "element": "Al"
                }
            ], 
            "properties": {
                "coordination_no": 10, 
                "forces": [
                    0.0, 
                    0.0, 
                    0.0
                ]
            }
        }, 
        {
            "label": "Al", 
            "xyz": [
                0.79223124, 
                2.240768335, 
                4.116554285
            ], 
            "abc": [
                0.0, 
                0.5, 
                0.5
            ], 
            "species": [
                {
                    "occu": 1, 
                    "element": "Al"
                }
            ], 
            "properties": {
                "coordination_no": 10, 
                "forces": [
                    0.0, 
                    0.0, 
                    0.0
                ]
            }
        }, 
        {
            "label": "Al", 
            "xyz": [
                2.376693725, 
                0.0, 
                4.116554285
            ], 
            "abc": [
                0.5, 
                0.0, 
                0.5
            ], 
            "species": [
                {
                    "occu": 1, 
                    "element": "Al"
                }
            ], 
            "properties": {
                "coordination_no": 10, 
                "forces": [
                    0.0, 
                    0.0, 
                    0.0
                ]
            }
        }, 
        {
            "label": "Lu", 
            "xyz": [
                5.54561868875, 
                3.9213445862499996, 
                9.605293328750001
            ], 
            "abc": [
                0.875, 
                0.875, 
                0.875
            ], 
            "species": [
                {
                    "occu": 1, 
                    "element": "Lu"
                }
            ], 
            "properties": {
                "coordination_no": 16, 
                "forces": [
                    0.0, 
                    0.0, 
                    0.0
                ]
            }
        }, 
        {
            "label": "Lu", 
            "xyz": [
                0.79223124125, 
                0.56019208375, 
                1.37218476125
            ], 
            "abc": [
                0.125, 
                0.125, 
                0.125
            ], 
            "species": [
                {
                    "occu": 1, 
                    "element": "Lu"
                }
            ], 
            "properties": {
                "coordination_no": 16, 
                "forces": [
                    0.0, 
                    0.0, 
                    0.0
                ]
            }
        }
    ], 
    "@class": "Structure", 
    "@module": "pymatgen.core.structure"
}
```

