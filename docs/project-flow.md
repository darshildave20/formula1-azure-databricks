# Project Flow

The project follows the Medallion Architecture to transform raw Formula 1 datasets into business-ready analytical data.

## Pipeline Flow

```text
CSV / JSON Files
        │
        ▼
Azure Data Lake Storage Gen2
        │
        ▼
Bronze Layer
(Raw Delta Tables)
        │
        ▼
Silver Layer
(Cleaned & Standardized Data)
        │
        ▼
Gold Layer
(Business Ready Data)
        │
        ▼
Analytics & Reporting
```

---

## Bronze Layer

Responsibilities:

- Read raw source files
- Apply predefined schemas
- Handle multiline JSON
- Add ingestion timestamps
- Store data in Delta Lake

---

## Silver Layer

Responsibilities:

- Data cleansing
- Data standardization
- Business transformations
- Column renaming
- Derived columns
- Incremental processing

---

## Gold Layer

Responsibilities:

- Driver Standings
- Constructor Standings
- Race Results
- Business-ready datasets
