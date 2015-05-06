##  mongodb - update if current

* findAndModify
* 'update if current' pattern:
1. Retrieve data
2. Use 'version' for tracking if document is current
2. Make modification to the MongoDB only if 'version' matches

source: 
http://docs.mongodb.org/manual/tutorial/update-if-current/

note:
