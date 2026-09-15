# Automated Fraud Reporting & Data Consolidation Pipeline

### 📌 Project Context
In top-tier retail digital banking, risk data is often fragmented across multiple legacy processing cores and digital wallet systems. Manual consolidation via Excel causes operational delays and delays high-risk security reporting to executive boards.

This project delivers an automated ETL and fraud-parsing data pipeline built using Python (Pandas) to replace manual reporting workflows.

### 🛠️ Tech Stack
- **Python** (Pandas, NumPy)
- **Concepts:** Data Consolidation, Multi-source Concatenation, Rule-based Risk Flagging.

### 📊 Business Logic
The pipeline automatically aggregates raw data feeds, matches transaction flows, and instantly flags high-risk behavioral anomalies:
- Filters specific **MCC codes** associated with extreme risk (e.g., MCC 7995 - Gambling/Casino).
- Checks velocity thresholds (Volumes over $10,000).
- Compiles a summary metric matrix ready for Top Management BI systems.

### 📈 Business Impact
Replacing manual spreadsheet parsing with this automated Python object-oriented script secured a **20% acceleration in data delivery and executive reporting speed**, minimizing financial exposure windows.
