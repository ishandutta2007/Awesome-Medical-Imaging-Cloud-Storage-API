# Awesome-Medical-Imaging-Cloud-Storage-API

# Top Medical Imaging Cloud Storage & API Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on DICOM Storage, Medical Imaging APIs & Self-Hosted PACS*  
**Last updated: October 2026**

This repository tracks notable **commercial medical imaging cloud platforms** and **open-source projects** that store, manage, and exchange DICOM imaging data — from cloud-native PACS to open-source DICOM servers and viewers.

**Examples** include AWS HealthImaging, Google Cloud Medical Imaging Suite, Azure Health Data Services DICOM, Intelerad Ambra Health, Aidoc, Arterys, Flywheel, Sectra Cloud, RamSoft OmegaAI, and Enlitic (the category leaders).

**Open-source emphasis**: Medical imaging is a strong open-source domain. **Orthanc** leads as the lightweight, extensible DICOM server recognized as a Digital Public Good. **dcm4chee** provides enterprise-grade PACS, **OHIF** delivers the leading zero-footprint viewer, and **DCMTK**/**pydicom** handle DICOM file processing. **Dicoogle** offers research-focused indexing, while **Stone Web Viewer** provides bandwidth-efficient web viewing. **DICOMcloud** and **dicomweb-proxy** bridge DICOMweb and DIMSE protocols. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AWS HealthImaging](https://aws.amazon.com/healthimaging/)**  
  **AWS's HIPAA-eligible medical imaging service** — store, analyze, and share PB-scale imaging data in the cloud . **Industry-leading performance** with HTJ2K encoding, SIMD-accelerated decoding, and progressive resolution access . **DICOMweb conformant APIs** with cloud-native extensions for metadata updates . **Automatically organizes DICOM data** by Patient, Study, and Series levels . **Built-in pixel data verification** for lossless encoding . **Best for enterprise imaging archives and AI/ML development** .

- **[Google Cloud Medical Imaging Suite](https://cloud.google.com/medical-imaging)**  
  **Google's comprehensive imaging platform** — Imaging Storage (Cloud Healthcare API), Imaging Lab (AI-assisted annotation), Imaging Datasets & Dashboards (BigQuery, Looker), and Imaging AI Pipelines (Vertex AI) . **Automated DICOM de-identification** built-in . **Flexible deployment** on cloud, on-prem, or edge with Google Distributed Cloud . **Used by Hackensack Meridian Health and Hologic** . **Best for AI development on imaging data** .

- **[Azure Health Data Services DICOM](https://azure.microsoft.com/en-us/products/health-data-services/)**  
  **Microsoft's cloud DICOM service** — store, manage, and exchange imaging data with any DICOMweb-enabled system . **Global availability, PHI compliance, PB-scale scalability, automatic data replication, and RBAC** . **Deploys alongside FHIR service in the same workspace** for multimodal health data analysis . **Best for Microsoft-centric healthcare organizations** .

- **[Intelerad Ambra Health](https://www.intelerad.com/)**  
  **Cloud-based enterprise image exchange** — 100% of studies successfully uploaded in 12-month comparison . **Automated routing rules** for study sharing across organizations . **Zero-footprint HTML5 viewer** (FDA 510(k) cleared) . **Best for enterprise image exchange** .

- **[Aidoc](https://www.aidoc.com/)**  
  **Clinical AI platform with 17 FDA-cleared algorithms** — analyzes 1.3M+ scans annually across 13 hospitals . **Foundation model approach** for comprehensive abdominal coverage . **Best for scaled clinical AI deployment** .

- **[Arterys](https://www.arterys.com/)**  
  **Cloud-based AI imaging platform** (acquired by Tempus AI) — first FDA clearance for machine learning in clinical setting . **Stroke Suite** for LVO and ICH detection with 95.6% accuracy . **Zero-footprint diagnostic web viewer** with multi-GPU rendering . **Best for stroke and cardiac AI** .

- **[Flywheel](https://flywheel.io/)**  
  **Imaging data activation platform** — partners with AWS HealthImaging for enterprise golden data lake . **Automated de-identification, QC, and normalization** at ingestion . **21 CFR Part 11 and HIPAA compliant** . **Best for clinical trials and AI development** .

- **[Sectra Cloud](https://medical.sectra.com/)**  
  **Cloud-based PACS and enterprise imaging** — Sectra One Cloud for SaaS deployment . **Best for large healthcare networks** .

- **[RamSoft OmegaAI](https://www.ramsoft.com/)**  
  **Cloud-native RIS/PACS/VNA** — built entirely on Microsoft Azure with 99.95% uptime . **Zero footprint, no local installation** . **AI-powered reporting with voice dictation** . **Best for cloud-native imaging** .

- **[Enlitic](https://www.enlitic.com/)**  
  **AI radiology workflow optimization** — Ensight platform for hanging protocol standardization . **Deployed at RHCNZ New Zealand across 65+ clinics** . **Integrates with Intelerad IntelePACS** . **Best for workflow standardization** .

## Open-Source GitHub Projects

### DICOM Servers & PACS

- **[Orthanc](https://github.com/jodogne/Orthanc)**  
  **The leading lightweight open-source DICOM server**, GPL-3.0 licensed . **Single executable with no external dependencies** — runs out-of-the-box on all major OS including commodity hardware . **RESTful API** wrapping DICOM functionality for easy integration . **Plugin architecture** for database backends, web viewers, DICOMweb support, and whole-slide imaging . **Recognized as a Digital Public Good** . **Used worldwide as lightweight PACS, middleware for image exchange, teleradiology substrate, and AI pipeline platform** . **Multi-tenant DICOM plugin** enables isolated views per tenant via labels . **Best for self-hosted DICOM storage and workflows** .

- **[dcm4chee](https://github.com/dcm4che/dcm4chee-arc-light)**  
  **Enterprise-grade open-source PACS**, MPL-1.1 licensed . **DICOM archive with storage, retrieval, and workflow services** . **Docker deployment available** . **Integrates with OHIF viewer** . **Best for enterprise DICOM archiving** .

- **[Dicoogle](https://github.com/bioinformatics-ua/dicoogle)**  
  **Open-source PACS with indexing and research focus**, GPL-3.0 licensed . **NoSQL-based medical image archive** . **Extensible plugin architecture** . **Best for research and AI pipelines** .

- **[DICOMcloud](https://github.com/DICOMcloud/DICOMcloud)**  
  **Azure-friendly DICOMweb server**, open-source . **Full QIDO-RS, WADO-RS, STOW-RS, and WADO-URI RESTful implementation** . **.NET-based** . **Best for DICOMweb on Azure** .

- **[dicomweb-proxy](https://github.com/knopkem/dicomweb-proxy)**  
  **Proxy translating between DICOMweb and traditional DICOM DIMSE**, open-source . **Bridges modern web APIs and legacy PACS** . **TypeScript-based** . **Best for DICOMweb-DIMSE integration** .

- **[raccoon-dicom](https://github.com/Chinlinlee/raccoon-dicom)**  
  **NoSQL-based medical image archive (miniPACS)**, open-source . **MongoDB-backed for scalability** . **JavaScript-based** . **Best for lightweight PACS** .

### Viewers & Web Tools

- **[OHIF Viewer](https://github.com/OHIF/Viewers)**  
  **The leading open-source zero-footprint DICOM viewer**, MIT licensed with **4,300+ GitHub stars** . **Extensible platform supporting DICOMweb and DICOM JSON** . **Oncology tools, segmentation, and measurement** . **Integrates with Orthanc, DCM4CHEE, and Google Cloud Healthcare API** . **The de facto standard for web-based medical imaging** . **Best for browser-based DICOM viewing** .

- **[Stone Web Viewer](https://github.com/jodogne/OrthancStone)**  
  **Bandwidth-efficient web viewer built on WebAssembly**, GPL-3.0 licensed . **Companion to Orthanc** . **Best for web-based viewing with Orthanc** .

- **[DICOMweb-js](https://github.com/DICOMcloud/DICOMweb-js)**  
  **JavaScript client for DICOM Web Services**, open-source . **QIDO-RS, WADO-RS, WADO-URI, STOW-RS support** . **Viewer demo included** . **Best for DICOMweb client development** .

### DICOM Libraries & Tools

- **[DCMTK](https://github.com/DCMTK/dcmtk)**  
  **The foundational DICOM toolkit**, BSD-3-Clause licensed . **DICOM file handling and networking** . **The reference implementation for DICOM** . **Best for DICOM development** .

- **[pydicom](https://github.com/pydicom/pydicom)**  
  **Python library for DICOM file handling**, MIT licensed . **Read, write, and modify DICOM files** . **Best for Python DICOM processing** .

- **[GDCM](https://github.com/malaterre/GDCM)**  
  **Grassroots DICOM library**, BSD-3-Clause licensed . **C++ library for DICOM reading/writing** . **Best for C++ DICOM development** .

- **[dcm4che](https://github.com/dcm4che/dcm4che)**  
  **Java DICOM toolkit**, MPL-1.1 licensed . **The foundation for dcm4chee** . **Best for Java DICOM development** .

- **[VTK](https://github.com/Kitware/VTK)**  
  **Visualization Toolkit with DICOM support**, BSD-3-Clause licensed . **3D visualization and image processing** . **Best for medical image visualization** .

### Additional Strong Open-Source Options

- **3D Slicer** — Medical image visualization and analysis platform .
- **Horos** — macOS DICOM viewer (1M+ users globally) .
- **Weasis** — Cross-platform DICOM viewer .
- **OHIF Viewer** — Web-based DICOM viewer .
- **Cornerstone.js** — JavaScript medical imaging libraries .
- **dcmjs** — JavaScript DICOM manipulation .

**Frameworks for building custom medical imaging storage and API solutions**: Combine **Orthanc** for lightweight DICOM storage with REST API and multi-tenant support . Use **dcm4chee** for enterprise-grade PACS . Deploy **OHIF Viewer** for zero-footprint web viewing . Integrate **DCMTK** or **pydicom** for DICOM file processing . Choose **DICOMcloud** for DICOMweb on Azure or **dicomweb-proxy** for DIMSE bridging . Use **Stone Web Viewer** for bandwidth-efficient viewing with Orthanc . Note that true enterprise medical imaging cloud with PB-scale storage, automated de-identification, and vendor-supported SLAs (AWS HealthImaging, Google Medical Imaging Suite, Azure DICOM) remains primarily commercial territory; open-source stacks provide strong DICOM storage, viewing, and API foundations that require integration for complete medical imaging workflows.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Medical imaging platforms handle protected health information (PHI) and must comply with HIPAA, GDPR, and applicable medical device regulations. **Self-hosted solutions require proper security hardening, encryption at rest and in transit, and audit logging**.
- **DICOM de-identification is critical** — Orthanc, Google Cloud, and Flywheel provide automated de-identification, but manual review is recommended before research use .
- **Cloud DICOM services may be regulated as medical devices** in some jurisdictions. Validate regulatory status before clinical use.
- **License considerations**: Orthanc uses GPL-3.0, dcm4chee uses MPL-1.1, OHIF uses MIT, and DCMTK uses BSD-3-Clause. Verify licensing against your use case before committing.
- The open-source ecosystem provides strong DICOM storage, viewing, and API foundations, but **PB-scale storage, automated de-identification, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for medical imaging engineers, PACS administrators, and organizations seeking imaging data sovereignty.**
Let's make medical imaging cloud storage and APIs more open, transparent, and interoperable.
