# Food Order System

Implementasi sistem pemesanan makan secara online menggunakan arsitektur Clean dan Hexagonal.
Di dalam projek ini terdapat beberapa microservice seperti:
1. Order Service
2. Payment Service
3. Restaurant Service

## Graphviz

`mvn com.github.ferstl:depgraph-maven-plugin:aggregate -DcreateImage=true -DreduceEdges=false -Dscope=compile "-Dincludes=com.food.ordering.system*:*"`