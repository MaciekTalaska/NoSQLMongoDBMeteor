##  transaction-5

```javascript
col = db.getSisterDB("bank").transactions;
col.update({_id: transaction._id}, {$set: {state: "commited"}});
```

note:
transaction state is set to committed
