###Relational Database

_popular db_

* (1) Oracle Database

* (2) MySQL

* (3) PostgreSQL

_strength_

* (1) flexible and well-established [1]

* (2) rich and useful query set: it handles multiple relationships between multiple entities well [3]

* (3) having extensive join capabilities [3]

* (4) experienced and well standard [3]

* (5) good performance with consistent schema [3]

_weakness_

* (1) lack of support for complex data types, such as complex JSON objects [1]

* (2) not scale out easily on commodity clusters [2]

* (3) bad performance when the data is of huge volume [3]

* (4) cannot handle semi-structure or variable structure [3]

_references_

* (1) http://it.toolbox.com/blogs/enterprise-solutions/some-pros-cons-of-relational-databases-24144

* (2) http://www.techrepublic.com/blog/10-things/10-things-you-should-know-about-nosql-databases/

* (3) http://stackoverflow.com/questions/13528216/motivations-for-using-relational-database-orm-or-document-database-odm

###Non-Relational Database

_popular db_

* (1) MongoDB

* (2) Redis

_strength_

* (1) elastic scaling: it is scalable to huge volume of data [1]

* (2) high availability and sharing [1]

* (3) capacity to handle semi-structure and various structure [1]

* (4) flexible data model: good for expression of web application [1]

* (5) no need to translate relation to object [1]

_weakness_

* (1) no join: it is hard to achieve cross-table features [1]

* (2) no transaction: it will cause less security [1] 

* (3) lack of maturity: developers and administrators usually lacks mature knowledge and skills [2]

* (4) not good with analytics: the monitor and analytics is complicate for non-relational databases [2]

_references_

* (1) http://stackoverflow.com/questions/13528216/motivations-for-using-relational-database-orm-or-document-database-odm

* (2) http://greendatacenterconference.com/blog/the-five-key-advantages-and-disadvantages-of-nosql/

###Grid/cache 

_popular db_

* (1) AWS ElastiCache

* (2) Memcached

_strength_

* (1) good performance: RAM is faster than disk [1]

* (2) flexible data structure: it uses key-value store [1]

* (3) good scalability and easy to operate [1]

* (4) powerful analysis capabilities: it is easy to analyze data in the grid [2]

* (5) easy management [2]

_weakness_

* (1) relative immaturity: developers do not have much experience about it [3]

* (2) potential bad performance at certain condition: results of processes are sent first on all nodes within the grid [3]

* (3) not easy to handle the grid: the technology is costly [3]

_references_

* (1) http://highscalability.com/blog/2011/12/21/in-memory-data-grid-technologies.html

* (2) http://www.scaleoutsoftware.com/products/technology/

* (3) http://www.brighthub.com/environment/green-computing/articles/107038.aspx
