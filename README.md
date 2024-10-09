# Clinic-Incident-Response
Incident response &amp; review

**** Clinic - Unusual Activity
Client has hired to come in as a security analyst on a team working for **** Clinic. **** Clinic, has a file transfer platform, recently flagged some unusual network activity that has raised alarms. The senior management is taking this incident very seriously, given the medical data contained on the network. As a contracting analyst for the Clinic, my job is to identify the nature of this alert, its potential impact, suggest mitigation strategies, and compile a review. To effectively complete the investigation I am collaborating with management and c-level execs to complete this project.

Given the alert, focus on understanding the nature of the unusual network activity, the systems and data affected, and its potential impact on Maven Clinic's network functionalities. There seems to have been multiple SSH attempts and RDP attempts - client has compiled a list of IPs which were noted as making a connection on or around the time of the unusual activity.

Tasks to complete

Log Analysis: Review the data set surrounding the reported unusual activity. Focus on:
Suspicious IPs
Unfamiliar IP addresses that might indicate unauthorized access.
Any sudden spikes in network traffic which could indicate data exfiltration.
Windows Event Logs
Failed login attempts that could signify brute-force attack attempts.
Check if any user or admin accounts accessed sensitive data 
Monitor for unauthorized access or abnormal behavior patterns.

Systems & Services Impact: Determine which systems and services were active during the time of the unusual network activity. Helpful for:
Understand if any critical systems were affected.
Identify if there were any unauthorized changes or interruptions in services.
Inform you during the second task, so that you know where to contain and mitigate this issue.

Document Findings: Go through the identification phase:
Follow the NIST steps and classify your findings (or, try compiling your key findings into a table or list!)
Document any patterns or anomalies observed.
Mark out any potential compromised accounts or services.
Document questions or clarifications for stakeholders or senior management
