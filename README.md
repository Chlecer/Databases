# Databases

This README provides a concise overview of key database concepts, helping you navigate the intricacies of databases and their significance in the context of Microservices or Monolithic architectures. From the basics of computer storage to the nuances of data persistence and performance trade-offs, this guide aims to demystify the world of databases and empower you with essential insights.

## Understanding Database Concepts for Microservices

In today's rapidly evolving world of software development, databases play a pivotal role in shaping the efficiency and performance of applications. Whether you're just starting your career or have been in the field for a while, a solid grasp of database concepts is fundamental. This is even more crucial with the advent of Microservices architecture, where choosing the right database can make all the difference.

Whether you're a developer, a systems designer, or simply someone eager to deepen their understanding of databases, this resource offers a valuable starting point to explore the intersection of databases and Microservices architecture.

So, let's dive into the world of databases and discover how their nuances can shape the success of your applications!

[Here](https://javachallengers.com/storage-and-databases) you can have a quick and nice overview from DelNero site.

I put here a resume important based on DelNero article:

This table provides a quick overview of key concepts related to databases and their importance in Microservices architecture.

| Aspect                          | Explanation                                                                                                          |
|---------------------------------|----------------------------------------------------------------------------------------------------------------------|
| Databases and Microservices     | Databases are essential for developers to grasp, especially with Microservices. Choosing the right database matters. |
| Computer Storage                | Digital space for data storage, including primary (RAM, Cache) and secondary (HDD, SSD) storage.                   |
| Data in Disk                    | Databases like Postgres, MySQL store data on disk for persistence.                                                |
| Data in Memory                  | In-memory databases (Redis, Hazelcast) store data in RAM for fast access, with the drawback of data loss on outage. |
| Databases                       | Structured storage, retrieval, and management of data, organized in tables of rows and columns.                   |
| RDBMS (Relational DBMS)          | Databases like Postgres, MySQL use tables to relate data, ensuring reliability and availability.                  |
| ACID Transactions               | ACID properties ensure reliable and consistent database transactions: Atomicity, Consistency, Isolation, Durability. |
| NoSQL                           | NoSQL databases (key-value, document, column-family, graph) offer scalability and performance advantages.        |
| CAP Theorem                     | Consistency, Availability, Partition Tolerance (CAP) trade-offs influence database design choice.                |
| When to Use Relational Database | Structured, medium volume data requiring ACID compliance is suited for relational databases.                     |
| Reasons to Avoid Relational DB  | Relational databases struggle with horizontal scaling and massive data storage.                                   |
| When to Use NoSQL Database      | NoSQL databases excel with unstructured, large volume data and horizontal scaling.                               |
| Reasons to Avoid NoSQL          | NoSQL lacks ACID support, complex relational models are slow, and there's a learning curve for various NoSQL tech. |

