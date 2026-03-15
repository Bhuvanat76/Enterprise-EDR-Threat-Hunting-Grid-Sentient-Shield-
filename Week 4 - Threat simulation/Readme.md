**# Week 4 – Threat Simulation \& Detection**



\## Objective

Simulate attacker behavior and validate the SIEM's ability to detect malicious activities.



\## Attack Simulations Performed



\### PowerShell Execution

Simulated suspicious command execution.



powershell -ExecutionPolicy Bypass -Command "whoami"



\### Account Discovery

Simulated attacker reconnaissance activity.



net user



\### System Information Discovery

Simulated system enumeration.



systeminfo



\### Suspicious File Creation

Simulated malware dropping a file in a public directory.



echo malware > C:\\Users\\Public\\malware.exe



\## Alerts Observed

The Wazuh SIEM detected multiple suspicious activities including:



\- PowerShell execution events

\- Account discovery commands

\- Suspicious file creation

\- Security rule triggers with MITRE ATT\&CK mappings



\## Outcome

The simulated attack activities generated multiple security alerts in Wazuh, demonstrating the system's ability to detect and analyze potential threats.



\## Skills Demonstrated

\- Threat simulation

\- Security event analysis

\- MITRE ATT\&CK mapping

\- SIEM alert investigation

