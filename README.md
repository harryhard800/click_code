Before Running this please open the port of our machine of vm i:e(3000, 8081);
run the make file;
run Docker compose;

It will generate Fake data and send those data to kafka topics;
now flink will process those data and ingest into postgres database; 
Graphana and Prometheous will show you the real time data based on some refresh interval;
