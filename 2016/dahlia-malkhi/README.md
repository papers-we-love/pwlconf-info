# Dahlia Malkhi / Randomized Gossip Methods

<img src="../../assets/DahliaMalkhi.png" align="right">

A family of network protocols are built around the following "random phone call" framework:

> In a round, each player selects a communication partner among its network neighbors uniformly at random and "calls" it; the two players now connect in a protocol-specific exchange.

The talk will touch on three protocols from this family and relate them to each other:

The first, Rumor Mongering, spreads gossip in each call. This protocol was invented at Xerox PARC for the purpose of synchronizing replicas in the Clearinghouse directory service.

The second, Name Dropper, pushes new neighbors in each call. This protocol was developed at Akamai for network discovery in a partially connected network.

The third, SWIM, pulls a heartbeat in each call. This mechanism was developed at Cornell University in order to implement scalable failure detection.

**[VIDEO: Randomized Gossip Methods](https://goo.gl/7nBhLF)**

### Referenced Papers

- [Epidemic algorithms for replicated database maintenance](https://www.cis.upenn.edu/~bcpierce/courses/dd/papers/demers-epidemic.pdf)
- [Resource Discovery in Distributed Networks](http://www.cs.cmu.edu/~harchol/Papers/discovery.ps)
- [Randomized Rumor Spreading](http://zoo.cs.yale.edu/classes/cs426/2013/bib/karp00randomized.pdf)
- [SWIM: Scalable Weakly-consistent Infection-style Process Group Membership Protocol](https://www.cs.cornell.edu/~asdas/research/dsn02-swim.pdf)
