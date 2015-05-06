##  MongoDB locking

* old MMapV1 (pre 2.8)
* new MMapV1 (3.x+)
* WiredTiger
note:

old uses db locking</br>
new uses collection locking</br>
WiredTiger uses optimistic locking on a document level</br>
locking is not as long as for RDBMs</br>
