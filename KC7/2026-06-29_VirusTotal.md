# VirusTotal Fundamentals 

[View Badge](VirusTotal.pdf)

- Date: 29/06/2026
- Platform: KC7

## Overview

Completed the VirusTotal Fundamentals module on the KC7 Cyber Platform, gaining hands-on experience using VirusTotal for malware analysis, threat intelligence, and IOC investigation. The module focused on understanding file reputation, behavioral analysis, digital signatures, MITRE ATT&CK mappings, and pivoting between related indicators to investigate cyber threats.

## Skills Gained

### VirusTotal Analysis

* Analyzed files, URLs, domains, IP addresses, and file hashes.
* Understood how VirusTotal aggregates results from multiple antivirus engines.
* Interpreted detection ratios (e.g., 15/72), representing the number of engines detecting a file as malicious out of the total engines that scanned it.
* Learned that uploading files to VirusTotal makes them available to the security community, making it unsuitable for confidential or sensitive files.

### File Metadata Analysis

* Examined file metadata, including:

  * File type
  * File size
  * Creation time
  * Modification time
  * First submission (upload) time
  * Last analysis time
* Learned that some timestamps can be manipulated (timestomping) and should be verified with additional evidence.

### Threat Intelligence & IOC Pivoting

* Pivoted between:

  * SHA-256 hashes
  * Domains
  * IP addresses
  * URLs
  * Digital certificates
  * Related files
* Investigated attacker infrastructure by following relationships between indicators.

### Malware Identification

* Identified malware families using VirusTotal intelligence.
* Learned the role of malware loaders such as IcedID, which can steal credentials and download additional malware.
* Understood that malware samples are often renamed using their SHA-256 hash for easier identification.

### Behavioral Analysis

* Investigated:

  * Process trees
  * Parent and child processes
  * Registry modifications
  * Command-line execution
  * Network communications
  * Command-and-Control (C2) infrastructure

### Digital Signatures

* Examined code-signing certificates.
* Verified certificate status through Details → Signature Info.
* Understood how attackers abuse or steal certificates to make malware appear legitimate.

### Detection Rules

* Learned how YARA rules identify malware based on file characteristics and patterns.
* Learned how Sigma rules provide vendor-neutral detection logic for SIEM platforms.

### MITRE ATT&CK

* Mapped observed behaviors to the MITRE ATT&CK framework.
* Understood that every attack technique is assigned a unique ATT&CK ID to standardize threat classification.

### Malware Evasion

* Learned that attackers may pack or inflate malware to evade sandbox analysis.
* Understood that defenders can unpack or deflate supported samples using tools such as **DBlob** for deeper inspection.

### Community Intelligence

* Used VirusTotal comments and community contributions to discover additional indicators, such as C2 infrastructure, while understanding that community-provided information should always be validated.

## Key Learning Outcomes

* Differentiate between benign and malicious files.
* Interpret VirusTotal reports accurately.
* Analyze file metadata and behavioral indicators.
* Investigate digital signatures and certificate trust.
* Understand malware behavior using process, registry, and network analysis.
* Apply MITRE ATT&CK techniques during malware investigations.
* Develop practical threat intelligence and malware analysis skills using VirusTotal.
