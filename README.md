# SOC-Incident-investigation-lab
SOC lab detecting and investigating simulated cyber attacks using Splunk and Sysmon
# SOC Incident Investigation Lab

## Objective
Simulate cyber attacks and investigate alerts using SIEM.

## Tools Used
- Windows VM
- Kali Linux
- Sysmon
- Splunk SIEM

## Attack Scenarios
1. Port scan using Nmap
2. Brute-force login attempt
3. Suspicious PowerShell download

## Investigation Steps
- Collected logs from Sysmon
- Detected failed logins in Splunk
- Correlated IP addresses
- Mapped activity to MITRE ATT&CK

## MITRE ATT&CK Mapping
- T1110 Brute Force
- T1046 Network Scan
- T1059 Command Execution

## Result
Successfully detected and investigated simulated attack.
