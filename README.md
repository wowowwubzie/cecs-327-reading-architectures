# CECS 327 Reading Assignment: Architectures

# Assignment Description
Answer the following questions from the Chapter 2 reading from your textbook. Be complete with your answers. You may work on these questions with one or two other partners, but all students must submit the document individually in their own repositories along with each student's name documented with the submission.

1. What is a three-tiered client-server architecture?
2. What is the difference between a vertical distribution and a horizontal distribution?
3. If a client and a server are placed far apart, we may see network latency dominating overall performance. How can we tackle this problem?
4. Consider a chain of processes $P_{1}, P_{2}, \ldots, P_{n}$ implementing a multitiered client-server architecture. Process $P_{i}$ is client of process $P_{i}+1$, and $P_{i}$ will return a reply to $P_{i}-1$ only after receiving a reply from $P_{i}+1$. What are the main problems with this organization when taking a look at the request-reply performance at process $P_{1}$?
5. In a structured overlay network, messages are routed according to the topology of the overlay. What is an important disadvantage of this approach?
6. Consider an unstructured overlay network in which each node randomly chooses $c$ neighbors. If $P$ and $Q$ are both neighbors of $R$, what is the probability that they are also neighbors of each other?
7. Not every node in a peer-to-peer network should become superpeer. What are reasonable requirements that a superpeer should meet?
8. Give an example of a self-managing system in which the analysis component is completely distributed or even hidden.
9. Consider a BitTorrent system in which each node has an outgoing link with a bandwidth capacity $B_{out}$ and an incoming link with bandwidth capacity $B_{in}$. Some of these nodes (called seeds) voluntarily offer files to be downloaded by others. What is the maximum download capacity of a BitTorrent client if we assume that it can contact at most one seed at a time?
10. Modern cars are stuffed with electronic devices. Give some 
  examples of feedback control systems in cars.

# Deliverables
Commit the answers to the questions in a readable file to your git repository by the due date and time indicated with your repository. Approved file submission formats are: plain text (\*.txt), Markdown (\*.md), PDF (\*.pdf) or web-renderable HTML (\*.html). Github will look for one of these file formats to confirm your "submission" of the assignment. Other formats will only be accepted with *explicit* approval. **NOTE: \*.docx is *not* acceptable. I will not make exceptions for this rule being violated**.
