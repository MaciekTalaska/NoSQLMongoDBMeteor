##  transaction-2

<pre>
<code class="javascript">
col = db.getSisterDB("bank").transactions;
col.insert({source: "Joe", destination: "Peter", amount: 100, state: "intital"});
</code>
</pre>

note:
transaction is being created
