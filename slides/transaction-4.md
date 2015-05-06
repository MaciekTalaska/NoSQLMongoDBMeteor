##  transaction-4

```javascript
col = db.getSisterDB("bank").accounts;
col.update(
{name: transaction.source, pendingTransactions:{$ne: transaction._id}},
{$inc: {balance: -transaction.value}, 
 $push: {pendingTransactions: transaction._id}
});
col.update(
{name: transaction.source, pendingTransactions: {$ne: transaction._id}}, 
{$inc: {balance: transaction.value}, 
 $push: {pendingTransactions: transaction._id}
});```

note:
applying transaction to both accounts
