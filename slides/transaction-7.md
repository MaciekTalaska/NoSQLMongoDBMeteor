##  transaction-7

```javascript
col = db.getSisterDB("bank").transactions;
col.update({_id: transaction._id}, {$set: {state: "done"}});
```

note:
transaction is finished, so the state is set to done
