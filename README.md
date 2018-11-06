spark-test
==========

### Introduction
Example submitable Spark application to play with.

### Build the app
To build, you need Scala 2.12, git and maven on the box.
Do a git clone of this repo and then run:
```
cd spark-test
mvn clean package
```

### spark-submit
```
spark-submit --master yarn --deploy-mode cluster --class com.spark.Main spark-test-1.0-SNAPSHOT-jar-with-dependencies.jar
```
