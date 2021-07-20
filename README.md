# Neo4j Connector for Apache Spark Zeppelin Notebooks

Collection of notebooks to get play with [Neo4j Connector for Apache Spark](https://github.com/neo4j-contrib/neo4j-spark-connector).

```
docker-compose up
```

If you want to get rid of the volume and the network:

```
docker-compose down
```

## Featuring

* Spark 2.4.5 with Scala 11
* Latest **Neo4j Connector for Apache Spark**
* [Neo4j Interpreter for Zeppelin](https://zeppelin.apache.org/docs/0.8.0/interpreter/neo4j.html)
* [Kinesis Connector for Structured Streaming](https://github.com/qubole/kinesis-sql)

## Getting Started

* Zeppelin [localhost:8080](http://localhost:8080)
* Neo4j Browser [localhost:7474](http://localhost:7474) (Username `neo4j`, Password `password`)

The Neo4j database data are volatile by default. 
If you want to change this behaviour check [these lines](https://github.com/utnaf/neo4j-connector-apache-spark-notebooks/blob/master/docker-compose.yml#L20-L22) in the `docker-compose.yml`.