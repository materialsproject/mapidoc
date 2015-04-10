This root key contains the various band gaps computed using different types of calculations and with different parameters; each parameter set is one of the sub-keys. The `search_gap` sub-key is special in that it copies information from the "best" band gap that we have available. This is typically the information displayed on the MP web site. The order of band gap quality from best to worst is:

1. NSCF

    Kohn-Sham band gap using the GGA functional, calculated using a static structure and static charge density on a high-density k-point mesh.

2. static

    Kohn-Sham band gap using the GGA functional, calculated during an charge optimization run on a static structure with intermediate k-point mesh.

3. optimize_structure

    Kohn-Sham band gap using the GGA functional, calculated during a structure optimization run on a lower density k-point mesh.

When available, a GGA+U gap will be preferred over a GGA gap in the `search_gap` field.

## Example output in JSON

```json
{"optimize_structure_gap": {"band_gap": 0.03989999999999938, "is_direct": false}, "search_gap": {"band_gap": 0.03989999999999938, "is_direct": false}}
```