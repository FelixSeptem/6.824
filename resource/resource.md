Awesome ds(https://github.com/theanalyst/awesome-distributed-systems/blob/master/README.md)

# CAP
- C(Consistency)表示一致性，每次都能够读到最新的数据或者是返回一个错误
- A(Avaliable)表示可用性，每次请求都能得到非错误的响应
- P(Partition tolerance)表示分区容错，消息因为网络而丢失或者延迟，系统仍旧可以运行
  
三者不可得兼
- CA 比如2PC
- CP 比如Paxos(Quorum类算法)
- AP 比如Gossip，dynamodb

reference:
- https://en.wikipedia.org/wiki/CAP_theorem
- https://blog.csdn.net/hanhuili/article/details/12192453
  
# Fallacies of distributed computing
八条错误的假设：
- 网络是稳定的
- 网络传输延迟为零
- 网络带宽是无限大
- 网络是安全的
- 网络拓扑不会改变
- 只有一个系统管理员
- 传输数据成本为零
- 网络是同构的
  
reference:
- https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing
- http://www.rgoarchitects.com/Files/fallacies.pdf
  
# Distributed systems theory for the distributed systems engineer

这里包含四份资料：
- [Distributed Systems for Fun and Profit](http://book.mixu.net/distsys/)
- [Notes on distributed systems for young bloods](https://www.somethingsimilar.com/2013/01/14/notes-on-distributed-systems-for-young-bloods/)
- [A Note on Distributed Systems](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.41.7628)
- [The fallacies of distributed computing](https://en.wikipedia.org/wiki/Fallacies_of_Distributed_Computing)
  
关于分布式事件发生先后顺序的确定，可以参考[Lamport Clock](https://en.wikipedia.org/wiki/Lamport_timestamps)和[Vector clock](https://en.wikipedia.org/wiki/Vector_clock)，具体实现上可以参考[DynamoDB](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)

关于leader选举，可以参考[Bully算法](https://en.wikipedia.org/wiki/Bully_algorithm)，分布式状态机复制，可以参考[wiki](https://en.wikipedia.org/wiki/State_machine_replication)和[Lamport经典论文](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.72.5429&rep=rep1&type=pdf)

# FLP
[link](https://groups.csail.mit.edu/tds/papers/Lynch/jacm85.pdf)

# An introduction to distributed system
[link](https://github.com/aphyr/distsys-class)

# Distributed system: principles and paradigms
[English](http://barbie.uta.edu/~jli/Resources/MapReduce&Hadoop/Distributed%20Systems%20Principles%20and%20Paradigms.pdf)
[Chinese](https://book.douban.com/subject/3108801/)

# Scalable Web Architecture and Distributed Systems
[link](http://www.aosabook.org/en/distsys.html)
[Chinese](http://nettee.github.io/posts/2016/Scalable-Web-Architecture-and-Distributed-Systems/)

# Principles of Distributed Computing
[link](https://disco.ethz.ch/courses/podc_allstars/lecture/podc.pdf)

# Making reliable distributed systems in the presence of software errors
[link](http://erlang.org/download/armstrong_thesis_2003.pdf)

# Design data intensive application
[作者博客](https://martin.kleppmann.com/)

