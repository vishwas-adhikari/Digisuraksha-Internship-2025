# Cybersecurity Tools Overview

**Author**: Vishwas S Adhikari  
**Intern ID**: 135  
**Email**: vishwas.s.1002@gmail.com  

This document provides a summarized report on two powerful tools used in cybersecurity and OSINT (Open Source Intelligence): **Carrot2** and **Zapmeta**. Both tools assist in gathering and organizing information from open sources, helping cybersecurity professionals uncover patterns, trends, and threats effectively.

> ⚠️ **NOTE**: The complete report is written in the PDF file attached in this folder.  
> Please refer to it for full details and the **Proof of Concept (POC)**.

---

## Tool 1: Carrot2

**Overview**:  
Carrot2 is an open-source search results clustering engine written in Java. It automatically organizes unstructured text (like search results or articles) into thematic clusters.

### Key Highlights:
- Developed originally as a master’s thesis project in 2001; now maintained by Carrot Search.
- Uses advanced clustering algorithms: **Lingo** and **STC**.
- Integrates with search engines like **Solr**, **Lucene**, **Bing**, and **PubMed**.
- REST API & Web Workbench for visualization and experimentation.
- Useful visualizations: treemaps and pie charts for easy insight.

###  Use in Cybersecurity:
- Ideal for OSINT investigations, especially in analyzing massive text data like threat reports or forum posts.
- Automatically clusters topics like **“Threat Actors”**, **“Malware Types”**, or **“Vulnerabilities”**.
- Helps identify trends (e.g., ransomware techniques, industry targets) quickly.

### Proof of Concept:
Used Carrot2 to analyze **"ransomware trends 2025"**:
- Clustered results into categories like **Cyberwarfare**, **Malware**, **Social Media**, etc.
- Helped visualize rising threats and emerging ransomware operations.
### POC attached in the pdf file 

---

## Tool 2: Zapmeta

**Overview**:  
Zapmeta is a meta-search engine that aggregates results from multiple sources (e.g., Bing, Yahoo, YouTube, Wikipedia) for broader intelligence gathering.

### Key Highlights:
- Combines search results across different engines in one place.
- Supports advanced search filters, Boolean operators, and domain/region targeting.
- Offers visual previews and snapshots for faster analysis.
- Integrates with the **Wayback Machine** for historical web page access.

### Use in Cybersecurity:
- Excellent tool for early-stage reconnaissance in OSINT.
- Helps discover leaked credentials, sensitive documents, or archived threat actor profiles.
- Supports Google Dorking for targeted searches (e.g., `site:pastebin.com leaked credentials`).

### Proof of Concept:
- Queried leaked data on Pastebin via Zapmeta.
- Identified sensitive data still publicly accessible via surface web.
- Demonstrated aggregated results from multiple engines to enhance threat visibility.
##POC attached in the pdf file 

---

##  Summary

| Tool | Purpose | Best Use Case |
|------|---------|----------------|
| **Carrot2** | Clusters large volumes of search data into topics | Investigating threat intelligence, identifying malware trends |
| **Zapmeta** | Aggregates multi-engine search results for OSINT | Finding leaked data, archived content, and early-stage threat discovery |

---

> These tools showcase how OSINT and data clustering can support cybersecurity research by saving time and improving visibility into emerging threats.

