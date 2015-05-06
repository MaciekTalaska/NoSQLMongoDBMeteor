##  MongoDB - restrictions

* document size < 16MB
* nesting < 100 levels
* index count < 100 (per collection)
* index name < 64b
* compound index < 31 fields
* max 2^32 documents in capped collection
* DB size < 8TB/32TB
* DB name != '' && len(DB name) < 64b
