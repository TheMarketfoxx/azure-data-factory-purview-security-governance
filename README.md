
---

## Services & Technologies

- Azure Data Factory  
- Azure Data Lake Storage Gen2  
- Microsoft Purview  
- Data governance & classification  
- Data lineage  
- Security telemetry  
- Cloud data pipelines  
- Compliance & audit readiness  

## Intended Deployment Flow

1. Azure Data Factory pipelines ingest security telemetry into raw storage zones.
2. Data is organized into curated zones for analytics consumption.
3. Microsoft Purview registers the data lake and performs automated scans.
4. Sensitive identity and network fields are classified for governance visibility.
5. Lineage supports audit and compliance workflows.

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


This project was developed under limited Azure tenant access.

Due to subscription and tenant restrictions, live execution of Azure Data Factory pipelines and Microsoft Purview scans was not available at the time of documentation. The project therefore focuses on:

- Accurate pipeline and governance design
- Correct service configuration and architecture
- Data governance and lineage planning aligned with Microsoft best practices

All implementation artifacts are structured to be deployable immediately once tenant access is granted.
