The final relaxed structure in a dict format. This dict follows pymatgen's as_dict() protocol and can be deserialized to a pymatgen Structure object using Structure.from_dict.

## Example output

```json
{"lattice": {"a": 3.92384391, "c": 3.92384391, "b": 3.92384391, "matrix": [[3.92384391, 0.0, 0.0], [0.0, 3.92384391, 0.0], [0.0, 0.0, 3.92384391]], "volume": 60.41366299424273, "beta": 90.0, "alpha": 90.0, "gamma": 90.0}, "sites": [{"label": "Al", "xyz": [0.0, 0.0, 0.0], "abc": [0.0, 0.0, 0.0], "species": [{"occu": 1, "element": "Al"}], "properties": {"coordination_no": 12, "forces": [0.0, 0.0, 0.0]}}, {"label": "Pt", "xyz": [0.0, 1.961921955, 1.961921955], "abc": [0.0, 0.5, 0.5], "species": [{"occu": 1, "element": "Pt"}], "properties": {"coordination_no": 12, "forces": [0.0, 0.0, 0.0]}}, {"label": "Pt", "xyz": [1.961921955, 1.961921955, 0.0], "abc": [0.5, 0.5, 0.0], "species": [{"occu": 1, "element": "Pt"}], "properties": {"coordination_no": 12, "forces": [0.0, 0.0, 0.0]}}, {"label": "Pt", "xyz": [1.961921955, 0.0, 1.961921955], "abc": [0.5, 0.0, 0.5], "species": [{"occu": 1, "element": "Pt"}], "properties": {"coordination_no": 12, "forces": [0.0, 0.0, 0.0]}}], "@class": "Structure", "@module": "pymatgen.core.structure"}
```

