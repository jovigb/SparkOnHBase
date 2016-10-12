##RowCounter
HADOOP_CLASSPATH="`hbase classpath`" hadoop jar /opt/cloudera/parcels/CDH/jars/hbase-server-1.2.0-cdh5.7.2.jar rowcounter t1
or
hbase org.apache.hadoop.hbase.mapreduce.RowCounter t1

##nc stream socket
cat access.log | nc -lk cdh180 9977
