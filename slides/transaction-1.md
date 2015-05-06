##  transaction-1

<pre>
<code class="javascript">
var col = db.getSisterDB("bank").accounts;
col.insert({name: "Joe", balance: 1000, pendingTransactions:[]});
col.insert({name: "Peter", balance: 1000, pendingTransactions:[]});
</code>
</pre>

source:

[1] http://docs.mongodb.org/manual/tutorial/perform-two-phase-commits/

[2] http://learnmongodbthehardway.com/schema/chapter9/

note:
this just creates two accounts
