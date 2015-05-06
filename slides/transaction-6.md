##  transaction-6

```javascript
col = db.getSisterDB("bank").accounts;
col.update({name: transaction.source}, 
  {$pull: {pendingTransactions: transaction._id}});
col.update({name: transaction.destination}, 
  {$pull: {pendingTransactions: transaction._id}});
```

note:
transaction is removed from accounts
