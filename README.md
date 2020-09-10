# bigdata-cluster
We will create docker containers for big data services such as Spark, Kafka, Cassandra..

## Spark
We will create a master container and two workers.  
For the master container, the bde2020/spark-master image will be user.  
As for the workers containers, we will use the image bde2020/spark-worker.

## Cassandra
We have two containers for Cassandra. The first one is for the SEEDS container and based on the image datastax/dse-server.  
For the second container, we used also the same image but it's a simple a container that depends on the first SEED.
## Kafka
LOADING ..

## Airflow
LOADING ..

## Jenkins
LOADING

## Kubernetes
LOADING ..


##Usage
To start the cluster, type this command:
```
cd bigdata-cluster
docker-compose up -d
```
To shutdown the cluster, you need to type the command below:
```
docker-compose down
```