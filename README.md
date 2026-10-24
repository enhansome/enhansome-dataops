# Awesome DataOps with stars

A curated list of awesome DataOps tools.

* [Awesome DataOps](#awesome-dataops)
  * [Data Catalog](#data-catalog)
  * [Data Exploration](#data-exploration)
  * [Data Ingestion](#data-ingestion)
  * [Data Processing](#data-processing)
  * [Data Quality](#data-quality)
  * [Data Serialization](#data-serialization)
    * [Data Compression](#data-compression)
    * [Data Table Format](#data-table-format)
  * [Data Visualization](#data-visualization)
  * [Data Warehouse](#data-warehouse)
  * [Data Workflow](#data-workflow)
  * [Database](#database)
    * [Columnar Database](#columnar-database)
    * [Document-Oriented Database](#document-oriented-database)
    * [Graph Database](#graph-database)
    * [Key-Value Database](#key-value-database)
    * [Relational Database](#relational-database)
    * [Time Series Database](#time-series-database)
    * [Vector Database](#vector-database)
  * [File System](#file-system)
  * [Logging and Monitoring](#logging-and-monitoring)
  * [Metadata Service](#metadata-service)
  * [SQL Playground](#sql-playground)
  * [SQL Query Engine](#sql-query-engine)
* [Resources](#resources)
  * [Books](#books)
  * [Other Lists](#other-lists)
  * [Slack](#slack)
* [Contributing](#contributing)

***

## Data Catalog

*Tools related to data cataloging.*

* [DataHub](https://github.com/linkedin/datahub) ⭐ 12,883 | 🐛 1,395 | 🌐 Python | 📅 2026-10-24 - LinkedIn's generalized metadata search & discovery tool.
* [CKAN](https://github.com/ckan/ckan) ⭐ 5,145 | 🐛 867 | 🌐 Python | 📅 2026-10-23 - Open-source DMS (data management system) for powering data hubs and data portals.
* [OpenLineage](https://github.com/OpenLineage/openlineage) ⭐ 2,721 | 🐛 412 | 🌐 Java | 📅 2026-10-21 - Open standard for metadata and lineage collection.
* [Marquez](https://github.com/MarquezProject/marquez) ⭐ 2,300 | 🐛 253 | 🌐 Java | 📅 2026-10-13 - Service for the collection, aggregation, and visualization of a data ecosystem's metadata.
* [Metacat](https://github.com/Netflix/metacat) ⭐ 1,691 | 🐛 59 | 🌐 Java | 📅 2026-10-24 - Unified metadata exploration API service for Hive, RDS, Teradata, Redshift, S3 and Cassandra.
* [Magda](https://github.com/magda-io/magda) ⭐ 606 | 🐛 406 | 🌐 JavaScript | 📅 2026-10-24 - A federated, open-source data catalog for all your big data and small data.
* [Amundsen](https://www.amundsen.io/) - Data discovery and metadata engine for improving the productivity when interacting with data.
* [Apache Atlas](https://atlas.apache.org) - Provides open metadata management and governance capabilities to build a data catalog.
* [OpenMetadata](https://open-metadata.org/) - A Single place to discover, collaborate and get your data right.
* [Unity Catalog](https://www.unitycatalog.io/) - Industry’s only universal catalog for data and AI.

## Data Exploration

*Tools for performing data exploration.*

* [Marimo](https://github.com/marimo-team/marimo) ⭐ 23,311 | 🐛 600 | 🌐 Python | 📅 2026-10-24 - A reactive Python notebook that's reproducible, git-friendly, and deployable as scripts or apps.
* [Jupytext](https://github.com/mwouts/jupytext) ⭐ 7,276 | 🐛 161 | 🌐 Python | 📅 2026-10-21 - Jupyter Notebooks as Markdown Documents, Julia, Python or R scripts.
* [Apache Zeppelin](https://zeppelin.apache.org/) - Enables data-driven, interactive data analytics and collaborative documents.
* [Jupyter Notebook](https://jupyter.org/) - Web-based notebook environment for interactive computing.
* [JupyterLab](https://jupyterlab.readthedocs.io) - The next-generation user interface for Project Jupyter.
* [Polynote](https://polynote.org/) - The polyglot notebook with first-class Scala support.

## Data Ingestion

*Tools for performing data ingestion.*

* [Apache Kafka](https://github.com/apache/kafka) ⭐ 34,115 | 🐛 670 | 🌐 Java | 📅 2026-10-24 - Open-source distributed event streaming platform used by thousands of companies.
* [Apache Pulsar](https://github.com/apache/pulsar) ⭐ 15,351 | 🐛 670 | 🌐 Java | 📅 2026-10-24 - Distributed pub-sub messaging platform with a flexible messaging model and intuitive API.
* [Fluentd](https://github.com/fluent/fluentd) ⭐ 13,610 | 🐛 119 | 🌐 Ruby | 📅 2026-10-23 - Collects events from various data sources and writes them to files.
* [Apache Gobblin](https://github.com/apache/gobblin) ⭐ 2,270 | 🐛 142 | 🌐 Java | 📅 2026-10-15 - A framework that simplifies common aspects of big data such as data ingestion.
* [Pravega](https://github.com/pravega/pravega) ⭐ 2,002 | 🐛 246 | 🌐 Java | 📅 2025-03-02 - An open source distributed storage service implementing Streams.
* [Embulk](https://github.com/embulk/embulk) ⭐ 1,785 | 🐛 167 | 🌐 Java | 📅 2026-10-08 - A parallel bulk data loader that helps data transfer between various storages.
* [Nakadi](https://github.com/zalando/nakadi) ⚠️ Archived - A distributed event bus that implements a RESTful API abstraction on top of Kafka-like queues.
* [Amazon Kinesis](https://aws.amazon.com/kinesis/) - Easily collect, process, and analyze video and data streams in real time.
* [Google PubSub](https://cloud.google.com/pubsub) - Ingest events for streaming into BigQuery, data lakes or operational databases.
* [RabbitMQ](https://www.rabbitmq.com/) - One of the most popular open source message brokers.

## Data Workflow

*Tools related to data workflow/pipeline.*

* [Apache Airflow](https://github.com/apache/airflow) ⭐ 47,268 | 🐛 1,929 | 🌐 Python | 📅 2026-10-24 - A platform to programmatically author, schedule, and monitor workflows.
* [Luigi](https://github.com/spotify/luigi) ⭐ 18,783 | 🐛 193 | 🌐 Python | 📅 2026-10-14 - Python module that helps you build complex pipelines of batch jobs.
* [Dagster](https://github.com/dagster-io/dagster) ⭐ 16,321 | 🐛 2,612 | 🌐 Python | 📅 2026-10-23 - An orchestration platform for the development, production, and observation of data assets.
* [Azkaban](https://github.com/azkaban/azkaban) ⭐ 4,511 | 🐛 802 | 🌐 Java | 📅 2024-07-03 - Batch workflow job scheduler created at LinkedIn to run Hadoop jobs.
* [Apache Oozie](https://github.com/apache/oozie) ⚠️ Archived - An extensible, scalable and reliable system to manage complex Hadoop workloads.
* [Prefect](https://docs.prefect.io/) - A workflow management system, designed for modern infrastructure.

## Data Processing

*Tools related to data processing (batch and stream).*

* [Apache Spark](https://github.com/apache/spark) ⭐ 44,295 | 🐛 696 | 🌐 Scala | 📅 2026-10-24 - A unified analytics engine for large-scale data processing.
* [Apache Flink](https://github.com/apache/flink) ⭐ 26,422 | 🐛 398 | 🌐 Java | 📅 2026-10-24 - An open source stream processing framework with powerful capabilities.
* [Apache Beam](https://github.com/apache/beam) ⭐ 8,691 | 🐛 3,857 | 🌐 Java | 📅 2026-10-24 - A unified model for defining both batch and streaming data-parallel processing pipelines.
* [Faust](https://github.com/robinhood/faust) ⭐ 6,823 | 🐛 280 | 🌐 Python | 📅 2024-07-27 - A stream processing library, porting the ideas from Kafka Streams to Python.
* [Apache Storm](https://github.com/apache/storm) ⭐ 6,697 | 🐛 42 | 🌐 Java | 📅 2026-10-24 - An open source distributed realtime computation system.
* [Apache Nifi](https://github.com/apache/nifi) ⭐ 6,274 | 🐛 53 | 🌐 Java | 📅 2026-10-23 - An easy to use, powerful, and reliable system to process and distribute data.
* [Apache Samza](https://github.com/apache/samza) ⭐ 844 | 🐛 44 | 🌐 Java | 📅 2026-09-01 - A distributed stream processing framework which uses Apache Kafka and Hadoop YARN.
* [Apache Tez](https://github.com/apache/tez) ⭐ 521 | 🐛 78 | 🌐 Java | 📅 2026-10-08 - A generic data-processing pipeline engine envisioned as a low-level engine.
* [Apache Hadoop MapReduce](https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html) - A framework for writing applications which process vast amounts of data.
* [skrub](http://skrub-data.org) - Python library to ease preprocessing and feature engineering for tabular machine learning.

## Data Quality

*Tools for ensuring data quality.*

* [Cleanlab](https://github.com/cleanlab/cleanlab) ⭐ 11,719 | 🐛 138 | 🌐 Python | 📅 2026-01-13 - Data-centric AI tool to detect (non-predefined) issues in ML data like label errors or outliers.
* [Deequ](https://github.com/awslabs/deequ) ⭐ 3,656 | 🐛 62 | 🌐 Scala | 📅 2026-10-20 - A library built on top of Apache Spark for measuring data quality in large datasets.
* [Cerberus](https://github.com/pyeve/cerberus) ⭐ 3,281 | 🐛 28 | 🌐 Python | 📅 2026-10-01 - Lightweight, extensible data validation library for Python.
* [DataProfiler](https://github.com/capitalone/DataProfiler) ⭐ 1,595 | 🐛 86 | 🌐 Python | 📅 2026-09-14 - A Python library designed to make data analysis, monitoring, and sensitive data detection easy.
* [SodaSQL](https://github.com/sodadata/soda-sql) ⚠️ Archived - Data profiling, testing, and monitoring for SQL accessible data.
* [Great Expectations](https://greatexpectations.io) - A Python data validation framework that allows to test your data against datasets.
* [JSON Schema](https://json-schema.org/) - A vocabulary that allows you to annotate and validate JSON documents.

## Data Serialization

*Tools related to data serialization.*

* [ProtoBuf](https://github.com/protocolbuffers/protobuf) ⭐ 72,129 | 🐛 408 | 🌐 C++ | 📅 2026-10-24 - Language-neutral, platform-neutral, extensible mechanism for serializing structured data.
* [Kryo](https://github.com/EsotericSoftware/kryo) ⭐ 6,546 | 🐛 5 | 🌐 HTML | 📅 2026-10-22 - A fast and efficient binary object graph serialization framework for Java.
* [Apache Avro](https://github.com/apache/avro) ⭐ 3,307 | 🐛 266 | 🌐 Java | 📅 2026-10-18 - A data serialization system which is compact, fast and provides rich data structures.
* [Apache Parquet](https://github.com/apache/parquet-mr) ⭐ 3,088 | 🐛 701 | 🌐 Java | 📅 2026-10-24 - A columnar storage format which provides efficient storage and encoding of data.
* [Apache ORC](https://github.com/apache/orc) ⭐ 770 | 🐛 25 | 🌐 Java | 📅 2026-10-21 - A self-describing type-aware columnar file format designed for Hadoop workloads.

### Data Compression

* [Snappy](https://github.com/google/snappy) ⭐ 6,622 | 🐛 66 | 🌐 C++ | 📅 2026-10-23 - Open source compression library that is fast, stable and robuts.
* [Pigz](https://github.com/madler/pigz) ⭐ 2,978 | 🐛 18 | 🌐 C | 📅 2025-08-16 - A parallel implementation of gzip for modern multi-processor, multi-core machines.

### Data Table Format

* [Apache Iceberg](https://github.com/apache/iceberg) ⭐ 9,362 | 🐛 931 | 🌐 Java | 📅 2026-10-24 - Open table format for huge analytic datasets.
* [Delta Lake](https://github.com/delta-io/delta) ⭐ 9,053 | 🐛 987 | 🌐 Scala | 📅 2026-10-23 - An open source project that enables building a Lakehouse architecture on top of data lakes.
* [Apache Hudi](https://github.com/apache/hudi) ⭐ 6,338 | 🐛 3,049 | 🌐 Java | 📅 2026-10-24 - Manages the storage of large analytical datasets on DFS.

## Data Visualization

*Tools for performing data visualization (DataViz).*

* [Apache Superset](https://github.com/apache/superset) ⭐ 75,288 | 🐛 599 | 🌐 Python | 📅 2026-10-24 - A modern data exploration and data visualization platform.
* [Dash](https://github.com/plotly/dash) ⭐ 24,468 | 🐛 433 | 🌐 Python | 📅 2026-10-23 - Analytical Web Apps for Python, R, Julia, and Jupyter.
* [Lux](https://github.com/lux-org/lux) ⭐ 5,378 | 🐛 90 | 🌐 Python | 📅 2024-03-20 - Fast and easy data exploration by automating the visualization and data analysis process.
* [HUE](https://github.com/cloudera/hue) ⭐ 1,406 | 🐛 18 | 🌐 JavaScript | 📅 2026-10-23 - A mature SQL Assistant for querying Databases & Data Warehouses.
* [Count](https://count.co) - SQL/drag-and-drop querying and visualisation tool based on notebooks.
* [Data Studio](https://datastudio.google.com) - Reporting solution for power users who want to go beyond the data and dashboards of GA.
* [Metabase](https://www.metabase.com/) - The simplest, fastest way to get business intelligence and analytics to everyone.
* [Redash](https://redash.io/) - Connect to any data source, easily visualize, dashboard and share your data.
* [Tableau](https://www.tableau.com) - Powerful and fastest growing data visualization tool used in the business intelligence industry.

## Data Warehouse

*Tools related to storing data in data warehouses (DW).*

* [Apache Hive](https://github.com/apache/hive) ⭐ 6,034 | 🐛 125 | 🌐 Java | 📅 2026-10-24 - Facilitates reading, writing, and managing large datasets residing in distributed storage.
* [Apache Kylin](https://github.com/apache/kylin) ⭐ 3,782 | 🐛 78 | 🌐 Java | 📅 2026-10-19 - An open source, distributed analytical data warehouse for big data.
* [Amazon Redshift](https://aws.amazon.com/redshift/) - Accelerate your time to insights with fast, easy, and secure cloud data warehousing.
* [Google BigQuery](https://cloud.google.com/bigquery) - Serverless, highly scalable, and cost-effective multicloud data warehouse.

## Database

*Database tools for storing data.*

### Columnar Database

* [Scylla](https://github.com/scylladb/scylla) ⭐ 15,799 | 🐛 3,043 | 🌐 C++ | 📅 2026-10-24 - Designed to be compatible with Cassandra while achieving higher throughputs and lower latencies.
* [Apache Druid](https://github.com/apache/druid) ⭐ 14,093 | 🐛 787 | 🌐 Java | 📅 2026-10-24 - Designed to quickly ingest massive quantities of event data, and provide low-latency queries.
* [Apache Cassandra](https://github.com/apache/cassandra) ⭐ 10,117 | 🐛 547 | 🌐 Java | 📅 2026-10-23 - Open source column based DBMS designed to handle large amounts of data.
* [Apache HBase](https://github.com/apache/hbase) ⭐ 5,566 | 🐛 420 | 🌐 Java | 📅 2026-10-23 - An open-source, distributed, versioned, column-oriented store.

### Document-Oriented Database

* [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 78,359 | 🐛 6,173 | 🌐 Java | 📅 2026-10-24 - A distributed document oriented database with a RESTful search engine.
* [MongoDB](https://github.com/mongodb/mongo) ⭐ 28,659 | 🐛 37 | 🌐 C++ | 📅 2026-10-24 - A cross-platform document database that uses JSON-like documents with optional schemas.
* [RethinkDB](https://github.com/rethinkdb/rethinkdb) ⭐ 27,007 | 🐛 1,351 | 🌐 C++ | 📅 2026-10-17 - The first open-source scalable database built for realtime applications.
* [Apache CouchDB](https://github.com/apache/couchdb) ⭐ 6,986 | 🐛 371 | 🌐 Erlang | 📅 2026-10-23 - An open-source document-oriented NoSQL database, implemented in Erlang.

### Graph Database

* [Neo4j](https://github.com/neo4j/neo4j) ⭐ 17,354 | 🐛 233 | 🌐 Java | 📅 2026-10-23 - A high performance graph store with all the features expected of a mature and robust database.
* [ArangoDB](https://github.com/arangodb/arangodb) ⭐ 14,286 | 🐛 815 | 🌐 C++ | 📅 2026-10-24 - A scalable open-source multi-model database natively supporting graph, document and search.
* [JanusGraph](https://github.com/JanusGraph/janusgraph) ⭐ 5,862 | 🐛 579 | 🌐 Java | 📅 2026-10-24 - Manage large graphs with billions of data distributed across a multi-machine cluster.
* [Titan](https://github.com/thinkaurelius/titan) ⭐ 5,224 | 🐛 181 | 🌐 Java | 📅 2022-10-19 - A highly scalable graph database optimized for storing and querying large graphs.
* [Age](https://github.com/apache/age) ⭐ 4,912 | 🐛 260 | 🌐 C | 📅 2026-10-13 - A multi-model database that supports both graph and relational data models.
* [Memgraph](https://github.com/memgraph/memgraph) ⭐ 4,629 | 🐛 885 | 🌐 C++ | 📅 2026-10-24 - An open source graph database, built for real-time streaming data, compatible with Neo4j.

### Key-Value Database

* [Redis](https://github.com/redis/redis) ⭐ 77,079 | 🐛 3,064 | 🌐 C | 📅 2026-10-24 - An in-memory key-value database that persists on disk.
* [etcd](https://github.com/etcd-io/etcd) ⭐ 52,423 | 🐛 394 | 🌐 Go | 📅 2026-10-23 - Distributed reliable key-value store for the most critical data of a distributed system.
* [Dragonfly](https://github.com/dragonflydb/dragonfly) ⭐ 31,816 | 🐛 279 | 🌐 C++ | 📅 2026-10-24 - A modern in-memory datastore, fully compatible with Redis and Memcached APIs.
* [Memcached](https://github.com/memcached/memcached) ⭐ 14,298 | 🐛 112 | 🌐 C | 📅 2026-09-11 - A high performance multithreaded event-based key/value cache store.
* [EVCache](https://github.com/Netflix/EVCache) ⭐ 2,225 | 🐛 24 | 🌐 Java | 📅 2026-10-15 - A distributed in-memory data store for the cloud.
* [Apache Accumulo](https://github.com/apache/accumulo) ⭐ 1,182 | 🐛 352 | 🌐 Java | 📅 2026-10-23 - A sorted, distributed key-value store that provides robust and scalable data storage.
* [DynamoDB](https://aws.amazon.com/dynamodb/) - Fast, flexible NoSQL database service for single-digit millisecond performance at any scale.

### Relational Database

* [CockroachDB](https://github.com/cockroachdb/cockroach) ⭐ 32,577 | 🐛 8,228 | 🌐 Go | 📅 2026-10-21 - A distributed database designed to build, scale, and manage data-intensive apps.
* [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,540 | 🐛 0 | 🌐 C | 📅 2026-10-23 - An advanced RDBMS that supports an extended subset of the SQL standard.
* [RQLite](https://github.com/rqlite/rqlite) ⭐ 17,849 | 🐛 67 | 🌐 Go | 📅 2026-10-24 - A lightweight, distributed relational database, which uses SQLite as its storage engine.
* [MySQL](https://github.com/mysql/mysql-server) ⭐ 12,475 | 🐛 130 | 🌐 C++ | 📅 2026-10-21 - One of the most popular open source transactional databases.
* [SQLite](https://github.com/sqlite/sqlite) ⭐ 10,775 | 🐛 26 | 🌐 C | 📅 2026-10-24 - A popular choice as embedded database software for local/client storage.
* [MariaDB](https://github.com/MariaDB/server) ⭐ 8,442 | 🐛 570 | 🌐 C++ | 📅 2026-10-24 - A replacement of MySQL with more features, new storage engines and better performance.
* [Crate](https://github.com/crate/crate) ⭐ 4,444 | 🐛 320 | 🌐 Java | 📅 2026-10-23 - A distributed SQL database that makes it simple to store and analyze massive amounts of data.

### Time Series Database

* [InfluxDB](https://github.com/influxdata/influxdb) ⭐ 31,781 | 🐛 2,179 | 🌐 Rust | 📅 2026-10-23 - Scalable datastore for metrics, events, and real-time analytics.
* [TimescaleDB](https://github.com/timescale/timescaledb) ⭐ 23,745 | 🐛 441 | 🌐 C | 📅 2026-10-24 - Open-source time-series SQL database optimized for fast ingest and complex queries.
* [QuestDB](https://github.com/questdb/questdb) ⭐ 17,470 | 🐛 1,286 | 🌐 Java | 📅 2026-10-24 - An open source SQL database designed to process time series data, faster.
* [Atlas](https://github.com/Netflix/Atlas) ⭐ 3,578 | 🐛 8 | 🌐 Scala | 📅 2026-10-23 - An in-memory dimensional time series database.
* [Akumuli](https://github.com/akumuli/Akumuli) ⚠️ Archived - Can be used to capture, store and process time-series data in real-time.

### Vector Database

* [Milvus](https://github.com/milvus-io/milvus/) ⭐ 46,466 | 🐛 1,468 | 🌐 Go | 📅 2026-10-23 - An open source embedding vector similarity search engine powered by Faiss, NMSLIB and Annoy.
* [Qdrant](https://github.com/qdrant/qdrant) ⭐ 35,228 | 🐛 796 | 🌐 Rust | 📅 2026-10-23 - An open source vector similarity search engine with extended filtering support.
* [Pinecone](https://www.pinecone.io) - Managed and distributed vector similarity search used with a lightweight SDK.

## File System

*Tools related to file system and data storage.*

* [MinIO](https://github.com/minio/minio) ⚠️ Archived - High Performance, Kubernetes Native Object Storage compatible with Amazon S3 API.
* [Alluxio](https://github.com/Alluxio/alluxio) ⭐ 7,253 | 🐛 1,048 | 🌐 Java | 📅 2026-09-01 - A virtual distributed storage system.
* [LakeFS](https://github.com/treeverse/lakeFS) ⭐ 5,569 | 🐛 455 | 🌐 Go | 📅 2026-10-21 - Open source tool that transforms your object storage into a Git-like repository.
* [GlusterFS](https://github.com/gluster/glusterfs) ⭐ 5,263 | 🐛 309 | 🌐 C | 📅 2026-10-24 - A software defined distributed storage that can scale to several petabytes.
* [Swift](https://github.com/openstack/swift) ⭐ 2,804 | 🐛 0 | 🌐 Python | 📅 2026-10-21 - A distributed object storage system designed to scale from a single machine to thousands of servers.
* [LizardFS](https://github.com/lizardfs/lizardfs) ⭐ 995 | 🐛 325 | 🌐 C++ | 📅 2024-08-11 - A highly reliable, scalable and efficient distributed file system.
* [SeaweedFS](https://github.com/chrislusf/seaweedfs) ⭐ 43 | 🐛 1 | 🌐 Go | 📅 2026-10-24 - A fast distributed storage system for blobs, objects, files, and data lake.
* [Amazon Simple Storage Service (S3)](https://aws.amazon.com/s3/) - Object storage built to retrieve any amount of data from anywhere.
* [Apache Hadoop Distributed File System (HDFS)](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html) - A distributed file system.
* [Google Cloud Storage (GCS)](https://cloud.google.com/storage) - Object storage for companies of all sizes, to store any amount of data.

## Logging and Monitoring

*Tools used for logging and monitoring data workflows.*

* [Grafana](https://github.com/grafana/grafana) ⭐ 77,477 | 🐛 3,332 | 🌐 TypeScript | 📅 2026-10-24 - Visualize metrics, logs, and traces from multiple sources like Prometheus, Loki, InfluxDB and more.
* [Prometheus](https://github.com/prometheus/prometheus) ⭐ 66,735 | 🐛 1,020 | 🌐 Go | 📅 2026-10-24 - A monitoring system and time series database.
* [Loki](https://github.com/grafana/loki) ⭐ 29,053 | 🐛 1,185 | 🌐 Go | 📅 2026-10-24 - A horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus.
* [Whylogs](https://github.com/whylabs/whylogs) ⭐ 2,836 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2025-01-10 - A tool for creating data logs, enabling monitoring for data drift and data quality issues.

## Metadata Service

*Tools used for storing and serving metadata.*

* [Hive Metastore](https://cwiki.apache.org/confluence/display/hive/design#Design-Metastore) - Service that stores metadata related to Apache Hive and other services.
* [Metacat](https://github.com/Netflix/metacat) ⭐ 1,691 | 🐛 59 | 🌐 Java | 📅 2026-10-24 - Provides you information about what data you have, where it resides and how to process it.

## SQL Playground

*Tools for testing and sharing SQL snippets in mock databases.*

* [RunSQL](https://runsql.com/) - Free online SQL playground for MySQL, PostgreSQL, and SQL Server.
* [SQLFiddle](https://sqlfiddle.com/) - Online SQL compiler for learning and practicing SQL.

## SQL Query Engine

*Tools for parallel processing SQL statements.*

* [Presto](https://github.com/prestodb/presto) ⭐ 16,760 | 🐛 3,016 | 🌐 Java | 📅 2026-10-24 - A distributed SQL query engine for big data.
* [Trino](https://github.com/trinodb/trino) ⭐ 13,364 | 🐛 2,735 | 🌐 Java | 📅 2026-10-24 - A fast distributed SQL query engine for big data analytics.
* [Apache Drill](https://github.com/apache/drill) ⭐ 2,027 | 🐛 129 | 🌐 Java | 📅 2026-10-21 - Schema-free SQL Query Engine for Hadoop, NoSQL and Cloud Storage.
* [Apache Impala](https://github.com/apache/impala) ⭐ 1,292 | 🐛 8 | 🌐 C++ | 📅 2026-10-23 - Lightning-fast, distributed SQL queries for petabytes of data.
* [Dremio](https://www.dremio.com/) - Power high-performing BI dashboards and interactive analytics directly on data lake.

***

# Resources

Where to discover new tools and discuss about existing ones.

## Books

* [Data Mesh: Delivering Data-Driven Value at Scale](https://www.oreilly.com/library/view/data-mesh/9781492092384/) (O'Reilly)
* [Designing Data-Intensive Applications](https://www.oreilly.com/library/view/designing-data-intensive-applications/9781491903063/) (O'Reilly)
* [Fundamentals of Data Engineering](https://www.oreilly.com/library/view/fundamentals-of-data/9781098108298/) (O'Reilly)
* [Getting Started with Impala](https://www.oreilly.com/library/view/getting-started-with/9781491905760/) (O'Reilly)
* [Learning and Operating Presto](https://www.oreilly.com/library/view/learning-and-operating/9781098141844/) (O'Reilly)
* [Learning Spark: Lightning-Fast Data Analytics](https://www.oreilly.com/library/view/learning-spark-2nd/9781492050032/) (O'Reilly)
* [Spark in Action](https://www.oreilly.com/library/view/spark-in-action/9781617295522/) (O'Reilly)
* [Spark: The Definitive Guide](https://www.oreilly.com/library/view/spark-the-definitive/9781491912201/) (O'Reilly)

## Other Lists

* [Awesome Data Engineering](https://github.com/igorbarinov/awesome-data-engineering) ⭐ 9,204 | 🐛 57 | 📅 2026-09-07
* [Awesome MLOps](https://github.com/kelvins/awesome-mlops) ⭐ 5,291 | 🐛 106 | 🌐 Python | 📅 2026-08-17
* [DataOps Resource](https://github.com/chen1649chenli/dataOpsResource) ⭐ 24 | 🐛 2 | 📅 2020-08-14

## Slack

* [Delta Lake Workspace](https://delta-users.slack.com/ssb/redirect)
* [Trino Workspace](https://trinodb.slack.com/ssb/redirect)

***

# Contributing

All contributions are welcome! Please take a look at the [contribution guidelines](https://github.com/kelvins/awesome-dataops/blob/main/CONTRIBUTING.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-24._
