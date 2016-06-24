# Machine Programming - Membership Protocol
The membership protocol implementation will sit above EmulNet in a peer-to-peer (P2P) layer, but below an App layer. 
This protocol must satisfy: 
- Completeness all the time: every non-faulty process must detect every node join, failure, and leave
- Accuracy of failure detection when there are no message losses and message delays are small. When there are message losses, completeness must be satisfied and accuracy must be high. It must achieve all of these even under simultaneous multiple failures.
