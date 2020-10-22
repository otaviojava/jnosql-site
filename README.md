# Eclipse JNoSQL

![JNoSQL Logo](http://www.jnosql.org/images/home_logo.png)



The Eclipse JNoSQL is a framework to help developers create enterprise-grade applications using Java and NoSQL technologies. It helps them create scalable applications while maintaining low coupling with the underlying NoSQL technology.



## What is Eclipse JNoSQL?

Eclipse JNoSQL is a Java framework that streamlines the integration of Java applications with NoSQL databases. It defines a set of APIs and provides a standard implementation for most NoSQL databases. This clearly helps to achieve very low coupling with the underlying NoSQL technologies used in applications.

The project has two layers:

1. *Communication Layer*: A set of APIs that defines communication with NoSQL databases. Compared with traditional the RDBMS world, they are like the JDBC API. It contains four modules, one for each NoSQL database type: Key-Value, Column Family, Document, and Graph.

1. *Mapping Layer*: These APIs help developers to integrate their Java application with the NoSQL database. This layer is annotation-driven and uses technologies like CDI and Bean Validation, making it simple for developers to use. In the traditional RDBMS world, this layer can be compared to the Java Persistence API or object-relational mapping frameworks such as Hibernate.


![](http://www.jnosql.org/images/layers.png)

