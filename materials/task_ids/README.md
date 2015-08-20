Unlike "task_id", this is a list of task_ids associated with each material. Multiple calculations (tasks) are performed for each material. Right now, you have no way of getting task data from the API yet, but in future, this would be the way you get a task_id for further exploration of specific tasks.

Each entry in "task\_ids" is unique to that material - i.e., the same task\_id will not be repeated for multiple materials. Another way to say it is that the task\_ids arrays for two materials are disjoint.










## Example response in JSON

```json
[
    "mp-1234", 
    "mp-925833", 
    "mp-940234", 
    "mp-940654"
]
```

