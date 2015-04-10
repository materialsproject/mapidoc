This field contains sub-keys for the various methodologies (GGA/GGA+U). Within each methodology is stored a pointer to a pymatgen band structure object that is stored in a GridFS (fs_id key). Thus, these sub-keys contain a link to the band structure object, but not the object itself.

This band structure is a dense uniform k-point mesh (not along symmetry lines).



## Example output in JSON

```json
{
    "GGA": {
        "oid": "54fcac5dc5981c67aa357cc7", 
        "fs_id": "54fbb60d726d30329adf3d55", 
        "task_id": "mp-940234"
    }
}
```

