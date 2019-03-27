This field contains sub-keys for the various methodologies (GGA/GGA+U). Within each methodology is stored a pointer to a pymatgen band structure object that is stored in a GridFS (fs_id key). Thus, these sub-keys contain a link to the band structure object, but not the object itself.

This band structure is the "line mode" along symmetry lines.



































## Example response in JSON

```json
{
    "GGA": {
        "task_id": "mp-657140"
    }
}
```

