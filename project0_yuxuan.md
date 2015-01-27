+--------------------+--------------------+--------------------+--------------------+
| Index              | System Name        | Strengths          | Weaknesses         |
+--------------------+--------------------+--------------------+--------------------+
| A1                 | -   Attivio        | -   Integrates     | Video searches     |
|                    |                    |     structured     | relies on video    |
|                    |                    |     data and       | metadata[3]           |
|                    |                    |     unstructured   |                    |
|                    |                    |     data in a      |                    |
|                    |                    |     single index   |                    |
|                    |                    | -   Comprehensive  |                    |
|                    |                    |     search,        |                    |
|                    |                    |     manipulation   |                    |
|                    |                    |     and analysis   |                    |
|                    |                    |     of data        |                    |
|                    |                    |     (thanks to the |                    |
|                    |                    |     single         |                    |
|                    |                    |     index -\>      |                    |
|                    |                    |     unified        |                    |
|                    |                    |     access)       |                    |
|                    |                    | -   Support both   |                    |
|                    |                    |     search Query   |                    |
|                    |                    |     and SQL[1]        |                    |
|                    |                    | -   Easy to        |                    |
|                    |                    |     distribute[2]     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Elasticsearch  | -   Search engine  | -   Doesn’t        |
|                    |                    |     that supports  |     support SQL    |
|                    |                    |     full-text      | -   Doesn’t        |
|                    |                    |     search         |     support        |
|                    |                    |     (schema-free)  |     MapReduce[5]      |
|                    |                    | -   Distributed    |                    |
|                    |                    |     architecture[4]   | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   HP Autonomy    | -   Support        | \                  |
|                    |                    |     structured     |                    |
|                    |                    |     data and       |                    |
|                    |                    |     unstructured   |                    |
|                    |                    |     data[6]           |                    |
|                    |                    | -   Automatic and  |                    |
|                    |                    |     real-time      |                    |
|                    |                    |     processing[7]     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Lucene/Solr    | -   Search engine  | -   Doesn’t        |
|                    |                    |     that supports  |     support SQL    |
|                    |                    |     full-text      | -   Doesn’t        |
|                    |                    |     search, hit    |     Support        |
|                    |                    |     highlighting,  |     MapReduce      |
|                    |                    |     rich-document  | -   Doesn’t        |
|                    |                    |     handling       |     support        |
|                    |                    | -   Easy to scale  |     foreign key    |
|                    |                    |     up and down    |                    |
|                    |                    | -   Easy to        |                    |
|                    |                    |     distribute     |                    |
|                    |                    | -   Great          |                    |
|                    |                    |     fault-toleranc |                    |
|                    |                    | e[8]                  |                    |
|                    |                    | -   Geo-spatial    |                    |
|                    |                    |     search[9]         |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Oracle Endeca  | -   Hybrid         | -   Stateless thus |
|                    |     Server         |     search-analyti |     requires       |
|                    |                    | cal                |     complete query |
|                    |                    | -   Support        |     for each       |
|                    |                    |     structured and |     request        |
|                    |                    |     unstructured   |                    |
|                    |                    |     data           |                    |
|                    |                    | -   In-memory      |                    |
|                    |                    |     architecture   |                    |
|                    |                    |     (Index in      |                    |
|                    |                    |     memory -\>     |                    |
|                    |                    |     in-memory      |                    |
|                    |                    |     analytics)[10]     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   SRCH2          | -   In-memory      | -   Commercial,    |
|                    |                    |     search (High   |     aims at        |
|                    |                    |     performance)   |     enterprise     |
|                    |                    | -   Seems to       |     search         |
|                    |                    |     support        |                    |
|                    |                    |     full-range of  |                    |
|                    |                    |     queries        |                    |
|                    |                    | -   Geo Search     |                    |
|                    |                    | -   Runs on both   |                    |
|                    |                    |     server and     |                    |
|                    |                    |     mobile devices[11] |                    |
+--------------------+--------------------+--------------------+--------------------+
| A2                 | -   Apache S4      | -   Real-time      | -   No guaranteed  |
|                    |                    |     processing     |     message        |
|                    |                    |     (continues     |     processing[13]     |
|                    |                    |     unbounded      |                    |
|                    |                    |     streams of     |                    |
|                    |                    |     data)          |                    |
|                    |                    | -   Distributed    |                    |
|                    |                    |     and scalable   |                    |
|                    |                    | -   Fault-tolerant |                    |
|                    |                    | -   Pluggable      |                    |
|                    |                    |     platform[12]       |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Apache Storm   | -   Distributed    | \                  |
|                    |                    |     and real-time  |                    |
|                    |                    | -   Fault-tolerant |                    |
|                    |                    | -   Guaranteed     |                    |
|                    |                    |     message        |                    |
|                    |                    |     processing     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   AWS Kinesis    | -   Support        | -   Data added to  |
|                    |                    |     real-time      |     a stream       |
|                    |                    |     processing of  |     expires after  |
|                    |                    |     streaming data |     24 hrs.        |
|                    |                    | -   Support        |                    |
|                    |                    |     multiple       |                    |
|                    |                    |     readers for a  |                    |
|                    |                    |     single stream  |                    |
|                    |                    | -   Fault—tolerant |                    |
|                    |                    | -   Support        |                    |
|                    |                    |     scaling[14]        |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   DataTorrent    | -   Support        | \                  |
|                    |                    |     real-time      |                    |
|                    |                    |     analytics      |                    |
|                    |                    | -   Automatic      |                    |
|                    |                    |     scale          |                    |
|                    |                    | -   Fault-tolerant |                    |
|                    |                    | -   Guaranteed no  |                    |
|                    |                    |     state/message  |                    |
|                    |                    |     loss[15]           |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   FeedZai        | -   Real-time data | -   Run in cloud   |
|                    |                    |     analysis       |                    |
|                    |                    |     (behavioral    |                    |
|                    |                    |     analysis)      |                    |
|                    |                    | -   Built in fraud |                    |
|                    |                    |     detection      |                    |
|                    |                    |     feature based  |                    |
|                    |                    |     on             |                    |
|                    |                    |     machine-learni |                    |
|                    |                    | ng                 |                    |
|                    |                    |     algorithms[16]     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Google Cloud   | -   Support both   | \                  |
|                    |     Dataflow       |     batch and      |                    |
|                    |                    |     stream-based   |                    |
|                    |                    |     data analysis  |                    |
|                    |                    | -   Auto-scaling   |                    |
|                    |                    | -   Fault-tolerant[17] |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Guavus         | -   Support        | -   Run            |
|                    |                    |     structured and |     on-premises    |
|                    |                    |     unstructured   |                    |
|                    |                    |     data, static   |                    |
|                    |                    |     data and       |                    |
|                    |                    |     dynamic data   |                    |
|                    |                    | -   Streaming      |                    |
|                    |                    |     analysis[18]       |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   IBM InfoSphere | -   Real-time      | -   Run in cloud   |
|                    |     Streams        |     analysis       |                    |
|                    |                    | -   Scalable       |                    |
|                    |                    | -   Support both   |                    |
|                    |                    |     relational and |                    |
|                    |                    |     non-relational |                    |
|                    |                    |     data types     |                    |
|                    |                    | -   Support event  |                    |
|                    |                    |     stream         |                    |
|                    |                    |     processing[19]     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Lokad          | \                  | -   Have to use    |
|                    |                    |                    |     Windows Azure  |
|                    |                    |                    |     Platform?[20]      |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Software AG    | -   Support        | -   Run in cloud   |
|                    |                    |     streaming      |                    |
|                    |                    |     analytics      |                    |
|                    |                    | -   Cached static  |                    |
|                    |                    |     data[21]           |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   SQLStream      | -   Streaming      | \                  |
|                    |                    |     processing     |                    |
|                    |                    | -   Support SQL[22]    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   TIBCO          | -   Push-based     | -   Run in cloud[24]   |
|                    |     StreamBase     |     real-time      |                    |
|                    |                    |     Analytics      |                    |
|                    |                    | -   Scalable[23]       |                    |
+--------------------+--------------------+--------------------+--------------------+
| A3                 | -   Altiscale      | -   Hadoop-as-a-se | -   Use            |
|                    |                    | rvice              |     virtualization |
|                    |                    | -   Use private    | -similar           |
|                    |                    |     hardware       |     technique      |
|                    |                    |     rather than    |     which may harm |
|                    |                    |     could services |     the            |
|                    |                    |     like EC2 -\>   |     performance[25]    |
|                    |                    |     Optimization   |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Infochimps     | -   Streaming data | \                  |
|                    |                    |     and real-time  |                    |
|                    |                    |     analytics      |                    |
|                    |                    | -   NoSQL database |                    |
|                    |                    |     and ad hoc,    |                    |
|                    |                    |     query-based    |                    |
|                    |                    |     analytics      |                    |
|                    |                    | -   Elastic Hadoop |                    |
|                    |                    |     clusters       |                    |
|                    |                    | -   Batch          |                    |
|                    |                    |     analytics      |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Metamarkets    | -   Real-time      | \                  |
|                    |                    |     analytics      |                    |
|                    |                    | -   Two separate   |                    |
|                    |                    |     data           |                    |
|                    |                    |     pipelines, one |                    |
|                    |                    |     on Storm and   |                    |
|                    |                    |     one on Hadoop  |                    |
|                    |                    |     Map/Reduce[26]     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Mortar Data    | -   Hadoop-as-a-se | -   Only support   |
|                    |                    | rvice              |     data store on  |
|                    |                    | -   Support        |     in Amazon Web  |
|                    |                    |     datasets       |     Services for   |
|                    |                    |     sharing        |     sharing        |
|                    |                    |                    |     feature[27]        |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Qubole         | -   Hadoop-as-a-se | \                  |
|                    |                    | rvice              |                    |
|                    |                    | -   Scale as       |                    |
|                    |                    |     demand         |                    |
|                    |                    | -   Elastic        |                    |
|                    |                    |     Hadoop-based   |                    |
|                    |                    |     cluster        |                    |
|                    |                    | -   Support        |                    |
|                    |                    |     structured and |                    |
|                    |                    |     unstructured   |                    |
|                    |                    |     data           |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Rackspace      | -   Hadoop-as-a-se | -   Considerable   |
|                    |                    | rvice              |     variance in    |
|                    |                    | -   Public cloud   |     performance    |
|                    |                    |     provider -\>   |                    |
|                    |                    |     can help with  |                    |
|                    |                    |     deployment and |                    |
|                    |                    |     maintenance    |                    |
|                    |                    | -   Built on top   |                    |
|                    |                    |     of OpenStack[28[   |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Savvis         | -   Hadoop-based   | -   Use Cloudera   |
|                    |                    | -   Infrastructure |                    |
|                    |                    | -as-a-service      |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Softlayer      | -   Hadoop-based   | -   Use Cloudera   |
|                    |                    | -   Infrasructure- |                    |
|                    |                    | as-a-service       |                    |
|                    |                    | -   On-demand      |                    |
|                    |                    |     deployment and |                    |
|                    |                    |     scalability[29]    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   T-Systems      | -   Hadoop-as-a-se | -   Infrastructure |
|                    |                    | rvice              |     provided by    |
|                    |                    |                    |     Cloudera?[30]      |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Verizon        | -   Offer          | -   Built upon     |
|                    |                    |     Cloudera’s     |     Cloudera?      |
|                    |                    |     platform-as a  |                    |
|                    |                    |     service        |                    |
|                    |                    |     (Cloudera is   |                    |
|                    |                    |     an enterprise  |                    |
|                    |                    |     analytic data  |                    |
|                    |                    |     management     |                    |
|                    |                    |     powered by     |                    |
|                    |                    |     Apache Hadoop)[31] |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   xPlenty        | -   Hadoop-as-a-se | -   Do not support |
|                    |                    | rvice              |     completely     |
|                    |                    | -   Support        |     unstructured   |
|                    |                    |     structured and |     data?          |
|                    |                    |     semi-structure |                    |
|                    |                    | d                  |                    |
|                    |                    |     data analytics |                    |
|                    |                    | -   Flexible with  |                    |
|                    |                    |     the data store |                    |
|                    |                    |     customer uses[32]  |                    |
+--------------------+--------------------+--------------------+--------------------+
| A4                 | -   AWS EMR        | -   Use Hadoop     | -   Only integrate |
|                    |                    |     managed        |     with AWS       |
|                    |                    |     cluster        |     available      |
|                    |                    | -   Integration    |     services       |
|                    |                    |     with other AWS |                    |
|                    |                    |     services       |                    |
|                    |                    | -   Scaling of     |                    |
|                    |                    |     virtual        |                    |
|                    |                    |     servers[33]        |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Google Compute | -   Infrastructure | -   Hard to move   |
|                    |     Engine         | -as-a-service      |     to other       |
|                    |                    | -   Run on         |     providers      |
|                    |                    |     google’s       |                    |
|                    |                    |     infrastructure |                    |
|                    |                    |     (which can be  |                    |
|                    |                    |     regarded as a  |                    |
|                    |                    |     proof for      |                    |
|                    |                    |     reliability)   |                    |
|                    |                    | -   Easy scaling   |                    |
|                    |                    | -   Compute,       |                    |
|                    |                    |     storage,       |                    |
|                    |                    |     services are   |                    |
|                    |                    |     all available  |                    |
|                    |                    |     in an          |                    |
|                    |                    |     integrated way[34] |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   MapR           | -   Provide        | \                  |
|                    |                    |     complete       |                    |
|                    |                    |     distribution   |                    |
|                    |                    |     for Hadoop     |                    |
|                    |                    |     with           |                    |
|                    |                    |     architectural  |                    |
|                    |                    |     optimization   |                    |
|                    |                    |     that ensures   |                    |
|                    |                    |     best           |                    |
|                    |                    |     performance.   |                    |
|                    |                    | -   Open-source[35]    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Treasure Data  | -   Near-realtime  | \                  |
|                    |                    |     data           |                    |
|                    |                    |     collection,    |                    |
|                    |                    |     storage and    |                    |
|                    |                    |     analysis       |                    |
|                    |                    |     service.       |                    |
|                    |                    | -   Infrastructure |                    |
|                    |                    | -as-a-service[36]      |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Zettaset       | -   Hadoop-as-a-se | \                  |
|                    |                    | rvice              |                    |
|                    |                    | -   Enterprise-Cla |                    |
|                    |                    | ss                 |                    |
|                    |                    |     Security[37]�      |                    |
+--------------------+--------------------+--------------------+--------------------+
| A5                 | -   Cloudera       | -   Provide        | \                  |
|                    |                    |     enterprise     |                    |
|                    |                    |     processing,    |                    |
|                    |                    |     storage,       |                    |
|                    |                    |     analysis       |                    |
|                    |                    |     services in    |                    |
|                    |                    |     one system     |                    |
|                    |                    | -   Massive        |                    |
|                    |                    |     scalable       |                    |
|                    |                    | -   Hadoop-based[38]   |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Databricks/Spa | -   A processing   | \                  |
|                    | rk                 |     engine         |                    |
|                    |                    |     compatible     |                    |
|                    |                    |     with Hadoop    |                    |
|                    |                    |     and many other |                    |
|                    |                    |     frameworks     |                    |
|                    |                    | -   Support many   |                    |
|                    |                    |     data storage   |                    |
|                    |                    |     (HDFS, HBase,  |                    |
|                    |                    |     Cassamdra,     |                    |
|                    |                    |     Hive, etc.)    |                    |
|                    |                    | -   Support batch  |                    |
|                    |                    |     processing,    |                    |
|                    |                    |     streaming,     |                    |
|                    |                    |     interactive    |                    |
|                    |                    |     queries, and   |                    |
|                    |                    |     machine        |                    |
|                    |                    |     learning[39]       |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Hortonworks    | -   Provide        | \                  |
|                    |                    |     enterprise-gra |                    |
|                    |                    | de                 |                    |
|                    |                    |     Hadoop system  |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   IBM            | -   Enterprise-gra | \                  |
|                    |     BigInsights    | de                 |                    |
|                    |                    |     Hadoop system  |                    |
|                    |                    | -   Additional     |                    |
|                    |                    |     features (e.g. |                    |
|                    |                    |     administrative |                    |
|                    |                    | ,                  |                    |
|                    |                    |     discovery,     |                    |
|                    |                    |     provisioning,  |                    |
|                    |                    |     security)[40]      |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Metascale      | -   Enterprise-gra | \                  |
|                    |                    | de                 |                    |
|                    |                    |     Hadoop system  |                    |
|                    |                    |     (on-premise)   |                    |
|                    |                    | -   Modernize      |                    |
|                    |                    |     Legacy systems[41] |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Microsoft HD   | -   Hadoop-based   | -   No             |
|                    |     Insight        | -   Support        |     unstructured   |
|                    |                    |     structured and |     data support   |
|                    |                    |     semi-structure |                    |
|                    |                    | d                  |                    |
|                    |                    |     data           |                    |
|                    |                    | -   Can integrate  |                    |
|                    |                    |     on-premises    |                    |
|                    |                    |     Hadoop         |                    |
|                    |                    |     clusters[42]       |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Oracle Big     | -   Use Cloudera   | -   Suitable for   |
|                    |     Data Appliance |     Enterpirse     |     mid-sized      |
|                    |                    |     Technology     |     companies, not |
|                    |                    |     software       |     small ones.    |
|                    |                    | -   Oracle NoSQL   |                    |
|                    |                    |     datbases       |                    |
|                    |                    | -   Comprehensive  |                    |
|                    |                    |     security       |                    |
|                    |                    |     features       |                    |
|                    |                    | -   Multiple OS    |                    |
|                    |                    |     choices[43]        |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Oracle Big     | -   Infrastructure | -   Seem to        |
|                    |     Data Could     | -as-a-service      |     restrict data  |
|                    |                    | -   Elastic        |     store to       |
|                    |                    | -   Integrated     |     Oracle storage |
|                    |                    |     security       |     cloud.         |
|                    |                    | -   Integrated     |                    |
|                    |                    |     storage        |                    |
+--------------------+--------------------+--------------------+--------------------+
| A6                 | -   Stratio        | -   Spark-based    | \                  |
|                    |                    | -   Open-source    |                    |
|                    |                    | -   Enterprise-rea |                    |
|                    |                    | dy                 |                    |
|                    |                    | -   Integrate with |                    |
|                    |                    |     main NoSQL     |                    |
|                    |                    |     databases[44]      |                    |
+--------------------+--------------------+--------------------+--------------------+
| B1                 | -   Logentries     | -   Centralize,    | \                  |
|                    |                    |     search and     |                    |
|                    |                    |     analyze logs   |                    |
|                    |                    | -   Anomaly        |                    |
|                    |                    |     detection      |                    |
|                    |                    | -   Log is         |                    |
|                    |                    |     archived on S3[45] |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Loggly         | -   Log-management | \                  |
|                    |                    | -   Scalable       |                    |
|                    |                    |     (hybrid of AWS |                    |
|                    |                    |     and their own  |                    |
|                    |                    |     Equinix        |                    |
|                    |                    |     infrastructure |                    |
|                    |                    | )                  |                    |
|                    |                    | -   Collect data   |                    |
|                    |                    |     through        |                    |
|                    |                    |     existing open  |                    |
|                    |                    |     standards[46]      |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   Sumo Logic     | -   Collect,       | \                  |
|                    |                    |     centralize,    |                    |
|                    |                    |     search and     |                    |
|                    |                    |     analyze logs   |                    |
|                    |                    | -   Anomaly        |                    |
|                    |                    |     detection      |                    |
|                    |                    | -   Visualization  |                    |
|                    |                    | -   Compliance     |                    |
|                    |                    | -   Hosted         |                    |
|                    |                    |     collection can |                    |
|                    |                    |     be on-premise  |                    |
|                    |                    |     or from S3[47]     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | -   TIBCO LogLogic | -   Log data       | \                  |
|                    |                    |     management     |                    |
|                    |                    | -   Visual         |                    |
|                    |                    |     analytics      |                    |
|                    |                    | -   Compliance[48]     |                    |
+--------------------+--------------------+--------------------+--------------------+
| B2                 | ArangoDB           | -   Support        | -   Use ArangoDB   |
|                    |                    |     multi-model    |     Query language |
|                    |                    |     (document,     |     which takes    |
|                    |                    |     graphs,        |     some time to   |
|                    |                    |     key-value      |     learn          |
|                    |                    |     pairs)         |                    |
|                    |                    | -   Use SQL-like   |                    |
|                    |                    |     query language |                    |
|                    |                    |     or JavaScript  |                    |
|                    |                    |     extensions[49]     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Azure Search       | -   Search-as-a-service[50]  | \                  |
|                    |                    |             |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | CortexDB           | -   Support        | \                  |
|                    |                    |     multi-model    |                    |
|                    |                    | -   Use temporal   |                    |
|                    |                    |     database       |                    |
|                    |                    |     technology     |                    |
|                    |                    |     (ensure only   |                    |
|                    |                    |     the truth at   |                    |
|                    |                    |     the            |                    |
|                    |                    |     transaction    |                    |
|                    |                    |     time and       |                    |
|                    |                    |     ignore the     |                    |
|                    |                    |     validity[51]       |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | IBM InfoSphere     | \                  | \                  |
|                    | Data Explorer      |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | LucidWorks Big     | \                  | \                  |
|                    | Data               |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MarkLogic          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | NGDATA             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Splunk             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Sqrrl Enterprise   | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Starcounter        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| B3                 | Actian Ingres      | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Apache Tajo        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | EnterpriseDB       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Firebird           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MariaDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MariaDB Enterprise | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Percona            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Postgres-XL        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | PostgreSQL         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | SAP Sybase ASE     | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | SAP Sybase SQL     | \                  | \                  |
|                    | Anywhere           |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Splice Machine     | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | SQLite             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Trafodion          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | vFabric Postgres   | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| B4                 | Apache Drill       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Apache Hive        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | IBM Big SQL        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | IBM DB2            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | IBM PureData       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MammothDB          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MySQL              | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Oracle Database    | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Oracle Exadata     | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Presto             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| B5                 | Actian PSQL        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | CitusDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Hadapt             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Impala             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Informix           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | JethroData         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Microsoft SQL      | \                  | \                  |
|                    | Server             |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Microsoft SQL      | \                  | \                  |
|                    | Server PDW         |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Pivotal HD/HAWQ    | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | SAP HANA           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| B6                 | HPCC               | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | IBM PureData for   | \                  | \                  |
|                    | Analytics          |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Oracle Exalytics   | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | RainStor           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | SciDB              | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | SQream             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Teradata           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Teradata Aster     | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | XtremeData         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| C1                 | Documentum xDB     | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Ipedo XML Database | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Neo4J              | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | OrientDB           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Sparksee           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Tamino XML Server  | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | UniData            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | UniVerse           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | YarcData           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| C2                 | Aerospike          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Cassandra          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Couchbase          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | DataStax           | \                  | \                  |
|                    | Enterprise         |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | FatDB              | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | FoundationDB       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Handlersocket      | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | HBase              | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Hypertable         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Redis              | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Riak               | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| C3                 | CockroachDB        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Datomic            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | FairCom            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | InfiniSQL          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | JustOneDB          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MemSQL             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | NuoDB              | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | VoltDB             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| C4                 | Clusrix            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | CodeFutures        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Drizzle            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | GenieDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Infobright         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MySQL Cluster      | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MySQL Fabric       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | ScaleArc           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | ScaleBase          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | ScaleDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Spider             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Tesora             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | TokuDB             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| C5                 | Exasol             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Google Cloud SQL   | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Heroku Postgres    | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | OpenStack Trove    | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Oracle TimesTen    | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Progress OpenEdge  | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Rackspace Cloud    | \                  | \                  |
|                    | Databases          |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | SolidDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | StormDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| C6                 | Actian Matrix      | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Actian Vector      | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | HP Vertica         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | IBM InfoSphere     | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Kognitio           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Kx Systems         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | LucidDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Metamarkets Druid  | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | ParStream          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | SAP Sybase IQ      | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| D1                 | Adabas             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | FlockDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | GrapheneDB         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | IBM IMS            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | McObject           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | ObjectStore        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Stardog            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Titan              | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | WakandaDB          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| D2                 | Accumulo           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | BerkeleyDB         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Cassandra.io       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | CloudBird          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Compose            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | CouchDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Google App Engine  | \                  | \                  |
|                    | Datastore          |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Google Cloud       | \                  | \                  |
|                    | Datastore          |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | HyperDex           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | JumboDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | LevelDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MongoDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | ObjectRocket Redis | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Oracle NoSQL       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | RavenDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | RethinkDB          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | TokuMX             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Voldemort          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| D3                 | Altibase HDB       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Altibase XDB       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Pivotal SQLFire    | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Translattice       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| D4                 | Continuent         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | DeepDB             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Galera             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Zimory Scale       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| D5                 | AWS RDS            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Azure SQL Database | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | ClearDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Database.com       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | FathomDB           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Google BigQuery    | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | HP Cloud RDB for   | \                  | \                  |
|                    | MySQL              |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | WebScaleSQL        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| D6                 | 1010data           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | AWS Redshift       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | BigYota            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | InfluxDB           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | LogicBlox          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MonetDB            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Pivotal Greenplum  | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | SpaceCurve         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | TempoIQ            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| E1                 | Actian Versant     | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | AffinityDB         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Allegrograph       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Giraph             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | HypergraphDB       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | InfiniteGraph      | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Intersystems Cache | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Objectivity        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | SPARQLBASE         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Trinity            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| E2                 | AWS DynamoDB       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | AWS ElasticCache   | \                  | \                  |
|                    | with Redis         |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | AWS SimpleDB       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Azure DocumentDB   | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Cloudant           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | DocumentDB         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Iris Couch         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Lotus Notes        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MagnetoDB          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MongoLab           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | ObjectRocket       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Redis Labs Redis   | \                  | \                  |
|                    | Cloud              |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Redis-to-go        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | RedisGreen         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| E3                 | GridGain           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MemCachier         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Redis Labs         | \                  | \                  |
|                    | Memcached Cloud    |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | ScaleOut Software  | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| E4                 | AWS ElastiCache    | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | BigCache           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | BigMemory          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | GigaSpaces XAP     | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | IronCache          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Pivital GemFire    | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| E5                 | CloudTran          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Ehcache            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Hazelcast          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Memcached          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Oracle Coherence   | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| E6                 | IBM eXtreme Scale  | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | InfiniSpan         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Red Hat JBoss Data | \                  | \                  |
|                    | Grid               |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | \                  | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | \                  | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+

References:

1.http://en.wikipedia.org/wiki/Attivio

2.http://www.itbusinessedge.com/blogs/it-unmasked/attivio-applies-predictive-analytics-to-indexed-data.html

3.http://arnoldit.com/wordpress/2010/11/02/attivio-upping-its-profile/

4.http://www.techworld.com/news/security/attackers-install-ddos-bots-on-amazon-cloud-exploiting-elasticsearch-weakness-3533164/

5.http://db-engines.com/en/system/Elasticsearch

6.http://en.wikipedia.org/wiki/HP\_Autonomy

7.http://www.autonomy.com/technology/

8.http://lucene.apache.org/solr/features.html

9.http://en.wikipedia.org/wiki/Apache\_Solr

10.https://docs.oracle.com/cd/E40521\_01/server.761/es\_dev/src/cdg\_interfaces\_mdex\_overview.html

11.http://srch2.com/releases/4.4.3/docs/

12.http://incubator.apache.org/s4/doc/0.6.0/overview/

13.http://www.quora.com/How-does-BackType-Twitter-Storm-compare-to-Yahoos-S4-and-IBMs-InfoSphere-Streams

14.http://venturebeat.com/2014/03/20/why-amazon-created-aws-kinesis-its-live-data-processing-service/

15.https://www.datatorrent.com/product/features

16.http://www.forbes.com/sites/tomgroenfeldt/2014/02/03/feedzai-brings-machine-learning-and-data-science-to-payment-fraud/

17.https://cloud.google.com/dataflow/

18.http://www.guavus.com/products/

19.http://www.slideshare.net/IBMInfoSphereUGFR/infosphere-streams-technical-overview-use-cases-big-data-jerome-chailloux

20.http://blog.lokad.com/journal/2010/6/23/honored-by-the-windows-azure-partner-award-of-2010.html

21.http://www.softwareag.com/corporate/products/apama\_webmethods/analytics/overview/default.asp

22.http://en.wikipedia.org/wiki/Sqlstream

23.http://www.streambase.com/news-and-events/press-releases/pr-2013/tibco-software-acquires-streambase-systems/

24.https://www.jkoolcloud.com/wp-content/uploads/jKool-451ResearchGroup.pdf

25.http://www.semantikoz.com/blog/full-metal-hadoop-as-a-service-with-altiscale/

26.https://metamarkets.com/2014/building-a-data-pipeline-that-handles-billions-of-events-in-real-time/

27.https://gigaom.com/2012/11/28/mortar-data-wants-to-become-a-hadoop-developers-best-friend/

28.http://www.scriptrock.com/articles/azure-vs-rackspace

29.http://www.ibm.com/cloud-computing/us/en/iaas.html

30.http://www.telekom.com/media/enterprise-solutions/181200

31.http://www.verizon.com/about/news/verizon-adds-clouderas-cloudbased-big-data-analytics-solution-verizon-cloud-ecosystem/

32.https://devcenter.heroku.com/articles/xplenty

33.http://docs.aws.amazon.com/ElasticMapReduce/latest/DeveloperGuide/emr-what-is-emr.html

34.https://cloud.google.com/why-google/

35.https://www.mapr.com/why-hadoop/why-mapr

36.http://www.ipso-alliance.org/june-17-2014-treasure-data-catches-the-eyes-of-ad-tech-market-with-first-flexible-cloud-data-service-2

37.http://www.zettaset.com/index.php/solutions/secure-enrterprise-hadoop/

38.http://www.cloudera.com/content/cloudera/en/products-and-services/cloudera-enterprise.html

39.https://spark.apache.org/faq.html

40.http://www-01.ibm.com/software/data/infosphere/biginsights/quick-start/

41.http://www.metascale.com/what-we-offer.html\#.VMbvoXDF\_XE

42.http://azure.microsoft.com/en-us/services/hdinsight/

43.https://www.oracle.com/engineered-systems/big-data-appliance/index.html

44.http://www.stratio.com/

45.https://logentries.com/product/anomaly-detection/

46.https://www.loggly.com/why-loggly/

47.http://www.sumologic.com/product/capabilities/

48.http://www.tibco.com/products/event-processing/loglogic-for-machine-data/machine-data-management

49.https://www.arangodb.com/

50.http://azure.microsoft.com/en-us/services/search/

51.http://www.odbms.org/2014/04/cortexdb/

\

