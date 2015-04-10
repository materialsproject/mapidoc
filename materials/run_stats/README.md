CPU time needed to complete the structure optimization portion of this material. Currently, time needed for other tasks (e.g. charge re-optimization, band structure calculation, etc.) is not listed. The structure optimization is performed through two consecutive relaxations (relax1 and relax2), with the second relaxation aiding in achieving a better optimized structure.











## Example response in JSON

```json
{
    "relax1": {
        "Total CPU time used (sec)": 305.885, 
        "Elapsed time (sec)": 307.189, 
        "Maximum memory used (kb)": 0.0, 
        "Average memory used (kb)": 0.0, 
        "User time (sec)": 288.011, 
        "System time (sec)": 17.874
    }, 
    "relax2": {
        "Total CPU time used (sec)": 50.296, 
        "Elapsed time (sec)": 51.538, 
        "Maximum memory used (kb)": 0.0, 
        "Average memory used (kb)": 0.0, 
        "User time (sec)": 48.533, 
        "System time (sec)": 1.764
    }, 
    "overall": {
        "System time (sec)": 19.637999999999998, 
        "Total CPU time used (sec)": 356.181, 
        "User time (sec)": 336.54400000000004, 
        "Elapsed time (sec)": 358.72700000000003
    }
}
```

