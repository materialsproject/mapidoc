Unlike "task_id", this is a list of task_ids associated with each material. Multiple calculations (tasks) are performed for each material. Right now, you have no way of getting task data from the API yet, but in future, this would be the way you get a task_id for further exploration of specific tasks.

Each entry in "task\_ids" is unique to that material - i.e., the same task\_id will not be repeated for multiple materials. Another way to say it is that the task\_ids arrays for two materials are disjoint.






































## Example response in JSON

```json
[
    "mp-673248",
    "mp-657140",
    "mp-657129",
    "mp-657134",
    "mp-20351",
    "mp-1059583",
    "mp-1059600",
    "mp-1059637",
    "mp-1059643",
    "mp-1060956",
    "mp-1060980",
    "mp-1061021",
    "mp-1061027",
    "mp-1114738",
    "mp-1142286"
]
```

