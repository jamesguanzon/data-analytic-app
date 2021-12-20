# Data-Analytic Application

This small assignment project is a cloud computing "Big Data Queries" system, which features the ability to store data in a distributed file system (HDFS), and then analyse it using an analytics engine (Apache Spark), displaying the results in easy-to-understand visualisations in the form of tables / graphs (using Jupyter Notebook). Includes example bank customer data and queries which shows bank customer trends with result visualisation.

## How to Run

1. Ensure that you have docker-compose.

```sh
$ apt-get update && apt install docker-compose -y
```

2. Run using docker-compose up -d.

```sh
$ docker-compose up -d
```

3. Open up Jupyter Notebook! (port 8888)
