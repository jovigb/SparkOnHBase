##RowCounter
HADOOP_CLASSPATH=&acute;hbase classpath&acute; hadoop jar /opt/cloudera/parcels/CDH/jars/hbase-server-1.2.0-cdh5.7.2.jar rowcounter t1

hbase org.apache.hadoop.hbase.mapreduce.RowCounter t1

##nc stream service
cat access.log | nc -lk cdh180 9977
