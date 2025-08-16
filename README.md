# PySpark Retail Analytics Project

- Ingest raw CSV → curated analytics **tables (Parquet)**
- Explicit schema + partitioning by `order_date` for efficient reads
- Daily KPIs & **window functions** (Top-N SKUs per country)
- **RFM** features (Recency / Frequency / Monetary)
- **KMeans** customer clustering (MLlib) + cluster profiling
- Tiny **7-day revenue forecast** (baseline: trend + day-of-week)
- Clean shutdown; optional exports for BI (Parquet/CSV)
