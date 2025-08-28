# Aleksandra Belousova | Data & Bioinformatics Engineer

### Technical Skill Matrix

| Category | Technologies |
|---|---|
| **Languages** | Python, C++, Java, R, SQL |
| **Databases & Search** | ClickHouse, Elasticsearch, PostgreSQL, SQLite |
| **Infrastructure & MLOps**| Docker, Docker Compose, Prefect, FastAPI, AWS (S3), HashiCorp Vault |
| **HPC & Specialized Libraries** | OpenMP, htslib, Pandas, NumPy, Scikit-learn, Dask, SciPy, Biopython |

---

### Key Projects

| Project | System Architecture | Key Result / Metric | Tech Stack |
|---|---|---|---|
|  **[GenoStream Analytics](https://github.com/AleksandraBelousova/genostream-analytics)** | OLAP system for large-scale (174M+ records) scRNA-seq analysis. | **Query time reduction from hours to <2s** for complex aggregations. | `ClickHouse`, `Python`, `Docker`, `Pandas`, `SciPy` |
|  **[ChromoSeek Engine](https://github.com/AleksandraBelousova/chromoseek-engine)** | Service-oriented search engine for genomic interval analysis, utilizing BKD-tree indexing. | **<200ms latency** on complex spatial (`integer_range`) queries. | `Elasticsearch`, `FastAPI`, `Prefect`, `Docker` |
|  **[BAMalyzer Toolkit](https://github.com/AleksandraBelousova/bamalyzer)** | Multi-threaded QC utility for genomic alignment analysis with low-level I/O. | High-throughput, parallelized BAM file processing, addressing Python performance bottlenecks. | `C++`, `OpenMP`, `htslib`, `CMake` |
|  **[BioAssure Validator](https://github.com/AleksandraBelousova/genearchive-validator)** | CLI for automated, multi-layer data integrity validation of genomic data packages. | Ensures structural, syntactic, and biological consistency prior to data ingestion. | `Java`, `Picocli`, `Jackson`, `Maven` |
