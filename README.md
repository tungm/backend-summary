### Network
  **TCP**
  - What is it?
  - How does it work?
  - Which layer in TCP/IP or OSI model?
  - Application of TCP?

  **UDP**
  - What is it?
  - How does it work?
  - Which layer in TCP/IP or OSI model?
  - Application of UDP?

  **HTTP**
  - What is it?
  - How does it work?
  - Which layer in TCP/IP or OSI model?
  - Compare version 1.0, 1.1, 2.0, 3.0
    + Use TCP or UDP?
    + Connection state?
    + HTTP header?

  **TLS**
  - Established:
    + Handshake
    + Exchange encryption key
    + Encrypt, send, descrypt

  **Web socket**
  - What is it?
  - How does it work?
  - Which layer in TCP/IP or OSI model?
  - Schema?
  - Port?
  - Application of web socket?

  **DNS**
  - What is it?
  - How does it work?
  - Which layer in TCP/IP or OSI model?

  **Brower**
  - What happens when we access to a web page? (DNS lookup, HTTP establish,...)
    + A normal page
    + A page that does not exist

### Database:

  **Indexing**
  - Clustered vs non-clustered
  - Single vs composite index
  - How does index columns order, data type, uniqueness affect to performance? (Reseach unique first column disable other columns)
  - Tree based index vs hash table based index (and other index type if there are any)
    + What are they? Explain the DS of them (tree traversal...)
    + Hash table collision handling
    + Compare complexity of insert, delete, search,...
  - Btree vs B+tree
    + Main different in DS
    + Advantages of B+tree
    
  **DB replication and fail over configurations**

  **Replication modes**
  - Sync
  - Async
  - Write & read on master
  - Write on master, read on slave

  What is **fail over**? Explain

  What is **DB ACID**? Explain and sample for each property

  **Transaction isolation levels** and **concurrency problems**? Explain and sample for each problem

  **DB and query design for high concurrent system** (Hotel concurrently booking problem in DB)

  **OLTP and OLAP**

  (Further item: No-SQL DB, Graph DB)

### Coding/languages specific

  **Race condition and race condition handling**
  - Locking
  - Better performance solution

  **Pass by ref vs pass by value**

  **Mem stack vs mem heap**
  - Differences?
  - Which data type for stack and for heap?

  **Processes vs threads**
  - .Net async await under the hood?
  - Async await vs multi-threads programming?
  - What is shared and what is not between threads and processes?
    + (To be verified).Net threads have their own call stack? Foot print/memory utilization compare to another languages
    + Reseach more about this

  **NodeJS event loop memory and I/O advantages?**

  **Golang Go Rountine memory and I/O advantages?**

  **Unit testing**
  - Coverage rate
  - Best practice (cover all core functionallity of item)

  **High level vs low level languages? Interpreted vs compiled languages?**

  **Pointer?**

### Other/To be classified items
  - Session vs cookie
  - Token based vs session based authenticate
  - Stateless vs stateful and scalability
  - What happens when any thing in a system failed?
