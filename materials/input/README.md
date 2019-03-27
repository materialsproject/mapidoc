A dict of the various input (crystal, incar, etc.) to the calculations.







































## Example response in JSON

```json
{
    "crystal": {
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
    },
    "incar": {
        "@class": "Incar",
        "@module": "pymatgen.io.vasp.inputs",
        "ALGO": "Normal",
        "AMIX": 0.2,
        "AMIX_MAG": 0.8,
        "BMIX": 0.001,
        "BMIX_MAG": 0.001,
        "ENCUT": 520,
        "IBRION": 2,
        "ICHARG": 1,
        "ISIF": 3,
        "ISMEAR": 1,
        "ISPIN": 2,
        "LREAL": "Auto",
        "LWAVE": true,
        "MAGMOM": [
            0.6,
            0.6
        ],
        "NELM": 100,
        "NELMDL": 6,
        "NELMIN": 3,
        "NPAR": 1,
        "NSW": 200,
        "PREC": "Accurate",
        "SIGMA": 0.2,
        "SYSTEM": "Rubyvaspy :: p in"
    },
    "kpoints": {
        "@class": "Kpoints",
        "@module": "pymatgen.io.vasp.inputs",
        "comment": "Automatic kpoint scheme",
        "coord_type": null,
        "generation_style": "Monkhorst",
        "kpoints": [
            [
                8,
                8,
                8
            ]
        ],
        "kpts_weights": null,
        "labels": null,
        "nkpoints": 0,
        "tet_connections": null,
        "tet_number": 0,
        "tet_weight": 0,
        "usershift": [
            0,
            0,
            0
        ]
    },
    "potcar_spec": [
        {
            "hash": "7dc3393307131ae67785a0cdacb61d5f",
            "titel": "PAW_PBE P 17Jan2003"
        },
        {
            "hash": "b87558aef4b20a3c4a008ff3e8775108",
            "titel": "PAW_PBE In_d 06Sep2000"
        }
    ]
}
```

