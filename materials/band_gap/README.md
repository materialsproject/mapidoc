This root band_gap key contains the various band gaps computed using different types of calculations and with different parameters; each parameter set is one of the sub-keys. The "search_gap" sub-key is special in that it copies information from the "best" band gap that we have available. This is typically the information displayed on the MP web site. The order of band gap quality from best to worst is:

- NSCF
- static
- optimize_structure

When available, a GGA+U gap will be preferred over a GGA gap in the "search_gap" field.
