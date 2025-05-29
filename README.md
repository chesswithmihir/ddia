# Designing Data-Intensive Applications By Martin Kleppmann
## The big ideas behind reliable, scalable, and maintainable systems
### Notes by Mihir Mirchandani
---

## Table of Contents

### 1. [Reliable, Scalable, and Maintainable Applications](01.md)
- introduces terminology and approaches through this book while considering R, S, and M.
### 2. [Data Models and Query Languages](02.md)
- compares several data modesl and query languages and the tradeoffs
### 3. [Storage and Retrieval](03.md)
- internals of storage engines and looks at how db layout data on disk
- different storage engines are optimized for different workloads
- choosing the right one can have a big impact on performance
### 4. [Encoding and Evolution](04.md)
- compares various formats for data encoding (serialization)
-  examines how they fare in environments where app reqs change and schemas need to adapt over time
### 5. [Replication](05.md)
- Keeping a copy of the same data on several different nodes, potentially in different locations
- replication provides redundancy, if some nodes are unavailable, the data can still be served from the remaining nodes.
- replication can also help improve performance
### 6. [Partitioning](06.md)
- splitting a big db into smaller subsets called partitions so that different partitions can be assigned to different nodes (sharding)
### 7. [Transactions](07.md)
- Tradeoffs in distributed systems such as with transactions, where things can go wrong and what to do about it.
### 8. [The Trouble with Distributed Systems](08.md)
- limits on distributed systems
### 9. [Consistency and Consensus](09.md)
- more limits on distributed systems
### 10. [Batch Processing](10.md)
- batch-oriented dataflow systems such as MapReduce
- see how they give us good tools and principles for building large-scale data systems
### 11. [Stream Processing](11.md)
- take those ideas from batch processing and apply them to data streams which allow us to do the same kinds of things with lower delays.
### 12. [The Future of Data Systems](12.md)
- exploring ideas about how we might use these tools to build reliable, scalable, and maintainable applications in the future.

> This book is awesome. It bridges the huge gap between distributed systems theory and practical engineering. I wish it had existed a decade ago, so I could have read it then and saved myself all the mistakes along the way. <br>
-Jay Kreps (Creator of Apache Kafka and CEO of Confluent, now BOD member for Anthropic)

> This book should be required reading for software engineers. DDIA is a rare resource that connects theory and practice to help developers make smart decisions as they design and implement data infrastructure and systems. <br>
-Kevin Scott (CTO of Microsoft)

Martin Kleppmann is a researcher in distributed systems at the University of Cambridge, UK. Previously, he was a SWE at Linkedin and Rapportive, where he worked on large-scale data infrastructure. Martin is a regular conference speaker, blogger, and open source contributor.





