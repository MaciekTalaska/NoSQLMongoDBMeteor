##  transaction-3

```javascipt
col = db.getSisterDB("bank").transactions;
var transaction = col.findOne({state: "initial"});
col.update({_id: transaction._id}, {$set: {state: "pending"}});```

note:
transaction state is now being set to pending
