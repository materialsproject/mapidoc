The snlgroup\_id is a way to track uniqueness of structures. Structures with the same snlgroup\_id will have the same atoms positioned with the same lattice and in the same positions, within a tolerance.

The snlgroup\_id of a material is the identifier for the crystal structure *before* we performed a structure optimization. i.e., if two materials have the same snlgroup\_id (should be rare), then they began with the same crystal structure.

The snlgroup\_id is used internally by the Materials Project to merge duplicated entries. See snlgroup\_id\_final for more details.

## Example response in JSON

```json
44146
```

