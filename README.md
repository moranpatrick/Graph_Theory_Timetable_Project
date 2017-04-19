# Graph Theory Project 2017
## Patrick Moran

## [Contents](#contents)  
[Introduction](#intro)  
[About NEO4J](#about)   
[Stored Data](#storedData)  
[My Strategy](#strategy)  
[Implementation](#implementation)  
[Conclusion](#conclusion)  
[References](#references)

## Introduction<a name = "intro"></a>   
This Project contains a Neo4j database for use in a timetabling system for GMIT, Galway. The following document contains all of my design ideas and the instructions to use with this project.  
The database stores information about my current third year, semester 2, software development timetable. Main Information Stored:    
* Lecturer Name
* Room
* Time
* Student Group
* Subject

[Top](#contents)  
## About NEO4J<a name = "about"></a>
![alt text](http://info.neo4j.com/rs/773-GON-065/images/neo4j_logo.png)  
<p>[Neo4j](https://neo4j.com/) is a graph database management system. Neo4j is an ACID based system, ACID standing for Atomicity, Consistency, Isolation, Durability. Acid is a set of properties of database transactions. To be considered ACID, the database must satisfy these properties. </p>

<p>Neo4j community is a free open source software which is great for me as I'm a student interested in learning about it. There are also enterprise and government editions which require a license to use. Neo4j can be downloaded [here](https://neo4j.com/download/).</p>

<p>Neo4j is implemented in java and works on all platforms.</p>

##### Data
<p>Data in a Neo4j database is stored as either a node, an edge or an attribute. Each node and edge can have any number of attributes. Nodes and edges can also have labels. These labels can then be used to quickly find what your searching for. </p>  

##### Cypher
Cypher is a graph query language, similar to SQL, developed by Neo Technology to use with Neo4j graph database. Cypher is used to visually describe patterns in graphs.
Some cypher examples:  

Create a Node:      
``CREATE (you:Person {name:"You"})
RETURN you``        

Add a new relationship:  
``MATCH  (you:Person {name:"You"})  
CREATE (you)-[like:LIKE]->(neo:Database {name:"Neo4j" })  
RETURN you,like,neo ``

[Top](#contents)

## Stored Data<a name = "storedData"></a>
[Top](#contents)

## My Strategy<a name = "strategy"></a>
[Top](#contents)

## Implementation<a name = "implementation"></a>
[Top](#contents)

## Conclusion<a name = "conclusion"></a>
[Top](#contents)

## References<a name = "references"></a>
* http://info.neo4j.com/rs/773-GON-065/images/neo4j_logo.png  
* https://en.wikipedia.org/wiki/Neo4j  
* https://neo4j.com/developer/cypher-query-language/    

[Top](#contents)  
