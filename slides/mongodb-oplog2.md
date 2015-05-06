##  mongodb - oplog2

```javascript
{
"ts" : Timestamp(1395663575, 1),
"h" : NumberLong("-5872498803080442915"),
"v" : 2,
"op" : "i",
"ns" : "wiktory.items",
"o" : {
    "_id" : ObjectId("533022d70d7e2c31d4490d22"),
        "author" : "JRR Hartley",
	    "title" : "Flyfishing"
        }
}
```
source: https://blog.compose.io/the-mongodb-oplog-and-node-js/
note:
ts - timestamp; h - id of an operation; v - version of oplog format</br>
op - i/u/d c/db (database) n=no-op</br>
o/o2 - for update</br>

