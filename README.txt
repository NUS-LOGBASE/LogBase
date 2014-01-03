LogBase [1] is an open-source, scalable log-structured database system in the Cloud that adopts log-only storage structure for removing the write bottleneck observed in write-heavy environments, e.g., continuous stream processing. 

LogBase leverages the Hadoop Distributed File System (HDFS) [2] to maintain log files, which constitute the only data repository in the system. LogBase is implemented in Java, inherits basic infrastructures from the open-source HBase [3], and adds new features for log-structured storages including access to log files and in-memory indexes.
	
In this release, LogBase provides basic API for schema definition and data operations. In the next releases, advanced features that are in the pipeline include secondary indexes, query processing engine, and system recovery. Further information of LogBase project can be found at [1].

1. http://www.comp.nus.edu.sg/~logbase/
2. http://hadoop.apache.org
3. http://hbase.apache.org/ 

The remaining chapters of this document are organized as follows. Chapter 2 introduces the data model of LogBase, and the provided API that handles data managed in LogBase. Example codes on how to use this API are also presented in this chapter. Chapter 3 elaborates on the configuration steps and running LogBase.


Please feel free to contact us at the following email addresses should you have any query.
huanghao@comp.nus.edu.sg 
wangsh@comp.nus.edu.sg
voht@comp.nus.edu.sg