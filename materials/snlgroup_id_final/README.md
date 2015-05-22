The snlgroup\_id is a way to track uniqueness of structures. Structures with the same snlgroup\_id will have the same atoms positioned with the same lattice and in the same positions, within a tolerance.

The snlgroup\_id\_final of a material is the identifier for the crystal structure *after* we performed a structure optimization. The definition of a "material" is actually based on the snlgroup\_id\_final, i.e. each material will have a unique snlgroup\_id\_final.

The snlgroup\_id is used internally by the Materials Project to merge duplicated entries, and also to merge different tasks (calculations) performed on the same material into a unified summary.

## Example response in JSON

```json
44146
```

