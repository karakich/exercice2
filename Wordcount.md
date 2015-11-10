* __Program Name__: WordCount
 
* __Description__: 
[Wordcount]() is a HDFS benchmark included in Hadoop distributions. It is designed to stress test the storage I/O (read and write) capabilities of a cluster. In this way performance bottlenecks in network, hardware, OS and Hadoop setup can be found and fixed. The benchmark consists of two parts: TestDFSIO-write and TestDFSIO-read. The write program starts multiple map tasks with each task writing a separate HDFS file. The read program starts multiple map tasks with each task sequentially reading the previously written HDFS files and measuring the file size and the task execution time. The benchmark uses a single reduce task to measure and compute two performance metrics for each map task: Average I/O Rate and Throughput. Respectively, Equation 1 and Equation 2 illustrate how the two metrics are calculated with N as the total number of map tasks and the index i (0< i < N), identifying the individual tasks.  


* __Usage__: 

* __Options__:

__-read__: start the read workload

__-write__: start the write workload

__-clean__: delete the generated data

__-nrFiles__: number of read files/number of map tasks

__-fileSize__: size of read file in MB

__-resFile__:

__-bufferSize__:


* __Sample Experiments__:


| Input Data Size | Parameter  | Ouput dir | Time Run1 | Time Run2 | Time Run3 | Average Time | Standard Deviation Time |
|-----------------|------------|-----------|-----------|-----------|-----------|--------------|----------|
|            	  |            |           |           |           |           |              |          |
