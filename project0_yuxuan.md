+--------------------+--------------------+--------------------+--------------------+
| Index              | System Name        | Strengths          | Weaknesses         |
+--------------------+--------------------+--------------------+--------------------+
| A1                 | Attivio            | -   Integrates     | Video searches     |
|                    |                    |     structured     | relies on video    |
|                    |                    |     data and       | metadata           |
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
|                    |                    |     access)        |                    |
|                    |                    | -   Support both   |                    |
|                    |                    |     search Query   |                    |
|                    |                    |     and SQL        |                    |
|                    |                    | -   Easy to        |                    |
|                    |                    |     distribute<spa |                    |
|                    |                    | n                  |                    |
|                    |                    |     class="Apple-c |                    |
|                    |                    | onverted-space"> < |                    |
|                    |                    | /span>             |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Elasticsearch      | -   Search engine  | -   Doesn’t        |
|                    |                    |     that supports  |     support SQL    |
|                    |                    |     full-text      | -   Doesn’t        |
|                    |                    |     search         |     support        |
|                    |                    |     (schema-free)  |     MapReduce      |
|                    |                    | -   Distributed    |                    |
|                    |                    |     architecture   | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | HP Autonomy        | -   Support        | \                  |
|                    |                    |     structured     |                    |
|                    |                    |     data and       |                    |
|                    |                    |     unstructured   |                    |
|                    |                    |     data           |                    |
|                    |                    | -   Automatic and  |                    |
|                    |                    |     real-time      |                    |
|                    |                    |     processing     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Lucene/Solr        | -   Search engine  | -   Doesn’t        |
|                    |                    |     that supports  |     support SQL    |
|                    |                    |     full-text      | -   Doesn’t        |
|                    |                    |     search, hit    |     Support        |
|                    |                    |     highlighting,  |     MapReduce      |
|                    |                    |     rich-document  | -   Doesn’t        |
|                    |                    |     handling       |     support        |
|                    |                    | -   Easy to scale  |     foreign key    |
|                    |                    |     up and down    |                    |
|                    |                    | -   Easy to        |                    |
|                    |                    |     distribute<spa |                    |
|                    |                    | n                  |                    |
|                    |                    |     class="Apple-c |                    |
|                    |                    | onverted-space"> < |                    |
|                    |                    | /span>             |                    |
|                    |                    | -   Great          |                    |
|                    |                    |     fault-toleranc |                    |
|                    |                    | e                  |                    |
|                    |                    | -   Geo-spatial    |                    |
|                    |                    |     search         |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Oracle Endeca      | -   Hybrid         | -   Stateless thus |
|                    | Server             |     search-analyti |     requires       |
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
|                    |                    |     analytics)     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | SRCH2              | -   In-memory      | -   Commercial,    |
|                    |                    |     search (High   |     aims at        |
|                    |                    |     performance)   |     enterprise     |
|                    |                    | -   Seems to       |     search         |
|                    |                    |     support        |                    |
|                    |                    |     full-range of  |                    |
|                    |                    |     queries        |                    |
|                    |                    | -   Geo Search     |                    |
|                    |                    | -   Runs on both   |                    |
|                    |                    |     server and     |                    |
|                    |                    |     mobile devices |                    |
+--------------------+--------------------+--------------------+--------------------+
| A2                 | Apache S4          | -   Real-time      | -   No guaranteed  |
|                    |                    |     processing     |     message        |
|                    |                    |     (continues     |     processing<spa |
|                    |                    |     unbounded      | n                  |
|                    |                    |     streams of     |     class="Apple-c |
|                    |                    |     data)          | onverted-space"> < |
|                    |                    | -   Distributed    | /span>             |
|                    |                    |     and scalable   |                    |
|                    |                    | -   Fault-tolerant |                    |
|                    |                    | -   Pluggable      |                    |
|                    |                    |     platform       |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Apache Storm       | -   Distributed    | \                  |
|                    |                    |     and real-time  |                    |
|                    |                    | -   Fault-tolerant |                    |
|                    |                    | -   Guaranteed     |                    |
|                    |                    |     message        |                    |
|                    |                    |     processing     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | AWS Kinesis        | -   Support        | -   Data added to  |
|                    |                    |     real-time      |     a stream       |
|                    |                    |     processing of  |     expires after  |
|                    |                    |     streaming data |     24 hrs.        |
|                    |                    | -   Support        |                    |
|                    |                    |     multiple       |                    |
|                    |                    |     readers for a  |                    |
|                    |                    |     single stream  |                    |
|                    |                    | -   Fault—tolerant |                    |
|                    |                    | -   Support        |                    |
|                    |                    |     scaling        |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | DataTorrent        | -   Support        | \                  |
|                    |                    |     real-time      |                    |
|                    |                    |     analytics      |                    |
|                    |                    | -   Automatic      |                    |
|                    |                    |     scale          |                    |
|                    |                    | -   Fault-tolerant |                    |
|                    |                    | -   Guaranteed no  |                    |
|                    |                    |     state/message  |                    |
|                    |                    |     loss           |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | FeedZai            | -   Real-time data | -   Run in cloud   |
|                    |                    |     analysis       |                    |
|                    |                    |     (behavioral    |                    |
|                    |                    |     analysis)      |                    |
|                    |                    | -   Built in fraud |                    |
|                    |                    |     detection      |                    |
|                    |                    |     feature based  |                    |
|                    |                    |     on             |                    |
|                    |                    |     machine-learni |                    |
|                    |                    | ng                 |                    |
|                    |                    |     algorithms     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Google Cloud       | -   Support both   | \                  |
|                    | Dataflow           |     batch and      |                    |
|                    |                    |     stream-based   |                    |
|                    |                    |     data analysis  |                    |
|                    |                    | -   Auto-scaling   |                    |
|                    |                    | -   Fault-tolerant |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Guavus             | -   Support        | -   Run            |
|                    |                    |     structured and |     on-premises    |
|                    |                    |     unstructured   |                    |
|                    |                    |     data, static   |                    |
|                    |                    |     data and       |                    |
|                    |                    |     dynamic data   |                    |
|                    |                    | -   Streaming      |                    |
|                    |                    |     analysis       |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | IBM InfoSphere     | -   Real-time      | -   Run in cloud   |
|                    | Streams            |     analysis       |                    |
|                    |                    | -   Scalable       |                    |
|                    |                    | -   Support both   |                    |
|                    |                    |     relational and |                    |
|                    |                    |     non-relational |                    |
|                    |                    |     data types     |                    |
|                    |                    | -   Support event  |                    |
|                    |                    |     stream         |                    |
|                    |                    |     processing     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Lokad              | \                  | -   Have to use    |
|                    |                    |                    |     Windows Azure  |
|                    |                    |                    |     Platform?      |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Software AG        | -   Support        | -   Run in cloud   |
|                    |                    |     streaming      |                    |
|                    |                    |     analytics      |                    |
|                    |                    | -   Cached static  |                    |
|                    |                    |     data           |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | SQLStream          | -   Streaming      | \                  |
|                    |                    |     processing     |                    |
|                    |                    | -   Support SQL    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | TIBCO StreamBase   | -   Push-based     | -   Run in cloud   |
|                    |                    |     real-time      |                    |
|                    |                    |     Analytics      |                    |
|                    |                    | -   Scalable<span  |                    |
|                    |                    |     class="Apple-c |                    |
|                    |                    | onverted-space"> < |                    |
|                    |                    | /span>             |                    |
+--------------------+--------------------+--------------------+--------------------+
| A3                 | Altiscale          | -   Hadoop-as-a-se | -   Use            |
|                    |                    | rvice              |     virtualization |
|                    |                    | -   Use private    | -similar           |
|                    |                    |     hardware       |     technique      |
|                    |                    |     rather than    |     which may harm |
|                    |                    |     could services |     the            |
|                    |                    |     like EC2 -\>   |     performance    |
|                    |                    |     Optimization   |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Infochimps         | -   Streaming data | \                  |
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
| \                  | Metamarkets        | -   Real-time      | \                  |
|                    |                    |     analytics      |                    |
|                    |                    | -   Two separate   |                    |
|                    |                    |     data           |                    |
|                    |                    |     pipelines, one |                    |
|                    |                    |     on Storm and   |                    |
|                    |                    |     one on Hadoop  |                    |
|                    |                    |     Map/Reduce     |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Mortar Data        | -   Hadoop-as-a-se | -   Only support   |
|                    |                    | rvice              |     data store on  |
|                    |                    | -   Support        |     in Amazon Web  |
|                    |                    |     datasets       |     Services for   |
|                    |                    |     sharing        |     sharing        |
|                    |                    |                    |     feature        |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Qubole             | -   Hadoop-as-a-se | \                  |
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
| \                  | Rackspace          | -   Hadoop-as-a-se | -   Considerable   |
|                    |                    | rvice              |     variance in    |
|                    |                    | -   Public cloud   |     performance    |
|                    |                    |     provider -\>   |                    |
|                    |                    |     can help with  |                    |
|                    |                    |     deployment and |                    |
|                    |                    |     maintenance    |                    |
|                    |                    | -   Built on top   |                    |
|                    |                    |     of             |                    |
|                    |                    |     OpenStack<span |                    |
|                    |                    |     class="Apple-c |                    |
|                    |                    | onverted-space"> < |                    |
|                    |                    | /span>             |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Savvis             | -   Hadoop-based   | -   Use Cloudera   |
|                    |                    | -   Infrastructure |                    |
|                    |                    | -as-a-service      |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Softlayer          | -   Hadoop-based   | -   Use Cloudera   |
|                    |                    | -   Infrasructure- |                    |
|                    |                    | as-a-service       |                    |
|                    |                    | -   On-demand      |                    |
|                    |                    |     deployment and |                    |
|                    |                    |     scalability    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | T-Systems          | -   Hadoop-as-a-se | -   Infrastructure |
|                    |                    | rvice              |     provided by    |
|                    |                    |                    |     Cloudera?      |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Verizon            | -   Offer          | -   Built upon     |
|                    |                    |     Cloudera’s     |     Cloudera?      |
|                    |                    |     platform-as a  |                    |
|                    |                    |     service        |                    |
|                    |                    |     (Cloudera is   |                    |
|                    |                    |     an enterprise  |                    |
|                    |                    |     analytic data  |                    |
|                    |                    |     management     |                    |
|                    |                    |     powered by     |                    |
|                    |                    |     Apache Hadoop) |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | xPlenty            | -   Hadoop-as-a-se | -   Do not support |
|                    |                    | rvice              |     completely     |
|                    |                    | -   Support        |     unstructured   |
|                    |                    |     structured and |     data?          |
|                    |                    |     semi-structure |                    |
|                    |                    | d                  |                    |
|                    |                    |     data analytics |                    |
|                    |                    | -   Flexible with  |                    |
|                    |                    |     the data store |                    |
|                    |                    |     customer uses  |                    |
+--------------------+--------------------+--------------------+--------------------+
| A4                 | AWS EMR            | -   Use Hadoop     | -   Only integrate |
|                    |                    |     managed        |     with AWS       |
|                    |                    |     cluster        |     available      |
|                    |                    | -   Integration    |     services       |
|                    |                    |     with other AWS |                    |
|                    |                    |     services       |                    |
|                    |                    | -   Scaling of     |                    |
|                    |                    |     virtual        |                    |
|                    |                    |     servers        |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Google Compute     | -   Infrastructure | -   Hard to move   |
|                    | Engine             | -as-a-service      |     to other       |
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
|                    |                    |     integrated way |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | MapR               | -   Provide        | \                  |
|                    |                    |     complete       |                    |
|                    |                    |     distribution   |                    |
|                    |                    |     for Hadoop     |                    |
|                    |                    |     with           |                    |
|                    |                    |     architectural  |                    |
|                    |                    |     optimization   |                    |
|                    |                    |     that ensures   |                    |
|                    |                    |     best           |                    |
|                    |                    |     performance.   |                    |
|                    |                    | -   Open-source    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Treasure Data      | -   Near-realtime  | \                  |
|                    |                    |     data           |                    |
|                    |                    |     collection,    |                    |
|                    |                    |     storage and    |                    |
|                    |                    |     analysis       |                    |
|                    |                    |     service.       |                    |
|                    |                    | -   Infrastructure |                    |
|                    |                    | -as-a-service      |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Zettaset           | -   Hadoop-as-a-se | \                  |
|                    |                    | rvice              |                    |
|                    |                    | -   Enterprise-Cla |                    |
|                    |                    | ss                 |                    |
|                    |                    |     Security       |                    |
+--------------------+--------------------+--------------------+--------------------+
| A5                 | Cloudera           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Databricks/Spark   | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Hortonworks        | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | IBM BigInsights    | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Metascale          | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Microsoft HD       | \                  | \                  |
|                    | Insight            |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Oracle Big Data    | \                  | \                  |
|                    | Appliance          |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Oracle Big Data    | \                  | \                  |
|                    | Could              |                    |                    |
+--------------------+--------------------+--------------------+--------------------+
| A6                 | Stratio            | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| B1                 | Logentries         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Loggly             | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Sumo Logic         | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | TIBCO LogLogic     | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| B2                 | ArangoDB           | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | Azure Search       | \                  | \                  |
+--------------------+--------------------+--------------------+--------------------+
| \                  | CortexDB           | \                  | \                  |
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

\

