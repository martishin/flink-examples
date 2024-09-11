# Flink Examples
## Running Batch Job Locally
* Build the job   
``` shell
./gradlew :batch:build
```
* Start the Flink cluster:   
``` shell
docker-compose up
```  
* Sumit the job:
``` shell
docker exec -it flink_jobmanager flink run /jars/batch-1.0-SNAPSHOT.jar
```
