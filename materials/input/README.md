A dict of the various input (crystal, incar, etc.) to the calculations.















































## Example response in JSON

```json
{
    "crystal": {
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
    },
    "incar": {
        "@class": "Incar",
        "@module": "pymatgen.io.vasp.inputs",
        "ALGO": "Fast",
        "EDIFF": 2e-06,
        "ENCUT": 520,
        "IBRION": 2,
        "ICHARG": 1,
        "ISIF": 3,
        "ISMEAR": -5,
        "ISPIN": 2,
        "LREAL": "Auto",
        "LWAVE": true,
        "MAGMOM": [
            0.6,
            0.6,
            0.6
        ],
        "NELM": 100,
        "NELMIN": 3,
        "NPAR": 1,
        "NSW": 200,
        "PREC": "Accurate",
        "SIGMA": 0.05,
        "SYSTEM": "Rubyvaspy :: te"
    },
    "kpoints": {
        "@class": "Kpoints",
        "@module": "pymatgen.io.vasp.inputs",
        "comment": "Automatic kpoint scheme",
        "coord_type": null,
        "generation_style": "Gamma",
        "kpoints": [
            [
                8,
                8,
                6
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
            "hash": "72719856e22fb1d3032df6f96d98a0f2",
            "titel": "PAW_PBE Te 08Apr2002"
        }
    ]
}
```

