
🛡️ DNS Log Analysis with Splunk SIEM
📘 Overview
This project focuses on analyzing DNS traffic within Splunk SIEM to detect suspicious behavior, identify anomalies, and uncover potential threats such as DNS tunneling, data exfiltration, and command-and-control (C2) activity. It demonstrates how DNS logs can be leveraged for proactive threat hunting and improved network visibility.

📊 Project Outcomes
Structured ingestion of sample DNS logs into Splunk


Custom field extractions for key DNS metadata (e.g., source IP, domain, query type)


Detection of anomalous DNS activity (e.g., spikes in queries, uncommon FQDNs)


Identification of potential threats using threat intel matching


Foundational framework for developing DNS-based detections and alerts



🧠 Project Outline
Dataset


Static sample DNS logs containing standard fields and event patterns.


Log Ingestion


Import DNS logs into Splunk with custom source type.


Field Extraction


Pull key indicators: src_ip, fqdn, query_type, response_code, etc.


Threat Hunting Queries


Frequency analysis, anomaly detection, and pattern recognition.


Enrichment & Investigation


Match DNS queries against known malicious domains or threat intel feeds.


Analysis & Reporting


Summarize findings, highlight anomalies, and suggest possible mitigations.



🎯 Goal
To build a repeatable DNS log analysis workflow within Splunk that supports real-world threat detection and strengthens cybersecurity monitoring capabilities.
