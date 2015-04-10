A dict of the various input (crystal, incar, etc.) to the calculations.





## Example output in JSON

```json
{
    "crystal": {
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
    }, 
    "lattice_rec": {
        "a": 0.22313775167982355, 
        "c": 0.22313774810301865, 
        "b": 0.22313775, 
        "matrix": [
            [
                0.21037629, 
                -0.07437925, 
                0.0
            ], 
            [
                0.0, 
                0.22313775, 
                0.0
            ], 
            [
                -0.10518814, 
                -0.07437925, 
                0.18219121
            ]
        ], 
        "@module": "pymatgen.core.lattice", 
        "volume": 0.008552582295098518, 
        "beta": 109.47121982783757, 
        "@class": "Lattice", 
        "alpha": 109.47122080670438, 
        "gamma": 109.47122048199125
    }, 
    "parameters": {
        "NELMDL": -5, 
        "LMUSIC": false, 
        "WC": 100.0, 
        "LCHIMAG": false, 
        "INIWAV": 1, 
        "APACO": 16.0, 
        "IBRION": 2, 
        "ICORELEVEL": 0, 
        "MODEL_GW": 0, 
        "LSCAAWARE": false, 
        "LDIPOL": false, 
        "ENCUTFOCK": 0.0, 
        "LRPA": true, 
        "HFSCREEN": 0.0, 
        "MAXMIX": -45, 
        "EMAX": -10.0, 
        "LBERRY": false, 
        "ENAUG": 298.798, 
        "LHFONE": false, 
        "ISYM": 2, 
        "MODEL_ALPHA": 1.0, 
        "AEXX": 0.0, 
        "LTCTE": false, 
        "IDIOT": 3, 
        "LELF": false, 
        "HFALPHA": 0.0, 
        "NBANDS": 25, 
        "LMAXPAW": -100, 
        "LSPIRAL": false, 
        "ISMEAR": 1, 
        "ENCUTGWSOFT": -2.0, 
        "EBREAK": 2e-08, 
        "IWAVPR": 11, 
        "WEIMIN": 0.001, 
        "NEDOS": 301, 
        "LCOMPAT": false, 
        "FOURORBIT": 0, 
        "LVEL": false, 
        "LDAU": false, 
        "LMAXMIX": 2, 
        "NOMEGAR": 0, 
        "ODDONLYGW": false, 
        "ISPIN": 2, 
        "GGA_COMPAT": true, 
        "BMIX_MAG": 1.0, 
        "NMAXFOCKAE": 0, 
        "SYMPREC": 1e-05, 
        "LVTOT": false, 
        "TEEND": 0.0001, 
        "AVECCONST": [
            0.0, 
            0.0, 
            0.0
        ], 
        "MAGDIPOL": [
            0.0, 
            0.0, 
            0.0
        ], 
        "ODDONLY": false, 
        "ORBITALMAG": false, 
        "EDIFFG": 2e-05, 
        "LZEROZ": false, 
        "NGX": 42, 
        "NGY": 42, 
        "LASYNC": false, 
        "ROPT": [
            -0.00025, 
            -0.00025
        ], 
        "NBLOCK": 1, 
        "LMAGBLOCH": false, 
        "NRMM": 4, 
        "NBANDSLF": -1, 
        "IDIPOL": 0, 
        "HFSCREENC": 0.0, 
        "EVENONLYGW": false, 
        "LRHFCALC": false, 
        "EFERMI": 0.0, 
        "LREAL_COMPAT": false, 
        "OMEGATL": -200.0, 
        "EDIFF": 2e-06, 
        "LEPSILON": false, 
        "EFIELD": 0.0, 
        "DIPOL": [
            -100.0, 
            -100.0, 
            -100.0
        ], 
        "MAGMOM": [
            0.6, 
            0.6, 
            0.6, 
            0.6, 
            5.0, 
            5.0
        ], 
        "LSORBIT": false, 
        "NUPDOWN": -1.0, 
        "NELMIN": 3, 
        "LTHOMAS": false, 
        "LSCALAPACK": false, 
        "NBLK": 32, 
        "NFREE": 1, 
        "ENCUT4O": -1.0, 
        "EVENONLY": false, 
        "NELECT": 30.0, 
        "LMAXMP2": -1, 
        "LCORR": true, 
        "EXXOEP": 0, 
        "AMIX": 0.4, 
        "TIME": 0.4, 
        "LORBIT": false, 
        "ICHARG": 1, 
        "ADDGRID": false, 
        "QSPIRAL": [
            0.0, 
            0.0, 
            0.0
        ], 
        "AGGAX": 1.0, 
        "NKREDLFX": 1, 
        "NKREDLFY": 1, 
        "NKREDLFZ": 1, 
        "IALGO": 68, 
        "NELM": 100, 
        "LPARD": false, 
        "PSTRESS": 0.0, 
        "LMODELHF": false, 
        "CSHIFT": -0.1, 
        "NGYF": 84, 
        "DEPER": 0.3, 
        "LWAVE": true, 
        "SELFENERGY": false, 
        "NGZ": 42, 
        "NPACO": 256, 
        "LASPH": false, 
        "LSPECTRAL": false, 
        "ENCUTLF": -1.0, 
        "EMIN": 10.0, 
        "LSCALU": false, 
        "KINTER": 0, 
        "NSIM": 4, 
        "ISIF": 3, 
        "MODEL_EPS0": 11.60110906, 
        "I_CONSTRAINED_M": 0, 
        "GGA": "--", 
        "TEBEG": 0.0001, 
        "NGXF": 84, 
        "LTETE": false, 
        "NBANDSGW": -1, 
        "MREMOVE": 5, 
        "INIMIX": 1, 
        "AMIN": 0.1, 
        "NGZF": 84, 
        "LMETAGGA": false, 
        "NPAR": 1, 
        "LUSEW": false, 
        "LGWLF": false, 
        "MIXPRE": 1, 
        "MAXMEM": 1024, 
        "ALDAC": 1.0, 
        "L2ORDER": false, 
        "OMEGAGRID": 0, 
        "PREC": "Accura", 
        "NWRITE": 2, 
        "ALDAX": 1.0, 
        "POMASS": [
            26.982, 
            174.967
        ], 
        "LHFCALC": false, 
        "SHIFTRED": false, 
        "DIM": 3, 
        "LGAUGE": true, 
        "NKREDX": 1, 
        "NKREDY": 1, 
        "NKREDZ": 1, 
        "VOSKOWN": 0, 
        "LNABLA": false, 
        "SMASS": -3.0, 
        "ENMAX": 520.0, 
        "AMIX_MAG": 1.6, 
        "RWIGS": [
            -1.0, 
            -1.0
        ], 
        "BMIX": 1.0, 
        "ISTART": 0, 
        "AGGAC": 1.0, 
        "SIGMA": 0.2, 
        "LDIAG": true, 
        "LMONO": false, 
        "SAXIS": [
            0.0, 
            0.0, 
            1.0
        ], 
        "LOPTICS": false, 
        "POTIM": 0.5, 
        "LMAXFOCK": 0, 
        "NSW": 200, 
        "ENCUTGW": 346.66666667, 
        "STM": [
            0.0, 
            0.0, 
            0.0, 
            0.0, 
            0.0
        ], 
        "NOMEGA": 0, 
        "SCISSOR": 0.0, 
        "LPLANE": true, 
        "LREAL": true, 
        "KBLOCK": 200, 
        "TELESCOPE": 0, 
        "MAGATOM": 0, 
        "LCHARG": true, 
        "EPSILON": 1.0, 
        "LNONCOLLINEAR": false, 
        "OMEGAMAX": -30.0, 
        "SYSTEM": "Rubyvaspy :: al lu", 
        "IMIX": 4, 
        "ENINI": 520.0, 
        "ANTIRES": 0
    }, 
    "incar": {
        "NELM": 100, 
        "ISPIN": 2, 
        "PREC": "Accurate", 
        "IBRION": 2, 
        "LREAL": "Auto", 
        "LCALCEPS": false, 
        "ISMEAR": 1, 
        "LWAVE": true, 
        "SIGMA": 0.2, 
        "LPEAD": false, 
        "MAGMOM": [
            0.6, 
            0.6, 
            0.6, 
            0.6, 
            5.0, 
            5.0
        ], 
        "NELMIN": 3, 
        "LEFG": false, 
        "SYSTEM": "Rubyvaspy :: al lu", 
        "ENCUT": 520.0, 
        "EFIELD_PEAD": [
            0.0, 
            0.0, 
            0.0
        ], 
        "ISIF": 3, 
        "ICHARG": 1, 
        "ALGO": "Fast", 
        "LCALCPOL": false, 
        "EDIFF": 2e-06, 
        "NSW": 200
    }, 
    "kpoints": {
        "comment": "Kpoints from vasprun.xml", 
        "usershift": [
            0.0, 
            0.0, 
            0.0
        ], 
        "kpoints": [
            [
                6, 
                6, 
                6
            ]
        ], 
        "actual_points": [
            {
                "abc": [
                    0.08333333, 
                    0.08333333, 
                    0.08333333
                ], 
                "weight": 0.00925926
            }, 
            {
                "abc": [
                    0.25, 
                    0.08333333, 
                    0.08333333
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    0.41666667, 
                    0.08333333, 
                    0.08333333
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    -0.41666667, 
                    0.08333333, 
                    0.08333333
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    -0.25, 
                    0.08333333, 
                    0.08333333
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    -0.08333333, 
                    0.08333333, 
                    0.08333333
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    0.25, 
                    0.25, 
                    0.08333333
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    0.41666667, 
                    0.25, 
                    0.08333333
                ], 
                "weight": 0.05555556
            }, 
            {
                "abc": [
                    -0.41666667, 
                    0.25, 
                    0.08333333
                ], 
                "weight": 0.05555556
            }, 
            {
                "abc": [
                    -0.25, 
                    0.25, 
                    0.08333333
                ], 
                "weight": 0.05555556
            }, 
            {
                "abc": [
                    -0.08333333, 
                    0.25, 
                    0.08333333
                ], 
                "weight": 0.05555556
            }, 
            {
                "abc": [
                    0.41666667, 
                    0.41666667, 
                    0.08333333
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    -0.41666667, 
                    0.41666667, 
                    0.08333333
                ], 
                "weight": 0.05555556
            }, 
            {
                "abc": [
                    -0.25, 
                    0.41666667, 
                    0.08333333
                ], 
                "weight": 0.05555556
            }, 
            {
                "abc": [
                    -0.08333333, 
                    0.41666667, 
                    0.08333333
                ], 
                "weight": 0.05555556
            }, 
            {
                "abc": [
                    -0.41666667, 
                    -0.41666667, 
                    0.08333333
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    -0.25, 
                    -0.41666667, 
                    0.08333333
                ], 
                "weight": 0.05555556
            }, 
            {
                "abc": [
                    -0.25, 
                    -0.25, 
                    0.08333333
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    0.25, 
                    0.25, 
                    0.25
                ], 
                "weight": 0.00925926
            }, 
            {
                "abc": [
                    0.41666667, 
                    0.25, 
                    0.25
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    -0.41666667, 
                    0.25, 
                    0.25
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    -0.25, 
                    0.25, 
                    0.25
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    0.41666667, 
                    0.41666667, 
                    0.25
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    -0.41666667, 
                    0.41666667, 
                    0.25
                ], 
                "weight": 0.05555556
            }, 
            {
                "abc": [
                    -0.25, 
                    0.41666667, 
                    0.25
                ], 
                "weight": 0.05555556
            }, 
            {
                "abc": [
                    -0.41666667, 
                    -0.41666667, 
                    0.25
                ], 
                "weight": 0.02777778
            }, 
            {
                "abc": [
                    0.41666667, 
                    0.41666667, 
                    0.41666667
                ], 
                "weight": 0.00925926
            }, 
            {
                "abc": [
                    -0.41666667, 
                    0.41666667, 
                    0.41666667
                ], 
                "weight": 0.02777778
            }
        ], 
        "@module": "pymatgen.io.vaspio.vasp_input", 
        "nkpoints": 0, 
        "generation_style": "Monkhorst-Pack", 
        "genvec2": [
            0.0, 
            0.16666667, 
            0.0
        ], 
        "genvec1": [
            0.16666667, 
            0.0, 
            0.0
        ], 
        "shift": [
            0.5, 
            0.5, 
            0.5
        ], 
        "genvec3": [
            0.0, 
            0.0, 
            0.16666667
        ], 
        "@class": "Kpoints"
    }, 
    "potcar": [
        "Al", 
        "Lu_3"
    ]
}
```

