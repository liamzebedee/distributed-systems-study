Distributed systems study
=========================

## Ideas.

 - [CRDT's](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type)
 - [Kademlia](https://pdos.csail.mit.edu/~petar/papers/maymounkov-kademlia-lncs.pdf), DHT's.
   - [Sub-Second Lookups on a Large-Scale Kademlia-Based Overlay](https://www.diva-portal.org/smash/get/diva2:436670/FULLTEXT01.pdf)
 - P2P systems:
   - [IPFS](https://arxiv.org/pdf/1407.3561)
   - [Incentives Build Robustness in BitTorrent](https://www.bittorrent.org/bittorrentecon.pdf)
 - Theory:
   - FLP impossibility.
   - Byzantine (Albanian) Generals problem.
   - [Safety, liveness, and consistency](https://courses.cs.washington.edu/courses/cse452/20sp/slides/consistency.pdf)
 - Paxos.
 - Raft.
   - [In Search of an Understandable Consensus Algorithm](http://www.scs.stanford.edu/20sp-cs244b/sched/readings/raft.pdf)
 - Google systems:
   - [Bigtable](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
   - [Chubby](https://static.googleusercontent.com/media/research.google.com/en//archive/chubby-osdi06.pdf)
   - [GFS](https://static.googleusercontent.com/media/research.google.com/en//archive/gfs-sosp2003.pdf)
   - [Building Large-Scale Internet Services](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44877.pdf)
   - [Spanner](https://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf#cite.0@Megastore), [Megastore](https://www.cidrdb.org/cidr2011/Papers/CIDR11_Paper32.pdf)
   - [Storage Architecture and Challenges](https://cloud.google.com/files/storage_architecture_and_challenges.pdf)
   - [Mapreduce](https://pdos.csail.mit.edu/6.824/papers/mapreduce.pdf)
 - Facebook systems
   - Blob storage https://distributed-computing-musings.com/2023/12/paper-notes-f4-facebooks-warm-blob-storage-system/ 
 - Amazon systems
   - Cassandra / DHT

**Weird ones:**

 - https://web.archive.org/web/20200630133111/http://rystsov.info/2020/06/27/pacified-consensus.html

## Code.

 - TLA+ specifications of Raft.
 - Minimal Python implementations of Raft/Paxos.

## Engineering.

 - [The Tail at Scale](https://cacm.acm.org/research/the-tail-at-scale/)
 - [Microservices and the First Law of Distributed Objects](https://martinfowler.com/articles/distributed-objects-microservices.html)
 - [Fallacies of distributed computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)
 - [gRPC principles](https://grpc.io/blog/principles/)
 - SSTable, Memtable, B-Tree, LSM Tree

## Academic Papers / reading list.

 - https://muratbuffalo.blogspot.com/2021/02/foundational-distributed-systems-papers.html 
 

## Blogs / writers.

 - https://distributed-computing-musings.com/page/7/ - great overview
 - https://decentralizedthoughts.github.io/videos/ 
 - https://muratbuffalo.blogspot.com/2020/06/learning-about-distributed-systems.html

## Software.

 - LevelDB, RocksDB.

