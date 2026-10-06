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

* [DataHub](https://github.com/linkedin/datahub) ⭐ 12,794 | 🐛 1,319 | 🌐 Python | 📅 2026-10-06 - LinkedIn's generalized metadata search & discovery tool.
* [CKAN](https://github.com/ckan/ckan) ⭐ 5,128 | 🐛 863 | 🌐 Python | 📅 2026-10-06 - Open-source DMS (data management system) for powering data hubs and data portals.
* [OpenLineage](https://github.com/OpenLineage/openlineage) ⭐ 2,690 | 🐛 417 | 🌐 Java | 📅 2026-10-06 - Open standard for metadata and lineage collection.
* [Marquez](https://github.com/MarquezProject/marquez) ⭐ 2,284 | 🐛 252 | 🌐 Java | 📅 2026-09-27 - Service for the collection, aggregation, and visualization of a data ecosystem's metadata.
* [Metacat](https://github.com/Netflix/metacat) ⭐ 1,691 | 🐛 58 | 🌐 Java | 📅 2026-10-01 - Unified metadata exploration API service for Hive, RDS, Teradata, Redshift, S3 and Cassandra.
* [Magda](https://github.com/magda-io/magda) ⭐ 608 | 🐛 400 | 🌐 JavaScript | 📅 2026-10-06 - A federated, open-source data catalog for all your big data and small data.
* [Amundsen](https://www.amundsen.io/) - Data discovery and metadata engine for improving the productivity when interacting with data.
* [Apache Atlas](https://atlas.apache.org) - Provides open metadata management and governance capabilities to build a data catalog.
* [OpenMetadata](https://open-metadata.org/) - A Single place to discover, collaborate and get your data right.
* [Unity Catalog](https://www.unitycatalog.io/) - Industry’s only universal catalog for data and AI.

## Data Exploration

*Tools for performing data exploration.*

* [Marimo](https://github.com/marimo-team/marimo) ⭐ 23,035 | 🐛 609 | 🌐 Python | 📅 2026-10-06 - A reactive Python notebook that's reproducible, git-friendly, and deployable as scripts or apps.
* [Jupytext](https://github.com/mwouts/jupytext) ⭐ 7,260 | 🐛 161 | 🌐 Python | 📅 2026-10-06 - Jupyter Notebooks as Markdown Documents, Julia, Python or R scripts.
* [Apache Zeppelin](https://zeppelin.apache.org/) - Enables data-driven, interactive data analytics and collaborative documents.
* [Jupyter Notebook](https://jupyter.org/) - Web-based notebook environment for interactive computing.
* [JupyterLab](https://jupyterlab.readthedocs.io) - The next-generation user interface for Project Jupyter.
* [Polynote](https://polynote.org/) - The polyglot notebook with first-class Scala support.

## Data Ingestion

*Tools for performing data ingestion.*

* [Apache Kafka](https://github.com/apache/kafka) ⭐ 33,916 | 🐛 626 | 🌐 Java | 📅 2026-10-06 - Open-source distributed event streaming platform used by thousands of companies.
* [Apache Pulsar](https://github.com/apache/pulsar) ⭐ 15,343 | 🐛 1,772 | 🌐 Java | 📅 2026-10-05 - Distributed pub-sub messaging platform with a flexible messaging model and intuitive API.
* [Fluentd](https://github.com/fluent/fluentd) ⭐ 13,598 | 🐛 131 | 🌐 Ruby | 📅 2026-10-06 - Collects events from various data sources and writes them to files.
* [Apache Gobblin](https://github.com/apache/gobblin) ⭐ 2,270 | 🐛 142 | 🌐 Java | 📅 2026-09-24 - A framework that simplifies common aspects of big data such as data ingestion.
* [Pravega](https://github.com/pravega/pravega) ⭐ 2,000 | 🐛 246 | 🌐 Java | 📅 2025-03-02 - An open source distributed storage service implementing Streams.
* [Embulk](https://github.com/embulk/embulk) ⭐ 1,784 | 🐛 166 | 🌐 Java | 📅 2026-09-25 - A parallel bulk data loader that helps data transfer between various storages.
* [Nakadi](https://github.com/zalando/nakadi) ⚠️ Archived - A distributed event bus that implements a RESTful API abstraction on top of Kafka-like queues.
* [Amazon Kinesis](https://aws.amazon.com/kinesis/) - Easily collect, process, and analyze video and data streams in real time.
* [Google PubSub](https://cloud.google.com/pubsub) - Ingest events for streaming into BigQuery, data lakes or operational databases.
* [RabbitMQ](https://www.rabbitmq.com/) - One of the most popular open source message brokers.

## Data Workflow

*Tools related to data workflow/pipeline.*

* [Apache Airflow](https://github.com/apache/airflow) ⭐ 47,064 | 🐛 1,826 | 🌐 Python | 📅 2026-10-06 - A platform to programmatically author, schedule, and monitor workflows.
* [Luigi](https://github.com/spotify/luigi) ⭐ 18,781 | 🐛 180 | 🌐 Python | 📅 2026-07-18 - Python module that helps you build complex pipelines of batch jobs.
* [Dagster](https://github.com/dagster-io/dagster) ⭐ 16,240 | 🐛 2,573 | 🌐 Python | 📅 2026-10-05 - An orchestration platform for the development, production, and observation of data assets.
* [Azkaban](https://github.com/azkaban/azkaban) ⭐ 4,510 | 🐛 802 | 🌐 Java | 📅 2024-07-03 - Batch workflow job scheduler created at LinkedIn to run Hadoop jobs.
* [Apache Oozie](https://github.com/apache/oozie) ⚠️ Archived - An extensible, scalable and reliable system to manage complex Hadoop workloads.
* [Prefect](https://docs.prefect.io/) - A workflow management system, designed for modern infrastructure.

## Data Processing

*Tools related to data processing (batch and stream).*

* [Apache Spark](https://github.com/apache/spark) ⭐ 44,130 | 🐛 599 | 🌐 Scala | 📅 2026-10-06 - A unified analytics engine for large-scale data processing.
* [Apache Flink](https://github.com/apache/flink) ⭐ 26,385 | 🐛 405 | 🌐 Java | 📅 2026-10-05 - An open source stream processing framework with powerful capabilities.
* [Apache Beam](https://github.com/apache/beam) ⭐ 8,678 | 🐛 3,895 | 🌐 Java | 📅 2026-10-06 - A unified model for defining both batch and streaming data-parallel processing pipelines.
* [Faust](https://github.com/robinhood/faust) ⭐ 6,823 | 🐛 280 | 🌐 Python | 📅 2024-07-27 - A stream processing library, porting the ideas from Kafka Streams to Python.
* [Apache Storm](https://github.com/apache/storm) ⭐ 6,696 | 🐛 40 | 🌐 Java | 📅 2026-10-03 - An open source distributed realtime computation system.
* [Apache Nifi](https://github.com/apache/nifi) ⭐ 6,248 | 🐛 33 | 🌐 Java | 📅 2026-10-05 - An easy to use, powerful, and reliable system to process and distribute data.
* [Apache Samza](https://github.com/apache/samza) ⭐ 845 | 🐛 44 | 🌐 Java | 📅 2026-09-01 - A distributed stream processing framework which uses Apache Kafka and Hadoop YARN.
* [Apache Tez](https://github.com/apache/tez) ⭐ 520 | 🐛 78 | 🌐 Java | 📅 2026-10-01 - A generic data-processing pipeline engine envisioned as a low-level engine.
* [Apache Hadoop MapReduce](https://hadoop.apache.org/docs/current/hadoop-mapreduce-client/hadoop-mapreduce-client-core/MapReduceTutorial.html) - A framework for writing applications which process vast amounts of data.
* [skrub](http://skrub-data.org) - Python library to ease preprocessing and feature engineering for tabular machine learning.

## Data Quality

*Tools for ensuring data quality.*

* [Cleanlab](https://github.com/cleanlab/cleanlab) ⭐ 11,686 | 🐛 127 | 🌐 Python | 📅 2026-01-13 - Data-centric AI tool to detect (non-predefined) issues in ML data like label errors or outliers.
* [Deequ](https://github.com/awslabs/deequ) ⭐ 3,648 | 🐛 61 | 🌐 Scala | 📅 2026-09-16 - A library built on top of Apache Spark for measuring data quality in large datasets.
* [Cerberus](https://github.com/pyeve/cerberus) ⭐ 3,280 | 🐛 23 | 🌐 Python | 📅 2026-10-01 - Lightweight, extensible data validation library for Python.
* [DataProfiler](https://github.com/capitalone/DataProfiler) ⭐ 1,590 | 🐛 82 | 🌐 Python | 📅 2026-09-14 - A Python library designed to make data analysis, monitoring, and sensitive data detection easy.
* [SodaSQL](https://github.com/sodadata/soda-sql) ⚠️ Archived - Data profiling, testing, and monitoring for SQL accessible data.
* [Great Expectations](https://greatexpectations.io) - A Python data validation framework that allows to test your data against datasets.
* [JSON Schema](https://json-schema.org/) - A vocabulary that allows you to annotate and validate JSON documents.

## Data Serialization

*Tools related to data serialization.*

* [ProtoBuf](https://github.com/protocolbuffers/protobuf) ⭐ 72,098 | 🐛 439 | 🌐 C++ | 📅 2026-10-06 - Language-neutral, platform-neutral, extensible mechanism for serializing structured data.
* [Kryo](https://github.com/EsotericSoftware/kryo) ⭐ 6,546 | 🐛 5 | 🌐 HTML | 📅 2026-10-06 - A fast and efficient binary object graph serialization framework for Java.
* [Apache Avro](https://github.com/apache/avro) ⭐ 3,307 | 🐛 251 | 🌐 Java | 📅 2026-10-04 - A data serialization system which is compact, fast and provides rich data structures.
* [Apache Parquet](https://github.com/apache/parquet-mr) ⭐ 3,084 | 🐛 724 | 🌐 Java | 📅 2026-10-04 - A columnar storage format which provides efficient storage and encoding of data.
* [Apache ORC](https://github.com/apache/orc) ⭐ 769 | 🐛 21 | 🌐 Java | 📅 2026-09-25 - A self-describing type-aware columnar file format designed for Hadoop workloads.

### Data Compression

* [Snappy](https://github.com/google/snappy) ⭐ 6,617 | 🐛 69 | 🌐 C++ | 📅 2026-09-18 - Open source compression library that is fast, stable and robuts.
* [Pigz](https://github.com/madler/pigz) ⭐ 2,972 | 🐛 17 | 🌐 C | 📅 2025-08-16 - A parallel implementation of gzip for modern multi-processor, multi-core machines.

### Data Table Format

* [Apache Iceberg](https://github.com/apache/iceberg) ⭐ 9,303 | 🐛 927 | 🌐 Java | 📅 2026-10-06 - Open table format for huge analytic datasets.
* [Delta Lake](https://github.com/delta-io/delta) ⭐ 9,039 | 🐛 968 | 🌐 Scala | 📅 2026-10-06 - An open source project that enables building a Lakehouse architecture on top of data lakes.
* [Apache Hudi](https://github.com/apache/hudi) ⭐ 6,281 | 🐛 2,969 | 🌐 Java | 📅 2026-10-06 - Manages the storage of large analytical datasets on DFS.

## Data Visualization

*Tools for performing data visualization (DataViz).*

* [Apache Superset](https://github.com/apache/superset) ⭐ 75,052 | 🐛 566 | 🌐 Python | 📅 2026-10-06 - A modern data exploration and data visualization platform.
* [Dash](https://github.com/plotly/dash) ⭐ 24,442 | 🐛 438 | 🌐 Python | 📅 2026-10-05 - Analytical Web Apps for Python, R, Julia, and Jupyter.
* [Lux](https://github.com/lux-org/lux) ⭐ 5,380 | 🐛 90 | 🌐 Python | 📅 2024-03-20 - Fast and easy data exploration by automating the visualization and data analysis process.
* [HUE](https://github.com/cloudera/hue) ⭐ 1,406 | 🐛 29 | 🌐 JavaScript | 📅 2026-10-06 - A mature SQL Assistant for querying Databases & Data Warehouses.
* [Count](https://count.co) - SQL/drag-and-drop querying and visualisation tool based on notebooks.
* [Data Studio](https://datastudio.google.com) - Reporting solution for power users who want to go beyond the data and dashboards of GA.
* [Metabase](https://www.metabase.com/) - The simplest, fastest way to get business intelligence and analytics to everyone.
* [Redash](https://redash.io/) - Connect to any data source, easily visualize, dashboard and share your data.
* [Tableau](https://www.tableau.com) - Powerful and fastest growing data visualization tool used in the business intelligence industry.

## Data Warehouse

*Tools related to storing data in data warehouses (DW).*

* [Apache Hive](https://github.com/apache/hive) ⭐ 6,028 | 🐛 132 | 🌐 Java | 📅 2026-10-06 - Facilitates reading, writing, and managing large datasets residing in distributed storage.
* [Apache Kylin](https://github.com/apache/kylin) ⭐ 3,775 | 🐛 79 | 🌐 Java | 📅 2026-10-06 - An open source, distributed analytical data warehouse for big data.
* [Amazon Redshift](https://aws.amazon.com/redshift/) - Accelerate your time to insights with fast, easy, and secure cloud data warehousing.
* [Google BigQuery](https://cloud.google.com/bigquery) - Serverless, highly scalable, and cost-effective multicloud data warehouse.

## Database

*Database tools for storing data.*

### Columnar Database

* [Scylla](https://github.com/scylladb/scylla) ⭐ 15,782 | 🐛 3,779 | 🌐 C++ | 📅 2026-10-06 - Designed to be compatible with Cassandra while achieving higher throughputs and lower latencies.
* [Apache Druid](https://github.com/apache/druid) ⭐ 14,059 | 🐛 772 | 🌐 Java | 📅 2026-10-06 - Designed to quickly ingest massive quantities of event data, and provide low-latency queries.
* [Apache Cassandra](https://github.com/apache/cassandra) ⭐ 10,114 | 🐛 547 | 🌐 Java | 📅 2026-10-05 - Open source column based DBMS designed to handle large amounts of data.
* [Apache HBase](https://github.com/apache/hbase) ⭐ 5,560 | 🐛 414 | 🌐 Java | 📅 2026-10-05 - An open-source, distributed, versioned, column-oriented store.

### Document-Oriented Database

* [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 78,196 | 🐛 6,144 | 🌐 Java | 📅 2026-10-06 - A distributed document oriented database with a RESTful search engine.
* [MongoDB](https://github.com/mongodb/mongo) ⭐ 28,617 | 🐛 36 | 🌐 C++ | 📅 2026-10-06 - A cross-platform document database that uses JSON-like documents with optional schemas.
* [RethinkDB](https://github.com/rethinkdb/rethinkdb) ⭐ 27,007 | 🐛 1,352 | 🌐 C++ | 📅 2026-03-28 - The first open-source scalable database built for realtime applications.
* [Apache CouchDB](https://github.com/apache/couchdb) ⭐ 6,969 | 🐛 377 | 🌐 Erlang | 📅 2026-10-06 - An open-source document-oriented NoSQL database, implemented in Erlang.

### Graph Database

* [Neo4j](https://github.com/neo4j/neo4j) ⭐ 17,278 | 🐛 230 | 🌐 Java | 📅 2026-09-22 - A high performance graph store with all the features expected of a mature and robust database.
* [ArangoDB](https://github.com/arangodb/arangodb) ⭐ 14,278 | 🐛 875 | 🌐 C++ | 📅 2026-10-06 - A scalable open-source multi-model database natively supporting graph, document and search.
* [JanusGraph](https://github.com/JanusGraph/janusgraph) ⭐ 5,843 | 🐛 609 | 🌐 Java | 📅 2026-10-05 - Manage large graphs with billions of data distributed across a multi-machine cluster.
* [Titan](https://github.com/thinkaurelius/titan) ⭐ 5,228 | 🐛 181 | 🌐 Java | 📅 2022-10-19 - A highly scalable graph database optimized for storing and querying large graphs.
* [Age](https://github.com/apache/age) ⭐ 4,874 | 🐛 264 | 🌐 C | 📅 2026-09-19 - A multi-model database that supports both graph and relational data models.
* [Memgraph](https://github.com/memgraph/memgraph) ⭐ 4,597 | 🐛 799 | 🌐 C++ | 📅 2026-10-06 - An open source graph database, built for real-time streaming data, compatible with Neo4j.

### Key-Value Database

* [Redis](https://github.com/redis/redis) ⭐ 76,614 | 🐛 3,002 | 🌐 C | 📅 2026-09-30 - An in-memory key-value database that persists on disk.
* [etcd](https://github.com/etcd-io/etcd) ⭐ 52,332 | 🐛 383 | 🌐 Go | 📅 2026-10-05 - Distributed reliable key-value store for the most critical data of a distributed system.
* [Dragonfly](https://github.com/dragonflydb/dragonfly) ⭐ 31,748 | 🐛 325 | 🌐 C++ | 📅 2026-10-06 - A modern in-memory datastore, fully compatible with Redis and Memcached APIs.
* [Memcached](https://github.com/memcached/memcached) ⭐ 14,290 | 🐛 110 | 🌐 C | 📅 2026-09-11 - A high performance multithreaded event-based key/value cache store.
* [EVCache](https://github.com/Netflix/EVCache) ⭐ 2,224 | 🐛 20 | 🌐 Java | 📅 2026-10-02 - A distributed in-memory data store for the cloud.
* [Apache Accumulo](https://github.com/apache/accumulo) ⭐ 1,173 | 🐛 342 | 🌐 Java | 📅 2026-10-05 - A sorted, distributed key-value store that provides robust and scalable data storage.
* [DynamoDB](https://aws.amazon.com/dynamodb/) - Fast, flexible NoSQL database service for single-digit millisecond performance at any scale.

### Relational Database

* [CockroachDB](https://github.com/cockroachdb/cockroach) ⭐ 32,552 | 🐛 8,380 | 🌐 Go | 📅 2026-10-03 - A distributed database designed to build, scale, and manage data-intensive apps.
* [PostgreSQL](https://github.com/postgres/postgres) ⭐ 22,296 | 🐛 0 | 🌐 C | 📅 2026-10-06 - An advanced RDBMS that supports an extended subset of the SQL standard.
* [RQLite](https://github.com/rqlite/rqlite) ⭐ 17,784 | 🐛 76 | 🌐 Go | 📅 2026-10-06 - A lightweight, distributed relational database, which uses SQLite as its storage engine.
* [MySQL](https://github.com/mysql/mysql-server) ⭐ 12,440 | 🐛 96 | 🌐 C++ | 📅 2026-09-29 - One of the most popular open source transactional databases.
* [SQLite](https://github.com/sqlite/sqlite) ⭐ 10,606 | 🐛 24 | 🌐 C | 📅 2026-10-06 - A popular choice as embedded database software for local/client storage.
* [MariaDB](https://github.com/MariaDB/server) ⭐ 8,321 | 🐛 535 | 🌐 C++ | 📅 2026-10-06 - A replacement of MySQL with more features, new storage engines and better performance.
* [Crate](https://github.com/crate/crate) ⭐ 4,443 | 🐛 333 | 🌐 Java | 📅 2026-10-06 - A distributed SQL database that makes it simple to store and analyze massive amounts of data.

### Time Series Database

* [InfluxDB](https://github.com/influxdata/influxdb) ⭐ 31,760 | 🐛 2,171 | 🌐 Rust | 📅 2026-10-05 - Scalable datastore for metrics, events, and real-time analytics.
* [TimescaleDB](https://github.com/timescale/timescaledb) ⭐ 23,648 | 🐛 425 | 🌐 C | 📅 2026-10-06 - Open-source time-series SQL database optimized for fast ingest and complex queries.
* [QuestDB](https://github.com/questdb/questdb) ⭐ 17,426 | 🐛 1,042 | 🌐 Java | 📅 2026-10-06 - An open source SQL database designed to process time series data, faster.
* [Atlas](https://github.com/Netflix/Atlas) ⭐ 3,571 | 🐛 9 | 🌐 Scala | 📅 2026-10-01 - An in-memory dimensional time series database.
* [Akumuli](https://github.com/akumuli/Akumuli) ⚠️ Archived - Can be used to capture, store and process time-series data in real-time.

### Vector Database

* [Milvus](https://github.com/milvus-io/milvus/) ⭐ 46,325 | 🐛 1,392 | 🌐 Go | 📅 2026-10-05 - An open source embedding vector similarity search engine powered by Faiss, NMSLIB and Annoy.
* [Qdrant](https://github.com/qdrant/qdrant) ⭐ 34,944 | 🐛 747 | 🌐 Rust | 📅 2026-10-06 - An open source vector similarity search engine with extended filtering support.
* [Pinecone](https://www.pinecone.io) - Managed and distributed vector similarity search used with a lightweight SDK.

## File System

*Tools related to file system and data storage.*

* [MinIO](https://github.com/minio/minio) ⚠️ Archived - High Performance, Kubernetes Native Object Storage compatible with Amazon S3 API.
* [Alluxio](https://github.com/Alluxio/alluxio) ⭐ 7,247 | 🐛 1,048 | 🌐 Java | 📅 2026-09-01 - A virtual distributed storage system.
* [LakeFS](https://github.com/treeverse/lakeFS) ⭐ 5,551 | 🐛 444 | 🌐 Go | 📅 2026-10-01 - Open source tool that transforms your object storage into a Git-like repository.
* [GlusterFS](https://github.com/gluster/glusterfs) ⭐ 5,254 | 🐛 326 | 🌐 C | 📅 2026-09-23 - A software defined distributed storage that can scale to several petabytes.
* [Swift](https://github.com/openstack/swift) ⭐ 2,803 | 🐛 0 | 🌐 Python | 📅 2026-10-06 - A distributed object storage system designed to scale from a single machine to thousands of servers.
* [LizardFS](https://github.com/lizardfs/lizardfs) ⭐ 995 | 🐛 325 | 🌐 C++ | 📅 2024-08-11 - A highly reliable, scalable and efficient distributed file system.
* [SeaweedFS](https://github.com/chrislusf/seaweedfs) ⭐ 41 | 🐛 1 | 🌐 Go | 📅 2026-10-06 - A fast distributed storage system for blobs, objects, files, and data lake.
* [Amazon Simple Storage Service (S3)](https://aws.amazon.com/s3/) - Object storage built to retrieve any amount of data from anywhere.
* [Apache Hadoop Distributed File System (HDFS)](https://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html) - A distributed file system.
* [Google Cloud Storage (GCS)](https://cloud.google.com/storage) - Object storage for companies of all sizes, to store any amount of data.

## Logging and Monitoring

*Tools used for logging and monitoring data workflows.*

* [Grafana](https://github.com/grafana/grafana) ⭐ 77,101 | 🐛 3,303 | 🌐 TypeScript | 📅 2026-10-06 - Visualize metrics, logs, and traces from multiple sources like Prometheus, Loki, InfluxDB and more.
* [Prometheus](https://github.com/prometheus/prometheus) ⭐ 66,386 | 🐛 968 | 🌐 Go | 📅 2026-10-06 - A monitoring system and time series database.
* [Loki](https://github.com/grafana/loki) ⭐ 28,990 | 🐛 1,037 | 🌐 Go | 📅 2026-10-06 - A horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus.
* [Whylogs](https://github.com/whylabs/whylogs) ⭐ 2,835 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2025-01-10 - A tool for creating data logs, enabling monitoring for data drift and data quality issues.

## Metadata Service

*Tools used for storing and serving metadata.*

* [Hive Metastore](https://cwiki.apache.org/confluence/display/hive/design#Design-Metastore) - Service that stores metadata related to Apache Hive and other services.
* [Metacat](https://github.com/Netflix/metacat) ⭐ 1,691 | 🐛 58 | 🌐 Java | 📅 2026-10-01 - Provides you information about what data you have, where it resides and how to process it.

## SQL Playground

*Tools for testing and sharing SQL snippets in mock databases.*

* [RunSQL](https://runsql.com/) - Free online SQL playground for MySQL, PostgreSQL, and SQL Server.
* [SQLFiddle](https://sqlfiddle.com/) - Online SQL compiler for learning and practicing SQL.

## SQL Query Engine

*Tools for parallel processing SQL statements.*

* [Presto](https://github.com/prestodb/presto) ⭐ 16,753 | 🐛 2,998 | 🌐 Java | 📅 2026-10-06 - A distributed SQL query engine for big data.
* [Trino](https://github.com/trinodb/trino) ⭐ 13,305 | 🐛 2,739 | 🌐 Java | 📅 2026-10-06 - A fast distributed SQL query engine for big data analytics.
* [Apache Drill](https://github.com/apache/drill) ⭐ 2,024 | 🐛 129 | 🌐 Java | 📅 2026-10-05 - Schema-free SQL Query Engine for Hadoop, NoSQL and Cloud Storage.
* [Apache Impala](https://github.com/apache/impala) ⭐ 1,290 | 🐛 8 | 🌐 C++ | 📅 2026-10-06 - Lightning-fast, distributed SQL queries for petabytes of data.
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

* [Awesome Data Engineering](https://github.com/igorbarinov/awesome-data-engineering) ⭐ 9,143 | 🐛 44 | 📅 2026-09-07
* [Awesome MLOps](https://github.com/kelvins/awesome-mlops) ⭐ 5,284 | 🐛 99 | 🌐 Python | 📅 2026-08-17
* [DataOps Resource](https://github.com/chen1649chenli/dataOpsResource) ⭐ 24 | 🐛 2 | 📅 2020-08-14

## Slack

* [Delta Lake Workspace](https://delta-users.slack.com/ssb/redirect)
* [Trino Workspace](https://trinodb.slack.com/ssb/redirect)

***

# Contributing

All contributions are welcome! Please take a look at the [contribution guidelines](https://github.com/kelvins/awesome-dataops/blob/main/CONTRIBUTING.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-06._
