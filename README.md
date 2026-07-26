### Technical Skills

| Category | Technologies |
|---|---|
| **Languages** | Python, C++, Java, SQL |
| **Databases & DWH** | ClickHouse, PostgreSQL, Elasticsearch, SQLite |
| **Streaming & CDC** | Apache Kafka, Redpanda, Debezium, Confluent Schema Registry, Avro |
| **Data Engineering & Orchestration** | dbt (dbt-core, dbt-clickhouse), Apache Airflow, Prefect |
| **Infrastructure & Cloud** | Docker, Docker Compose, Kubernetes (Manifests), FastAPI, AWS (S3), HashiCorp Vault |
| **HPC & Specialized Libraries** | OpenMP, htslib, Pandas, NumPy, Scikit-learn, Dask, SciPy, Biopython |

---

### Projects

| Project | System Architecture | Key Result / Metric | Tech Stack |
|---|---|---|---|
| **[PostgreSQL to ClickHouse CDC Pipeline](https://github.com/AleksandraBelousova/clinicalsync-realtime-cdc-dwh)** | Real-time CDC integration pipeline with Avro serialization and Schema Registry for heterogeneous DB replication. | **Sub-second replication latency** with 100% schema evolution resilience and 15 automated data quality tests. | `PostgreSQL`, `Debezium`, `Kafka`, `Avro`, `ClickHouse`, `dbt`, `Airflow` |
| **[Kafka Stream Processor with DLQ](https://github.com/AleksandraBelousova/claimstream-dental)** | Event-driven streaming platform with Dead Letter Queue (DLQ) routing, Pydantic schema validation, and idempotent storage. | **At-Least-Once delivery guarantees** with zero data loss under simulated node failures. | `Redpanda`, `Kafka`, `ClickHouse`, `Python`, `Pydantic`, `Prometheus` |
| **[ClickHouse OLAP Engine (174M+ Records)](https://github.com/AleksandraBelousova/genostream-analytics-platform)** | OLAP system for large-scale (174M+ records) scRNA-seq analysis. | **Query time reduction from hours to <2s** for complex aggregations. | `ClickHouse`, `Python`, `Docker`, `Pandas`, `SciPy` |
| **[Elasticsearch Interval Search API](https://github.com/AleksandraBelousova/chromoseek-engine)** | Service-oriented search engine for genomic interval analysis, utilizing BKD-tree indexing. | **<200ms latency** on complex spatial (`integer_range`) queries. | `Elasticsearch`, `FastAPI`, `Prefect`, `Docker` |
| **[C++ Parallel File Parser](https://github.com/AleksandraBelousova/BAMalyzer)** | Multi-threaded QC utility for genomic alignment analysis with low-level I/O. | High-throughput, parallelized BAM file processing, addressing Python performance bottlenecks. | `C++`, `OpenMP`, `htslib`, `CMake` |
| **[Java Data Integrity Validator](https://github.com/AleksandraBelousova/BioAssure)** | CLI for automated, multi-layer data integrity validation of genomic data packages. | Ensures structural, syntactic, and biological consistency prior to data ingestion. | `Java`, `Picocli`, `Jackson`, `Maven` |
