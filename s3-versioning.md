## 1. 📖 **S3 Cloud Lab Overview**
Gain hands‑on experience with S3 bucket configuration, versioning behavior, object lifecycle transitions, and operational workflows for managing data durability and recovery in cloud environments.

## 2. 🌩️ **Skill Building — S3 Versioning**
* Work with S3 versioning states — **Unversioned Object**, **Versioning-Enabled**, and **Versioning-Suspended**  
* Use S3 commands to upload, copy, remove, list versions, and restore objects  
* Review version history and see how delete markers affect object visibility  
* Roll back to earlier versions to understand recovery behavior  
* Apply lifecycle rules to control storage growth and automate version cleanup

## 3. 🛰️ **AWS Resources & Services**
* S3
 
## 4. 📟 **Metrics & Behaviors Triggered by Versioning**
* **ObjectCount** — increases as new versions accumulate  
* **BucketSizeBytes** — grows with each version and delete marker  
* **DeleteMarkers** — created when objects are deleted while versioning is enabled  
* **LifecycleTransitions** — triggered when older versions move to Glacier or other storage classes  
* **VersionRestores** — observed when retrieving or copying older object versions  

## 6. 👀 **Behaviors Observed**
* Multiple versions created as objects were overwritten  
* Delete markers appeared when objects were removed  
* Bucket size increased due to retained historical versions  
* Older versions remained recoverable even after deletion  
* Lifecycle rules (if configured) transitioned older versions to lower‑cost storage  
* S3 maintained full durability and availability throughout all operations  

## 7. 👁️ **Observations & Next Actions**
### 🏢 *Workplace Applications*
* Review versioning behavior with team or customer  
* Validate whether versioning aligns with compliance, backup, lifecycle or recovery requirements  
* Evaluate storage growth and cost impact from retained versions

### 🧙🏽 *Ongoing Development*
* Plan additional scenarios such as MFA Delete, cross‑region replication, or lifecycle expiration  
* Simulate real‑world workflows like accidental deletion recovery or rollback to previous versions  
* Expand the lab to include S3 event notifications, Lambda automation, or Glacier archival strategies
* Add Cross-Region Replication (CRR) and Same-Region Replication (SRR) for live replication
