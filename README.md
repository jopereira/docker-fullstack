# Hive + HBase + Spark docker

This is a combination of these three repositories:

 * https://github.com/big-data-europe/docker-hive
 * https://github.com/big-data-europe/docker-hbase
 * https://github.com/big-data-europe/docker-spark

In addition, Hive is configured to use Spark and to access HBase tables.
HBase is configured for storage in the same HDFS as Hive. Presto 
has been removed.o

Currently using Spark 2.4.5 due to issue with HBase from Hive in Spark 3.1.1 images.

See original repositories for more details.
