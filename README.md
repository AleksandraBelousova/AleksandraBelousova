### Skills
|---|---|
| Python, C++, Java, SQL |
| **DB & DWH** | ClickHouse, PostgreSQL, Elasticsearch, SQLite |
| **Streaming & CDC** | Apache Kafka, Redpanda, Debezium, Confluent Schema Registry, Avro |
| **DE** | dbt (dbt-core, dbt-clickhouse), Apache Airflow, Prefect |
| Docker, Docker Compose, Kubernetes (Manifests), FastAPI, AWS (S3), HashiCorp Vault |
| **HPC & Specialized Lib** | OpenMP, htslib, Pandas, NumPy, Scikit-learn, Dask, SciPy, Biopython |

---

### Projects

| Project | System Architecture | Key Result / Metric | Tech Stack |
| :--- | :--- | :--- | :--- |
| **[PostgreSQL to ClickHouse CDC Pipeline](https://github.com/AleksandraBelousova/clinicalsync-realtime-cdc-dwh)** | Heterogeneous DB replication (PostgreSQL WAL → Debezium → Avro / Schema Registry → Kafka → ClickHouse) with dbt data quality gates. | **Sub-second replication latency** with 100% schema evolution resilience and 15 automated data quality tests. | `Debezium` `Kafka` `Avro` `Schema Registry` `ClickHouse` `dbt` `Airflow` |
| **[PostgreSQL ETL Pipeline with HashiCorp Vault](https://github.com/AleksandraBelousova/PostgreSQL-ETL-Pipeline-with-HashiCorp-Vault)** | Secure, containerised system for ingesting, storing, and analysing data, leveraging network-isolated PostgreSQL and HashiCorp Vault for runtime secrets management. | **Production-ready secret isolation** with automated two-step initialisation and zero hardcoded credentials. | `PostgreSQL` `HashiCorp Vault` `Python` `Pandas` `Docker` |
| **[C++ Parallel File Parser](https://github.com/AleksandraBelousova/Parallel-File-Parser)** | Multi-threaded QC utility for genomic alignment analysis with low-level I/O. | High-throughput, parallelized BAM file processing, addressing Python performance bottlenecks. | `C++` `OpenMP` `htslib` `CMake` |
| **[Elasticsearch Interval Search API](https://github.com/AleksandraBelousova/Elasticsearch-Interval-Search-API)** | Service-oriented search engine for genomic interval analysis, utilizing BKD-tree indexing. | **<200ms latency** on complex spatial ( integer_range ) queries. | `Elasticsearch` `FastAPI` `Prefect` `Docker` |
| **[BioAssure Validator](https://github.com/AleksandraBelousova/BioAssure)** | A command-line gatekeeper for genomic data, ensuring integrity and biological consistency in bio-pipelines. Its configurable, stream-based engine validates DNA-to-protein translation, yielding JSON reports and exit codes for CI/CD integration. | Efficiently handles large-scale FASTA and JSONL files. | `Java` `Picocli` `Jackson` `Maven` |
