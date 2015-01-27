##COMPSCI 516 Project 0 
###    --- pros and cons of specific data platforms 
</br>
###name: xiaohang wang
###netid: xw65
</br>

####1010 data

_strength_

 * (1) good at large data processing: specific for Big Data analysis [1]

 * (2) good performance: can do rapid, seamless integration and analysis of disparate datasets [2]

_weakness_

* (1) have no related hardware and software service  [3]

_reference_

* (1) https://www.1010data.com/uploads/files/1010data_Sonic_Drive-In_Case_Study.pdf

* (2) https://www.1010data.com/solutions/by-industry/financial-services

* (3) http://wikibon.org/wiki/v/Big_Data_Vendor_Revenue_and_Market_Forecast_(2)0(1)(2)-(2)0(1)(7)

####Accumulo

_strength_

* (1) good security: it controls data at the cell-level [1]

* (2) good performance: it has low administrative overhead, fast reads and writes —(1)0000 operations per second per node to support [1]

* (3) good flexibility: can easily handle different kinds of datasets [1]

_weakness_

* (1) not good at bulk ingest [2]

_reference_

* (1) http://sqrrl.com/product/accumulo/ 

* (2) http://mail-archives.apache.org/mod_mbox/accumulo-commits/201305.mbox/%3C20130508133447.DE6C123888D2@eris.apache.org%3E

####Actian Ingres

_strength_

* (1) guarantees data backup: it has multiple data locations, allow parallel backups [1]

* (2) easy to build incite action [2]

_weakness_

* (1) not cheap [3]

* (2) not easy to setup configuration [3]

_reference_

* (1) wikipedia

* (2) Unveils New Action Apps Strategy: Disrupts Business Intelligence Market

* (3) http://www.actian.com/products/operational-databases/ingres/

####Actian Matrix

_strength_

* (1) not only good performance: it provides high performance when considering investment protection [1]

* (2) provide readiness features such as snap-shot  [1]

* (3)  fully considering hardware: it takes full advantage of modern CPU technology [1]

* (4)  fully supporting: combines a high performance analytics database with a powerful suite of supporting [2]

_weakness_

* (1) not cross-platform, mainly designed for Linux [3]

_reference_

* (1) Actian Matrix—Highest Performing Analytics Database

* (2) http://wwwcdn.actian.com/wp-content/uploads/(2)0(1)(4)/0(1)/Actian-Matrix-Datasheet.pdf

* (3) http://esd.actian.com/product/Matrix

####Actian PSQL

_strength_

* (1) cheap for small user: provides large database features at an affordable price, such as full security, encryption, management and monitoring tools [1]

* (2) good stability and reliability [1]

* (3) good backwards compatibility [1]

_weakness_

* (1) lacks enterprise level support [2]

_reference_

* (1) http://www.actian.com/products/operational-databases/psql/

* (2) http://community.actian.com/forum/comp-databases-ingres/(4)(3)(8)0-comparing-ingres-vs-postgresql.html

####Actian Vector

_strength_

* (1) good performance: exploits CPU— fast [1]

* (2) use advanced technology: use SIMD [1]

* (3) explore hardware ability: utilizing CPU cache as execution memory [1] 

_weakness_

* (1) use single-node architecture ((2))

_reference_

* (1) http://www.odbms.org/wp-content/uploads/(2)0(1)(4)/0(8)/WP0(1)-ActianVector-0(4)(2)(4).pdf

* (2) http://www.ovum.com/actian-plants-its-sql-on-hadoop-stake/

####Actian Versant

_strength_

* (1) good APIs: good for developers that use complex C++ or Java [1]

* (2) supports high concurrency ability and large data sets [1]

* (3) good performance: supports multi-thread on dual cache [1]

_weakness_

* (1) it does not have complete API for some other popular languages, such as Python [1]

_reference_
* (1) http://www.actian.com/wp-content/uploads/(2)0(1)(4)/0(1)/Actian-Object-Database-(8).0-Datasheet.pdf

####Adabas

_strength_

* (1) good performance: use SMP technology [1]

* (2) provides extremely high transaction levels—more than (1) million commands per second [2]

* (3) assures flexible data integration [2]

_weakness_

* (1) it is for enterprise level user, not for personal user

_reference_

* (1) Software AG Products - Adabas-Natural

* (2) http://www.softwareag.com/corporate/products/adabas_natural/adabas/overview/default.asp

####Aerospike

_strength_

* (1) good performance with low price: provides RAM-like performance but at a much lower cost [1]

* (2) fully takes advantage of the latest hardware: multi-core, multi-CPU servers and flash memory, and a distributed shared memory system [2]

_weakness_

* (1) bad performance at specific condition: when used without SSD, the performance is bad [3]

_reference_

* (1) www.aerospike.com/price-performance-advantages-(2)

* (2) http://www.infoq.com/articles/aerospike-qa

* (3) http://dba.stackexchange.com/questions/(8)(3)(8)(2)(7)/using-aerospike-without-ssd

####Allegrograph

_strength_

* (1) fast and full recoverability [1]

* (2) full read concurrency, near full write concurrency [1]

* (3) SPIN support [1]

* (4) maximum loading speed and query speed [1]

_weakness_

* (1) has some bad APIs: takes the “kitchen sink” approach to syntax [2]

_reference_

* (1) http://franz.com/agraph/allegrograph/

* (2) Common Logic for an RDF Store, Robert MacGregor, Ph.D.

####Altibase HDB 

_strength_

* (1) good performance: much faster than conventional on-disk databases [1]

* (2) short and predictable response time measured in microseconds [1]

_weakness_

* (1) not supports relational data model [2]

* (2) allows data duplication, difficult to manage [2]

_reference_

* (1)http://altibase.com/in-memory-database-hybrid-products/hdbtm-hybrid-dbms/

* (2) http://altibase.com/in-memory-database-comparisons/nosql/

####Altibase XDB

_strength_

* (1) fast data processing speeds [1]

* (2) the world’s fastest In-Memory only database [1]

_weakness_

* (1) may not have as much storage as other in-disk DB [1]

_reference_

* (1) http://altibase.com/in-memory-database-hybrid-products/xdb/

####Altiscale

_strength_

* (1) rich experience: first cloud service purpose-built to run Hadoop [1]

* (2) ability for specific order: offers an on-demand, elastic solution on a pay-as-you-go basis [1]

_weakness_

* (1) may not be quite reliable and safe since it does not has its own disk [1]

_reference_

* (1) https://www.altiscale.com/

####Apache Drill

_strength_

* (1) good performance: provides direct queries on self-describing and semi-structured data in files [1]

* (2) good UI: users can explore live data on their own [1]

* (3) good extension: compatibility with existing SQL environments [1]

_weakness_

* (1) may not be able to run SQL as fast as RDBMS

_reference_

* (1) http://drill.apache.org/#agility

####Apache Hive

_strength_

* (1) good ability of extension: supports analysis of large datasets stored in Hadoop's HDFS and compatible file systems such as Amazon S(3) filesystem [1]

* (2) cross-platform [1]

_weakness_

* (1) still not use exactly SQL, not convenient for usual DB engineer to use 

_reference_

* (1) http://en.wikipedia.org/wiki/Apache_Hive

####Apache S4

_strength_

* (1) good abstraction: hides the complexity inherent in parallel processing system from the application programmer [1]

* (2) good APIs: can easily be written and deployed using a simple API [1]

_weakness_

* (1) not quite secure: it has no guaranteed message processing [2]

_reference_

* (1) http://incubator.apache.org/s(4)/

* (2)  http://www.quora.com/How-does-BackType-Twitter-Storm-compare-to-Yahoos-S(4)-and-IBMs-InfoSphere-Streams

####Apache Storm

_strength_

* (1) good ability for streaming: it provides reliably process unbounded streams of data [1]

* (2) good monitor: it provides a benchmark clocked it at over a million tuples processed per second per node [1]

* (3) good integration with the queueing and database technologies [1]

_weakness_

* (1) cannot do data store and MapReduce at the same time [2]

_reference_

* (1) https://storm.apache.org/

* (2) http://www.ymc.ch/en/storm-or-apache-kafka

####Apache Tajo

_strength_

* (1) user friendly: provides user-defined functions [1]

* (2) easy to use and debug: provides interactive shell [1]

* (3) good performance [1]

_weakness_

* (1) as other RDBMS, it does not support very flexible schema

_reference_

* (1) http://tajo.apache.org/

####ArangoDB

_strength_

* (1) flexible data model [1]

* (2) free [1]

* (3) open source [1]

_weakness_

* (1) may not be as fast as RDBMS when schema is fixed

_reference_

* (1) https://www.arangodb.com/

####Attivio

_strength_

* (1) good intelligence: use self-developed Active Intelligence Engine which can provide customers with greater access and contextual insight into the skyrocketing volume of data facing today’s organizations [1]

_weakness_

* (1) bad performance at certain condition: when querying with umlauts, tokens will get duplicated, which reduce the performance [2]

_reference_

* (1) Attivio for big data - KMWorld Magazine

* (2) https://insighters.attivio.com/thread/1056

####AWS DynamoDB

_strength_

* (1) easy to use: it provides complete document [1]

* (2) cheap: the fee is flexible and not expensive [1]

* (3) good performance: uses automatic partitioning and SSD technologies [1]

* (4) flexible: supports both document and key-value data structures [1]

* (5) fine-grained access control:  integrates with AWS Identity and Access Management (IAM) for fine-grained access control for users [1]

* (6) fully managed: users do not need to worry about database management tasks such as hardware or software provisioning, setup and configuration, software patching, operating a reliable, distributed database cluster, or partitioning data over multiple instances [1]

* (7) automatic data replication: all data items are stored on SSDs and are automatically replicated [3]

* (8) provides integration with Amazon Elastic MapReduce [3]

_weakness_

* (1) the price cannot be fully guaranteed to be low [1]

* (2) attributes are not exactly flexible: attribute values cannot be empty strings or empty sets [2]

* (3) all strings must conform to the UTF-8 encoding [2]

* (4) 64kb limit on row size [2]

* (5) 1MB limit on querying [3]

* (6) deployable only on AWS [3]

* (7) unable to do complex queries: it is good for lookups by key, not so good for queries , and abysmal for queries with multiple predicates [3]

* (8) joins are impossible: user need to manage complex data relations on their own code/cache layer [3]

* (9) no foreign keys [3]

* (10) no triggers [3]

* (11) no ACID [3]

* (12) no support for atomic transactions: each write operation is atomic to an item [3]

_reference_

* (1) http://aws.amazon.com/dynamodb/details/

* (2) http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Limits.html

* (3) “Dynamo DB”





####AWS ElastiCache

_strength_

* (1) easy to setup and use [1]

* (2) fully managed: user do not need to care too much about management [1]

* (3) supports a single DNS per cluster [1]

* (4) supports two open-source in-memory caching engines: memcached and redis [2]

* (5) reliable: automatically detects and replaces failed nodes, reducing the overhead associated with self-managed infrastructures [2]

* (6) good performance: it provides enhanced visibility into key performance metrics associated with Memcached or Redis nodes [2]

* (7) provides replication features for the Redis engine and Multi-AZ functionality [2]

_weakness_

* (1) not cheap for personal user

* (2) it is unreliable: user can lose your data in the following events— node failure, scaling event, process restart or software upgrade  [1]

_reference_

* (1) quora

* (2) Amazon document

####AWS ElastiCache with Redis

_strength_

* (1) easy to setup and use [1]

* (2) fully managed [1]

* (3) supports two open-source in-memory caching engines: memcached and redis [2]

* (4) provides enhanced visibility into key performance metrics associated with Memcached or Redis nodes [2]

* (5) provides replication features for the Redis engine and Multi-AZ functionality [2]

* (6) supports Master / Slave replication and Multi-AZ which can be used to achieve cross AZ redundancy [2]

* (8) provides persistence to disk [3]

_weakness_

* (1) single-threaded and event driven [3]

* (2) less memory efficient [3]

_reference_

* (1) quora

* (2) Amazon document

* (3) http://www.quora.com/What-are-pros-and-cons-of-using-AWS-ElastiCache-Redis-versus-Memcached

####AWS EMR

_strength_

* (1) easy to use: easy to setup the configuration and run [1]

* (2) good documentation [2]

* (3) fast and robust: it handles many possible failure condition [2]

_weakness_

* (1) expensive and costly [1]

_reference_

* (1) http://www.quora.com/What-are-the-advantages-of-Amazon-EMR-vs-your-own-EC(2)-instances-vs-running-Hadoop-locally

* (2) http://www.quora.com/What-are-the-advantages-disadvantages-running-Clouderas-distribution-for-Hadoop-on-EC(2)-instances-rather-than-using-Amazons-Elastic-Map-Reduce-Service

####AWS Kinesis

_strength_

* (1) good data capture: it can continuously capture and store terabytes of data per hour [1]

* (2) good documentation: it is easy to use for developer

* (3) supports parallel processing: it allows user to have multiple Amazon Kinesis Applications processing the same stream concurrently [1]

* (4) reliable [1]

* (5) integration with other AWS services: it can integrate with Amazon S(3), Amazon Redshift, and Amazon DynamoDB. [1]

* (6) good and rich client libraries: it provides developers rich client libraries [1]

* (7) robust: it has built-in fault tolerance, automatically and synchronously replicating data across multiple Availability Zones in a Region [1]

_weakness_

* (1) it is not cheap comparing to other similar products [2]

_reference_

* (1) Amazon documentation

* (2) http://aws.amazon.com/kinesis/pricing/

####AWS RDS

_strength_

* (1) fully managed: such as set-up and configuration [1]

* (2) it has pre-configured parameters, simple to use but may not very fit for specific usage [1]

* (3) provides monitoring and metrics [1]

* (4) provides automatic software patching [1]

* (5) provides Multi-AZ deployments, which enhances availability and durability for Database (DB) Instances, making them a natural fit for production database workloads [1]

* (6) provides automated backups [1]

* (7) provides DB snapshots [1]

* (8) nice features: it does replication and automated back-up at the click of a button [3]

_weakness_

* (1) not cheap: it is more expensive than other similar products, such as Heroku PostgreSQL [2]

* (2) not quite guaranteed: RDS will only guarantee data up to (5) minutes ago [3]

* (3) performance is not steady: the performance of an RDS instance depends highly on a properly designed schema [3]

* (4) fee is not fixed: may not be able to justify the additional costs [3]

_reference_

* (1) Amazon documentation

* (2) http://www.quora.com/Are-there-any-reasons-to-use-Heroku-PostgreSQL-compared-to-AWS-RDS-PostgreSQL

* (3) http://www.quora.com/What-are-the-pros-cons-of-hosting-a-MySQL-DB-in-Amazon-RDS-versus-a-DB-instance-in-EC(2)

####AWS Redshift

_strength_

* (1) steady performance: generally (5)0-(1)00x speedup over Hive [1]

* (2) cheap: low cost, especially for long term user [1]

* (3) fully managed: amazon handles everything [1]

* (4) good interface: it provides SQL based interface so user can keep using existing tools and knowledge, no need to learn new tech [1]

* (5) good scalable: user can always grow their storage with needs [1]

* (6) good features: has multiple features that enhance the reliability of data warehouse cluster [2]

* (7) secure: users can set up Amazon Redshift to use SSL to secure data in transit and hardware-accelerated AES-(2)(5)(6) encryption for data at rest [2]

_weakness_

* (1) small feature set: lacks complex data types, udf, etc [1]

* (2) low performance: not fast enough for most web apps [1]

* (3) not user friendly: users have to pull data into a caching layer, or a vanilla postgres instance [1]

* (4) not easy to start: it is not convenient to load data from currently existing source [1]

_reference_

* (1) http://www.quora.com/What-are-the-pros-and-cons-of-using-Amazon-Redshift

* (2) Amazon documentation

####AWS SimpleDB

_strength_

* (1) low touch: this allows user to focus fully on value-added application development, rather than arduous and time-consuming database administration [1]

* (2) highly available: Amazon SimpleDB automatically creates multiple geographically distributed copies of each data item [1]

* (3) easy to use: Amazon SimpleDB provides streamlined access to the store and query functions that traditionally are achieved using a relational database cluster – while leaving out other complex, often-unused database operations [1]

* (4) flexible: users can easily reflect these changes in Amazon SimpleDB without worrying about breaking a rigid schema or needing to refactor code [1]


_weakness_
* (1) too many fixed features, hard for user to fit in their own product objects

* (2) it is a little expensive [2]

_reference_

* (1) Amazon documentation

* (2) http://aws.amazon.com/simpledb/pricing/

####Azure DocumentDB

_strength_

* (1) developer friendly [1]

* (2) rich query set: it supports a rich query set over a schema-free JSON data model [2]

* (3) supports transactional execution of JavaScript logic: it express application logic as stored procedures, triggers, and user defined functions using standard JavaScript [2]

* (4) scalable storage and throughput [2]

* (5) tunable consistency: it select from four well defined consistency levels to achieve optimal trade-off between consistency and performance [2]

* (6) fast and write optimized database service [2]

* (7) fully managed: eliminate the need to manage database and machine resources [2]

* (8) open design: good for programmer to use [2]

_weakness_

* (1) hard to know the restart: the restarts may not give user alerts if infra is on high availability [1]

* (2) bad performance at certain condition: the throughput will be far less and non-deterministic [1]

_reference_

* (1) http://www.quora.com/Is-Microsoft-Azure-seriously-giving-a-stiff-competition-to-Amazon

* (2) Microsoft Azure documentation

####Azure Search

_strength_

* (1) open and flexible: supports any operating system, language, tool, and framework— from Windows to Linux, SQL Server to Oracle, C# to Java [1]

* (2) economical: user only pay for what they use [1]

* (3) easy to start: quick setup and no hassle with installing [2]

* (4) scalable: user can easily increase storage [1]

_weakness_

* (1) fixed configuration: less free to configure and tune when needed [2]

* (2) not always be supported: it is dependent of MS support when it comes to specialized environment settings [2]

_reference_

* (1) Microsoft Azure documentation

* (2) https://www.linkedin.com/groups/Windows-Azure-Pros-Cons-(4)0(9)(4)(9).S.(1)(3)(5)(2)(2)(8)(9)(9)(8)

####Azure SQL Database

_strength_

* (1) easy and convenient to setup: it has no physical administration [1]

* (2) high availability: Azure generally obviates the need for building high availability architectures [1]

* (3) economically flexible: it provides scalable service plans for multiple needs and budgets [1]

* (4) good elasticity: applications written for multiple databases can be scaled out with Azure by adding instances as needed. [1]

_weakness_

* (1) only implements a subset of T-SQL [2]

* (2) user can't run agented jobs: SQL Agent itself is not supported on SQL Azure, so user cannot run jobs via the agent in the first place [2]

* (3) hard-wired limitation: it limits on usage and will throttle or disconnect database connections under heavy loads [2]

* (4) unreasonable charge: reporting also costs extra money [2]

_reference_

* (1) http://searchsqlserver.techtarget.com/feature/The-pros-of-Windows-Azure-SQL-Database

* (2) http://searchsqlserver.techtarget.com/feature/Why-you-should-think-twice-about-Windows-Azure-SQL-Database

####BerkeleyDB

_strength_

* (1) robust data storage features: it has similar features as relational database systems, such as ACID transactions and recovery; locking, multi-process and multi-threading for high concurrency; hot and cold backup; and replication for high availability applications [1]

* (2) good for term storage [2]

* (3) especially fast lookups with cache [2]

_weakness_

* (1) does not support constraints [2]

* (2) needs replicate application involvement [2]

* (3) limited in size capabilities: (2)(5)(6) GB per DB and (4)GB per record [2]

* (4) limited features: application needs to deal with more things [2]

_reference_

* (1) http://www.oracle.com/technetwork/products/berkeleydb/overview/index-0(8)(5)(3)(6)(6).html

* (2) “Evaluation of Massively Scalable Database Management Systems for Erlang” 

####BigCache

_strength_

* (1) good data protection: it prevents the Garbage Collector from interacting with the cache’s memory area [1]

* (2) relatively good performance: it is faster than disk or network data transfers [1]

_weakness_

* (1) slightly slower than in-heap data access [1]

_reference_

* (1) http://nosql.mypopescu.com/post/(2)(7)(4)(2)(3)0(3)(3)(1)(2)(7)/what-is-bigcache-off-heap-caching-solution-for

####BigMemory 

_strength_

* (1) good performance: it restricts the size of the Java Heap while still using all available physical RAM [1]

_weakness_

* (1) not complete GC: it does not solve every GC problem [1]

_reference_

* (1) http://www.quora.com/How-does-BigMemory-hide-objects-from-the-Java-garbage-collector

####BitYota

_strength_

* (1) simplicity: easy to load data and start running queries with SQL or URF [1]

* (2) fully managed  [1]

* (3) good performance: it stores and analyzes the data in a good format and reduces the data transformation processes [1]

* (4) good monitor: it provides real-time data analytics [1]

* (5) elastic up and down scaling [1]

_weakness_

* (1) expensive: the price $(1) per hour, much expensive than AWS [2]

_reference_

* (1) http://www.bityota.com/product/

* (2) http://www.bityota.com/product/price

####Cassandra 

_strength_

* (1) good fault tolerant: it copies data to multiple nodes in order of fault-tolerance. Also, it copies data to multiple data center at different place. And failed nodes can be replaced with no downtime [1]

* (2) durable: it will not lose data even when an entire data center goes down, since data is stored in multiple place [1]

* (3) user specific configuration: user can choose between synchronous or asynchronous at each update [1]

_weakness_ 

* (1) cannot do joins across partitions [2]

* (2) not actually very scalable or stable [2]

_reference_

* (1) http://cassandra.apache.org/

* (2) http://www.quora.com/Why-does-Quora-use-MySQL-as-the-data-store-instead-of-NoSQLs-such-as-Cassandra-MongoDB-or-CouchDB

####CitusDB

_strength_

* (1) high availability: it can recover from failures in real-time [1]

* (2) semi-structured data support: it runs distributed SQL queries on JSON and log files [2]

* (3) good performance: it provides sub-second response times to key-value lookups [2]

* (4) convenient to deploy: it can deploy both on-premise or in the cloud [2]

* (5) easy to download and use [2]

_weakness_

* (1) generates false positives at certain condition: it ignores the context in which keywords appear [3]

_reference_

* (1) “Making PostgreSQL scale Hadoop-style: Benchmark numbers”

* (2) http://www.citusdata.com/

* (3) http://www.citusdata.com/blog/(5)(7)-postgresql-full-text-search

####ClearDB

_strength_

* (1) uses global master design: it uses geo-distributed MySQL database configurations for the ultimate in database availability, survivability, and performance [1]

* (2) completely fault tolerant: it offers multi-regional read or write mirroring [1]

* (3) good security: uses a combination of (2)(5)(6) bit SSL encryption and client certificates directly in MySQL to secure connections [1]

_weakness_

* (1) as a RDBMS, the schema is not flexible, may not be able to fit to specific usage

_reference_

* (1) https://www.cleardb.com/

####Cloudant 

_strength_

* (1) DBaas: Cloudant provides DBaas,  eliminates the risk of service delivery failure for user and users’ project [1]

* (3) fully managed [1]

* (4) robust: provides scalable, fault-tolerant JSON data store [1]

* (5) backup guarantee: it uses multi-master replication across data centers [1]

* (6) advanced index technology: it uses (2)D and (3)D geo-spatial indexing [1]

_weakness_

* (1) the APIs may not be rich for specific usage, such as mobile app [2]

_reference_

* (1) https://cloudant.com/product/cloudant-features/

* (2) https://developer.ibm.com/answers/questions/(1)(6)(8)(5)(7)(1)/what-are-the-differences-between-mobiledata-and-cl.html

####Cloudera 

_strength_

* (1) good security: guaranteed by different kinds of authentication [1]

* (2) fully governed: it has enterprise-grade data auditing, data lineage, and data discovery [1]

* (3) fully managed: managed by cloudera, has self-healing storage and automated backup and disaster recovery [1]

* (4) unified: cloudera use one integrated system, so user will need no data movement [1]

* (5) open platform: it can connect all other technology [1]

_weakness_

* (1) it is designed for Linux, other platform may need extra support [3]

_reference_

* (1) http://www.cloudera.com/content/cloudera/en/products-and-services/cloudera-enterprise.html

* (2) http://www.quora.com/What-are-some-major-pros-cons-of-Cloudera-vs-Hortonworks-as-a-Hadoop-platform-for-a-main-street-e-g-not-Silicon-Valley-giant-enterprise

* (3) http://nosql.mypopescu.com/post/20582276970/what-are-the-pros-and-cons-of-running-clouderas

####Ehcache 

_strength_

* (1) it is light weight: it has no initial configuration, and the API is easy to use [1]

* (2) it has good performance: it is one of the fastest Java caches [1]

* (3) it is scalable: it provides Memory and Disk stores for scalability into gigabytes, and can increase to hundreds of caches [1]

* (4) it is tuned for high concurrent load on large multi-CPU servers [1]

* (5) it has multiple CacheManagers per virtual machine [1]

* (6) it is flexible: supports various other technologies [1]

* (7) it is well extensible: supports various plugged-in: cache extensions, cache, etc [1]

_weakness_

* (1) it has less directly visible code-path [2]

_reference_

* (1) http://ehcache.org/about/features

* (2) http://www.slideshare.net/HyeonSeokChoi/overview-of-the-ehcache

####EnterpriseDB 

_strength_

* (1) easy and suitable to deploy in cloud [2]

* (2) good scalability: it can scale to a new VM [2]

* (3) easy to setup [2]

_weakness_

* (1) as PostgreSQL DB, it is harder to search for solutions of some problems on Google [1]

* (2) its replication is not satisfying [1] 

_reference_

* (1) http://www.quora.com/What-are-pros-and-cons-of-PostgreSQL-and-MySQL

* (2) http://www.enterprisedb.com/news-events/news/postgresql-can-deliver-considerable-benefits-cloud

####CodeFutures 

_strength_

* (1) convenience: different from other database, it removes complexity and limitations of current data management methods [1]

* (2) good performance: provides real-time high-performance stream processing, also it uses in-memory cache [1]

* (3) good scalability: it allows quick and proficient accumulation of meaningful data [1]

* (4) it is a new way to look at database [1]

_weakness_

* (1) some latency are added into the system, such that all views are not immediately propagated [2]

_reference_

* (1)http://codefutures.com/agildata/

* (2) http://codefutures.com/infoq-agile-view-of-big-data-article-features-codefutures/

####CouchDB 

_strength_
* (1) it elegantly handles incremental updates to pre-aggregated data [1]

* (2) it uses multi-part map keys to provide an elegant mechanism for hierarchical rollup of metrics [1]

* (3) it is a peer based distributed database system [2]

_weakness_

* (1) hard to use: all queries in CouchDB are done by MapReduce, which is not a familiar way to query data [1]

* (2) performance depends on user design: with CouchDB, users have to reprogram your brain to think of every query as a map-reduce operation [1]

* (3) it does not include chained map-reduce as a standard feature [1]

* (4) it does not have many features of regular SQL, such as join [1]

_reference_

* (1) http://www.quora.com/Why-isnt-CouchDB-more-popular

* (2) https://cwiki.apache.org/confluence/display/COUCHDB/Introduction

####Databricks/Spark 

_strength_

* (1) good performance: enables applications in Hadoop clusters to run up to (1)00x faster in memory, and (1)0x faster even when running on disk [1]

* (2) good and rich APIs: it has APIs for Java, Scala or Python [1]

* (3) easy to catch up with: supports regular SQL queries and streaming data [1]

* (4) easy to setup configuration [1]

* (5) fully managed: easy for user to use [2]

* (6) open source [3]

_weakness_

* (1) It does not have API for C/C++, which is also a popular coding language

_reference_

* (1) https://databricks.com/spark

* (2) https://databricks.com/

* (3) http://www.quora.com/How-does-Cloudera-Impala-compare-to-Apache-Shark-now-part-of-Spark

####DataStax Enterprise 

_strength_

* (1) hardware transparent: DataStax allows users to optimize database performance depends on what hardware they use, such as traditional spinning disks, SSDs, or in-memory computing [1]

* (2) good security: it protects critical data [1]

* (3) good monitor: user can visually monitor and manage their environment according to their usage [1]

_weakness_

* (1) expensive: $(5)000-$(8)000 per node [2]

_reference_

* (1) http://www.datastax.com/what-we-offer/products-services/datastax-enterprise

* (2) http://www.quora.com/What-is-the-per-node-price-for-a-DataStax-enterprise-subscription

####DataTorrent

_strength_

* (1) wide usage: supports any data source and business logic [1]

* (2) easy to scale: scale linearly with no code changes [1]

* (3) easy integration: easily integrate with any existing data environment [1]

* (4) guarantee availability and scalability [1]

* (5) easy to deploy: user only need to write the business logic [2]

_weakness_

* (1) only designed for enterprise level customer 


_reference_

* (1) https://www.datatorrent.com/product/benefits/

* (2) https://www.datatorrent.com/product/features/

####Exasol

_strength_

* (1) really fast: Exasol is the world’s fastest database [1]

* (2) easy to integrate: easy to integrate into existing business applications [1]

* (3) use massively parallel processing: EXASolution was developed as a parallel system based on a shared nothing architecture [1]

* (4) supports various interface: ODBC, JDBC, MDX, and ADO.net[1]

* (5) supports high user concurrency [1]

_weakness_

* (1) similar as other RDBMS, it does not support flexible schema

_reference_

* (1) http://www.exasol.com/en/products/exasolution/

####FeedZai

_strength_

* (1) good intelligence: integrates with machine learning [1]

* (2) attention for every byte: guarantee to stream every last byte [1]

* (3) succinct UI: easy to analyze data [1]

_weakness_

* (1) not quite convenient: it is not fully managed 

* (2) not quite secure: it does not has its own hard disk

_reference_

* (1) https://www.feedzai.com/home/big-data-insight/

####Firebird 

_strength_

* (1) open source: has bright future [2]

* (2) free: no fees for download,  registration, licensing or deployment [2]

* (3) self-design: anyone can build a custom version of it [2]

_weakness_

* (1) a bit slow: slower than PostgreSQL and MySQL [1]

* (2) not quite reliable: since it is an open source and free project, there are no companies to maintain it

_reference_

* (1) http://www.quora.com/What-are-pros-and-cons-of-PostgreSQL-and-MySQL

* (2) http://www.firebirdsql.org/en/about-firebird/

####FlockDB

_strength_

* (1) open source, created by twitter [1]

* (2) good performance for large adjacency [1]

* (3) designed for graph storage: very fit for specific usage [2]

* (4) very specific at direct edge relationship [2]

_weakness_

* (1) not a complete graph database: it does not have graph traversals [2]

* (2) no stable release: may have some bugs [2]

_reference_

* (1) https://blog.twitter.com/2010/introducing-flockdb

* (2) http://readwrite.com/(2)0(1)(1)/0(4)/(2)0/(5)-graph-databases-to-consider

####Galera

_strength_

* (1) high availability: it uses synchronous replication, and all nodes have all data [1]

* (2) good performance: it has no slave lag and smaller client latencies [1]

* (3) convenient interface: the interface is like native MySQL [1]

* (4) highly synchronous: all nodes are equal on read and write [2]

* (5) easy to scale: easy to add and remove nodes, join cluster and monitor the cluster status [2]

_weakness_

* (1) not much referenced experience [2]

* (2) performance depends on the most slowly node: actually, the performance is equal to the slowest node [2]

* (3) restart may be slow: the cluster could grow too big to restart [2]

* (4) easy to come to deadlocks and rollbacks [2]

_reference_

* (1) http://galeracluster.com/products/

* (2) http://blog.secaserver.com/(2)0(1)(2)/0(4)/mysql-advantages-disadvantages-galera/

####IBM DB2

_strength_

* (1) multiple platform support: it supports all platform [1]

* (2) self-tuning memory management: this feature makes the database to automatically change the memory allocation whenever the workload changes [1]

* (3) steady and strong support by IBM [1]

* (4) good security: it is self protecting and has build-in secure features [2]

* (5)  easily scalable [3]

_weakness_

* (1) not as robust as Oracle [3]

* (2) expensive compared to other similar database [3]

_references_

* (1) http://www.ehow.com/info_(1)(2)(1)0(6)(5)(9)(9)_advantages-db(2).html

* (2) http://www-03.ibm.com/systems/power/software/i/db2/benefits.html

* (3) http://www.experts-exchange.com/Database/Miscellaneous/Q_(2)0(5)(6)(2)(6)(7)(2).html

####Microsoft SQL Server  

_strength_

* (1) easy to install: it can be installed using setup wizard [1]

* (2) good performance: it has built-in transparent data compression and encryption [1]

* (3) good security: it has strong authentication and access protection [1]

* (4) less network traffic: its network traffic is reduced in a client/server scenario [2]

* (5) rich excellent tools: sql server profile, server management studio, etc [3]

_weakness_

* (1) very expensive: $27,494 per processor,  $8,592.00 per server, $164.00 per CAL [3]

* (2) limit user in Microsoft's Ecosystem [3]

* (3) slow update: usually it’s a 2 years cycle [3]

_references_

* (1) http://www.ehow.com/list_6458544_microsoft-sql-server-advantages.html

* (2) http://www.expresstechnology.com/support/knowledge-base/46-sql-database-server/103-what-is-the-advantage-of-microsoft-sql-server-over-access

* (3) http://www.quora.com/What-are-the-advantages-or-drawbacks-in-choosing-Microsoft-SQL-server-over-MySQL

####MongoDB 

_strength_

* (1) easy to scale [1]

* (2) good performance: it is lightening fast, especially for a single lookup [1] [2]

(3) flexibility: user can use various data structure for objects [2]

* (4) sharding and load-balancing: workload is balanced distributed when the workload is heavy [2] 

* (5) deep query-ability: it supports dynamic queries on documents [3] 

_weakness_

* (1) no joins [2] 

* (2) the memory usage is not efficient [2]

* (3) the concurrency is not intelligent: one operation will lead to the lock of entire database [2]

* (4) it does not automatically treat operations as transactions [2]

_references_

* (1) http://www.tutorialspoint.com/mongodb/mongodb_advantages.htm

* (2) http://halls-of-valhalla.org/beta/articles/the-pros-and-cons-of-mongodb,(4)(5)/

* (3) http://stackoverflow.com/questions/(2)(1)(1)(7)(3)(7)(2)/what-are-the-advantages-of-using-a-schema-free-database-like-mongodb-compared-to

####MySQL

_strength_

* (1) easy to use: easy to install, run and start [2]

* (2) inexpensive compare to other popular NoSQL database [2]

* (3) extremely popular: many experience can can be googled [2]

* (4) good security: it includes solid data security layers that protect sensitive data [3]

* (5) scalable: it can almost deal with any amount of data [3]

_weakness_ 

* (1) not as mature as some other RDBMS [1]

* (2) not exactly open source [1]

* (3) performance scaling is poor [2]

_references_

* (1) http://www.smartfile.com/blog/the-pros-and-cons-of-mysql/

* (2) https://www.datarealm.com/blog/five-advantages-disadvantages-of-mysql/

* (3) https://www.novell.com/documentation/nw(6)(5)/web_mysql_nw/data/aj(5)bj(5)(2).html

####Oracle Database 

_strength_

* (1) backward compatible: good for business user to update [1]

* (2) good reliability: it can easily pass ACID test when given demanding task [1]

* (3) efficient recovery: it uses flashback technology [1]

* (4) good performance: it provides good performance even for very large data set or data with locking and transaction control [2]

* (5) cursor support: it is very useful to improve performance [2]

* (6) good deployment flexibility  [3]

* (7) good security [3]

_weakness_

* (1) overloading functionality is restricted [4]

* (2) no version control [4]

* (3) procedures of detection of accidentally drop are disabled [4]

* (4) dependency tracking is automatic [4]

_references_

* (1) http://www.learn.geekinterview.com/database/oracle/advantages-of-using-oracle.html

* (2) http://www.ehow.com/list_7684620_advantages-oracle-databases.html

* (3) http://www.oracle.com/us/solutions/sap/database/features-options/index.html

* (4) http://www.toadworld.com/platforms/oracle/w/wiki/(5)(8)(1)0.disadvantages.aspx

####Oracle NoSQL 

_strength_

* (1) scalable throughput and bounded latency: it scales linearly [1]

* (2) good performance under large workload [1]

* (3) good APIs and interfaces: easy to program [1]

* (4) well monitor and managed by Oracle [1]

* (5) highly-available, reliable and scalable [1]

_weakness_

* (1) lack of support for complex queries [2]

* (2) lack of support for multi-table joins [2]

* (3) limited transaction support [2] 

* (4) difficult to achieve consistency across multi-document update [3]

_references_

* (1) http://www.oracle.com/us/corporate/press/519708

* (2) http://www.forbes.com/sites/oracle/2013/08/22/do-you-know-nosql/

* (3) http://stackoverflow.com/questions/(1)(2)(9)(9)000(9)/can-nosql-e-g-mongodb-replace-data-grid-solutions-e-g-oracle-coherence

####PostgreSQL

_strength_

* (1) open source and community driven

* (2) high-quality GUI: easy to use [1]

* (3) over-deployment is guaranteed to avoid [1]

* (4) rich feature set [2]

* (5) strong third-party support [2]

* (6) objective: it is not only a RDBMS, but also has objective features [2]

_weakness_

* (1) the performance is bad even for simple read-heavy operations [2]

* (2) not compatible with Windows [3]

* (3) not built-in support for web-application [3]

_references_

* (1) http://www.postgresql.org/about/advantages/

* (2) https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems

(3) http://forums.devshed.com/postgresql-help-21/advantages-disadvantages-postgresql-106805.html

####Solr

_strength_

(1) advanced Full-Text search capability: it provides capabilities including phrases, wildcards, joins, grouping and much more across any data type [1]

(2) large scales: it is good for high volume traffic [1]

* (3) easy monitoring: it prints log via JMX [1]

_weakness_

* (1) bad at update and commit [2]

_references_
 
(1) http://lucene.apache.org/solr/features.html

* (2) http://www.quora.com/Should-we-use-Solr-as-the-main-database-Is-there-any-advantage-or-disadvantage-over-using-a-traditional-RDBMS

####SQLite

_strength_

* (1) easy to manage: it requires little or no administration, very fit for embedded devices and applications [1]

* (2) zero-configuration: it does not need install [2]

* (3) serverless: it directly interact with disk, there’s no intermediary server process [2]

* (4) light weighted: the whole SQLite package is less than 500KB in size [2]

* (5) cross-platform file format: its database file can be directly copied to another machine with another platform and run [2]

_weakness_

* (1) cannot be used for high volume applications [1]

* (2) low concurrency: it only supports (1) write at any instant at a time [1]

* (3) cannot be used for very large datasets: it is limited in size to 140 TB [1]

_references_
 
* (1) http://www.sqlite.org/whentouse.html

* (2) https://www.sqlite.org/different.html

####XtremeData

_strength_

* (1) good performance for very large data set [1]

* (2) supports machine learning [1]

_weakness_

* (1) not good at complex relationship between tables [1]

_references_

* (1) http://www.xtremedata.com/articles/big-data-management-platforms-architecting-heterogeneous-solutions

####YarcData

_strength_ 

* (1) good analytics technology: it is the best analytics product [1]

_weakness_

* (1) it does not focus on database service [1]

_references_

* (1) http://www.cray.com/products/analytics/

####Zettaset

_strength_

* (1) good security features: includes encryption, role-based access control, kerberos and policy enforcement [1] 

* (2) easy to use: it has automatic Hadoop installation and on-going management [1]

* (3) good Hadoop availability and reliability: it provides good availability for all critical Hadoop services [1]

* (4) consistent monitoring [1]

_weakness_

* (1) it is a young company, so the service is somehow defocus [2]

_reference_

* (1) http://www.zettaset.com/index.php/products/enterprise-hadoop-cluster-management/

* (2) http://www.softwarememories.com/2011/07/10/when-professional-services-and-software-mix/

####Zimory Scale 

_strength_

* (1) globally distributed: it has multi-site data center and infrastructure management around the world [1]

* (2) good security: it provides enterprise level security features [1]

_weakness_

* (1) not convenient: only provide basic service, not fully managed [1]

_reference_

* (1) http://www.zimory.com/en/solutions/why-zimory/global-cloud-services.html
