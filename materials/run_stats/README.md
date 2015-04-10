CPU time needed to complete the structure optimization portion of this material. Currently, time needed for other tasks (e.g. charge re-optimization, band structure calculation, etc.) is not listed. The structure optimization is performed through two consecutive relaxations (relax1 and relax2), with the second relaxation aiding in achieving a better optimized structure.

## Example output in JSON

```json
{"relax1": {"Total CPU time used (sec)": 78.127, "Elapsed time (sec)": 79.376, "Maximum memory used (kb)": 0.0, "Average memory used (kb)": 0.0, "User time (sec)": 75.181, "System time (sec)": 2.947}, "relax2": {"Total CPU time used (sec)": 50.006, "Elapsed time (sec)": 51.344, "Maximum memory used (kb)": 0.0, "Average memory used (kb)": 0.0, "User time (sec)": 48.302, "System time (sec)": 1.705}, "overall": {"System time (sec)": 4.652, "Total CPU time used (sec)": 128.13299999999998, "User time (sec)": 123.483, "Elapsed time (sec)": 130.72}}
```