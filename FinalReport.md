# [GSoC 2019] Empower Apache Nemo I/O with new hardware and off-heap memory

##### Organization: Apache Software Foundation

##### Project: Apache Nemo

##### Mentor: Gyewon Lee, Jangho Seo

##### Student: Haeyoon Cho



For the Google Summer of Code 2019, I have been working on empowering Apache Nemo in two different ways. First, Nemo's I/O can leverage modern hardware and technologies like RDMA and NVMe by integration with another open-source project, Apache Crail. Second, Nemo can alleviate garbage collection pressure by utilizing off-heap memory as an intermediate data store. I have implemented these features in Nemo throughout the summer and the work products are as follows:



## 1. Empowering Nemo with fast I/O using Apache Crail

#### GitHub Pull Request

* <https://github.com/apache/incubator-nemo/pull/219>

#### JIRA issue

* [NEMO-351: Empowering Nemo with fast I/O using Apache Crail](https://issues.apache.org/jira/projects/NEMO/issues/NEMO-351)



## 2. Supporting off-heap memory store

#### GitHub Pull Request

* <https://github.com/apache/incubator-nemo/pull/213> (merged)
* <https://github.com/apache/incubator-nemo/pull/222> (merged)
* <https://github.com/apache/incubator-nemo/pull/223> (merged)
* <https://github.com/apache/incubator-nemo/pull/236>

#### JIRA issue

* [NEMO-383: Implement DirectByteBufferOutputStream for Off-heap SerializedMemoryStore](https://issues.apache.org/jira/projects/NEMO/issues/NEMO-383)
* [NEMO-350: Implement Off-heap SerializedMemoryStore](https://issues.apache.org/jira/projects/NEMO/issues/NEMO-#350)
* [NEMO-384: Implement DirectByteBufferInputStream for Off-heap SerializedMemoryStore](https://issues.apache.org/jira/projects/NEMO/issues/NEMO-#384)
* [NEMO-388: Off-heap memory management (reuse ByteBuffer)](https://issues.apache.org/jira/projects/NEMO/issues/NEMO-388)
* [NEMO-397: Separation of JVM heap region and off-heap memory region](https://issues.apache.org/jira/browse/NEMO-397)



## 3. Other issues fixed

#### GitHub Pull Request

* <https://github.com/apache/incubator-nemo/pull/206> (merged)
* <https://github.com/apache/incubator-nemo/pull/235> (merged)

#### JIRA issue

* [NEMO-369: DirectByteArrayOutputStream usage refactoring](https://issues.apache.org/jira/projects/NEMO/issues/NEMO-369)
* [NEMO-414: Command-line specified runtime data plane configurations not applied](https://issues.apache.org/jira/projects/NEMO/issues/NEMO-414)



## 4. TODO



