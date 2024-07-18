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
3. If a client and a server are placed far apart, we may see network latency dominating overall performance. How can we tackle this problem? 
- A solution to this problem is to develop edge infrastructure, which is considered to be close to the end devices. According to page 102, closeness of service to end devices, which could be a laptop, tablet, printer, etc. is needed, and the closer the service is to the device, the latency will get smaller. Edge computing takes into account the placement of services at the end boundary of the network space, meaning that if a person was using the internet not as close to the center of the network, the edge aspect of the infrastructure will make sure that the internet service will work the same even if the person is farther away from the source.
---
4. Consider a chain of processes 𝑃1,𝑃2,…,𝑃𝑛 implementing a multitiered client-server architecture. Process 𝑃𝑖 is client of process 𝑃𝑖+1, and 𝑃𝑖 will return a reply to 𝑃𝑖−1only after receiving a reply from 𝑃𝑖+1 . What are the main problems with this organization when taking a look at the request-reply performance at process 𝑃1 ? 
- This organization leads to high latency problems. Since each process Pi waits for the reply from Pi+1, any delay in the processing of Pi+1 will then lead to a delay in getting the data to Pi to return to Pi-1. It is a chained event from one process to the next, so any mishaps will cause timing issues.
---
5. In a structured overlay network, messages are routed according to the topology of the overlay. What is an important disadvantage of this approach? 
- An important disadvantage to this approach is that the number of nodes is not fixed. Any changes in the number of routing paths and network, such as other nodes joining and or leaving, will requiem the structure to adjust in order to maintain.
---
6. Consider an unstructured overlay network in which each node randomly chooses 𝑐 neighbors. If 𝑃 and 𝑄 are both neighbors of 𝑅 , what is the probability that they are also neighbors of each other? 
- The probability that P and Q are neighbors of each other in an unstructured overlay network is based off random graph model, so he probability is determined by the probability distribution since the neighbors are chosen randomly. This meaning that the probability can vary widely and is not fixed. 
---
7. Not every node in a peer-to-peer network should become superpeer. What are reasonable requirements that a superpeer should meet? 
- On page 95 of the textbook it states that a super peer should be a “long lived process with high-availability”, meaning that super peer must be able to able to support weaker peers in their network. They should also be cable of handling additional load, and maintaining directories. 
---
8. Give an example of a self-managing system in which the analysis component is completely distributed or even hidden. 
- The textbook mentions a BitTorrent system, which is a self-managing system with a distributed analysis. For this system, each node autonomously manages the download and upload rates based on the seeds or nodes. 
---
9. Consider a BitTorrent system in which each node has an outgoing link with a bandwidth capacity 𝐵𝑜𝑢𝑡 and an incoming link with bandwidth capacity 𝐵𝑖𝑛. Some of these nodes (called seeds) voluntarily offer files to be downloaded by others. What is the maximum download capacity of a BitTorrent client if we assume that it can contact at most one seed at a time? 
- The maximum download capacity of a BitTorrent client if we assume that it can contact at most one seed at a time would be dependent on the incoming and outcoming bandwidth that the seed. Since the BitTorrent client is only capable of downloading data one seed at a time then it would choose the seed with the highest outgoing bandwidth, so that the download speed is faster. Although, the speed is limited due to the incoming bandwidth which determines the rate at which data can be received. 
---
10. Modern cars are stuffed with electronic devices. Give some examples of feedback control systems in cars
- Adaptive cruise control: This control system allows cars to maintain a constant speed by comparing the vehicle's speed to the desired speed and adjusting the throttle according to the feedback received. 
- Lane-keeping assist: This control system uses sensors and cameras to detect lanes and different floor markings while driving. When the vehicle crosses or is close to crossing these markings, the car's control system will help direct the car so that it stays in a singular lane. This feedback received from the cars’ cameras and sensors allows the car to adjust to the proper conduct. 
