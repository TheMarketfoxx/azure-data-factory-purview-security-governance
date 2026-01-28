
---

## Services & Technologies (ATS Keywords)

- Azure Data Factory  
- Azure Data Lake Storage Gen2  
- Microsoft Purview  
- Data governance & classification  
- Data lineage  
- Security telemetry  
- Cloud data pipelines  
- Compliance & audit readiness  

---

## Dataset

The dataset represents **simulated security telemetry** such as:
- Authentication events
- MFA activity
- Privileged actions
- Device activity indicators

These fields are intentionally included to trigger **Purview discovery and classification**:
- User identifiers
- IP addresses
- Locations
- Device names
- Event outcomes

All data is synthetic and safe for public sharing.

---

## Implementation Summary

### Azure Data Factory
- Built ingestion pipelines to copy security telemetry into Azure Data Lake
- Organized data into raw and curated storage zones
- Executed and monitored pipeline runs

### Microsoft Purview
- Registered Azure Data Lake as a data source
- Performed scans for automated discovery
- Reviewed schema, classifications, and asset metadata
- Evaluated governance visibility for sensitive data elements

### Governance Focus
- Identity-related fields
- Network indicators
- Auditability and lineage awareness
- Separation of raw vs curated access patterns

---

## Evidence & Screenshots

Screenshots are included to demonstrate:
- Azure Data Factory pipeline design and successful runs
- Data Lake folder structure
- Purview scans and discovered assets
- Classification and lineage visibility

See the `screenshots/` directory.

---

## Resume-Ready Highlights

- Built a security telemetry ingestion pipeline using **Azure Data Factory**
- Governed cloud data assets with **Microsoft Purview**, enabling discovery, classification, and lineage
- Demonstrated data governance concepts supporting **security analytics and compliance**
- Applied Microsoft-native data services aligned with enterprise security workflows

---

## Notes

- This project focuses on **governance and data movement**, not exploitation or offensive security
- Architecture aligns with Microsoft-recommended cloud data patterns
- Designed to be evaluated by recruiters and hiring managers

