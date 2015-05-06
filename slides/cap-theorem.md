##  CAP theorem

<img src="../images/captheorem.png"/>

source: http://blog.flux7.com/blogs/nosql/cap-theorem-why-does-it-matter 

note:
  consistency = after successful write, all nodes return same latest value 
  availability = each request gets a response (even if this is error/fail) 
  partition tolerance = system works even if there is partial data loss/message lost, or other malfunction (internal communication routing)
