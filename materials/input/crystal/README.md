The input structure to the relaxation calculation in pymatgen's 
Structure.as_dict() format.











## Example response in JSON

```json
{
    "lattice": {
        "a": 5.474420702421935, 
        "c": 5.4744207, 
        "b": 5.474420695951078, 
        "matrix": [
            [
                4.7409874, 
                0.0, 
                2.73721035
            ], 
            [
                1.58032913, 
                4.46984578, 
                2.73721035
            ], 
            [
                0.0, 
                0.0, 
                5.4744207
            ]
        ], 
        "@module": "pymatgen.core.lattice", 
        "volume": 116.01109058717881, 
        "beta": 60.00000001463479, 
        "@class": "Lattice", 
        "alpha": 59.99999997553398, 
        "gamma": 60.000000005542695
    }, 
    "sites": [
        {
            "label": "Al", 
            "xyz": [
                3.160658265, 
                2.23492289, 
                5.4744207
            ], 
            "abc": [
                0.5, 
                0.5, 
                0.5
            ], 
            "species": [
                {
                    "occu": 1, 
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
                3.160658265, 
                2.23492289, 
                2.73721035
            ], 
            "abc": [
                0.5, 
                0.5, 
                0.0
            ], 
            "species": [
                {
                    "occu": 1, 
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
                0.790164565, 
                2.23492289, 
                4.105815525
            ], 
            "abc": [
                0.0, 
                0.5, 
                0.5
            ], 
            "species": [
                {
                    "occu": 1, 
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
                2.3704937, 
                0.0, 
                4.105815525
            ], 
            "abc": [
                0.5, 
                0.0, 
                0.5
            ], 
            "species": [
                {
                    "occu": 1, 
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
                5.53115196375, 
                3.9111150575, 
                9.580236225
            ], 
            "abc": [
                0.875, 
                0.875, 
                0.875
            ], 
            "species": [
                {
                    "occu": 1, 
                    "@module": "pymatgen.core.periodic_table", 
                    "@class": "Element", 
                    "element": "Lu"
                }
            ], 
            "properties": {}
        }, 
        {
            "label": "Lu", 
            "xyz": [
                0.79016456625, 
                0.5587307225, 
                1.368605175
            ], 
            "abc": [
                0.125, 
                0.125, 
                0.125
            ], 
            "species": [
                {
                    "occu": 1, 
                    "@module": "pymatgen.core.periodic_table", 
                    "@class": "Element", 
                    "element": "Lu"
                }
            ], 
            "properties": {}
        }
    ], 
    "@class": "Structure", 
    "@module": "pymatgen.core.structure"
}
```

