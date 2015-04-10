For thermodynamically stable materials (e_above_hull=0), this field is set to None.

For thermodynamically unstable materials, this field contains a description of the most favorable theromdynamic decomposition known from the data set. This takes the form of a list of dictionaries containing {amount, formula, task_id} keys.



## Example output in JSON

```json
[
    {
        "formula": "Al4 Pt12", 
        "amount": 1.0, 
        "task_id": "mp-607111"
    }
]
```

