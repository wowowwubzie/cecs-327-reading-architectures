# Reading 1
## Deanna Solis (student ID: 028309162) in collaboration with Danniella Martinez (student ID027037606)
## Due Date: 07/17/2024

1. What is a three-tiered client-server architecture? 
- A three-tiered client-server architecture is a structure used in many cases, to organize data management. It uses three layers that can be used in transaction processing, where a transaction monitor coordinates the transactions. When this layer architecture is used in websites, a ‘web server acts as an entry point to the site, passing requests to the application server, which then interacts with a database server’, as mentioned in the textbook. The application handles the information being received, the processing layer gets the information from the data layer and translates it for the application layer, and the data layer is where the data lives.
---
2. What is the difference between a vertical distribution and a horizontal distribution? 
- Vertical Distribution: it is achieved by placing logically different components on different machines. In terms of relational databases, it splits the tables column wise and distributed across many machines. Vertical distribution help in a systems-management area as functions are logically and physically split across multiple machines. Each component does its share of the work, not having equal contributions like Horizontal.
- Horizontal Distribution: this is used in more modern architectures since it is often the distribution of the clients and servers that are being accounted for. Client OR server split  in logically equal parts, but each part is operating on its own share of the whole data set, which then balances the load. Peer-to-peer is supported by horizontal distribution.
---