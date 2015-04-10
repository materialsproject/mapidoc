This field contains sub-keys for the various methodologies (GGA/GGA+U). Within each methodology is stored a pointer to a pymatgen band structure object that is stored in a GridFS (fs_id key). Thus, these sub-keys contain a link to the band structure object, but not the object itself.

This band structure is the "line mode" along symmetry lines.







## Example response in JSON

```json
{
    "GGA": {
        "oid": "54fcac67c5981c67aa357cc9", 
        "fs_id": "54fc8af1d1b6dd448253ed71", 
        "task_id": "mp-940654"
    }
}
```

