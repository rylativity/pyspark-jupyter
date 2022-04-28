### Setup
- Run `docker-compose up -d` to bring up the spark cluster and jupyter server
- Navigate to http://localhost:8888 in your browser to find jupyter
- Follow sample notebooks to get started and connect to the Spark cluster with Pyspark
- If you want to use additional local data (e.g CSVs, JSON, etc), drop the files in the data folder (this folder is bind-mounted to all containers at /data inside the container)