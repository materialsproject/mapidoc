Unlike "task_id", this is a list of task_ids associated with each material. Multiple calculations (tasks) are performed for each material. Right now, you have no way of getting task data from the API yet, but in future, this would be the way you get a task_id for further exploration of specific tasks.

Each entry in "task\_ids" is unique to that material - i.e., the same task\_id will not be repeated for multiple materials. Another way to say it is that the task\_ids arrays for two materials are disjoint.














































## Example response in JSON

```json
[
    "mp-920017",
    "mp-919016",
    "mp-906212",
    "mp-19",
    "mp-567367",
    "mp-1061888",
    "mp-1061917",
    "mp-1061880",
    "mp-1061907",
    "mp-1061969",
    "mp-1061987",
    "mp-1062004",
    "mp-1062011",
    "mp-1062278",
    "mp-1062240",
    "mp-1062254",
    "mp-1062271",
    "mp-1114745",
    "mp-1140942"
]
```

