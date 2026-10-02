SOC Security Monitoring & Incident Detection Lab
A simulated SOC lab focused on monitoring SSH authentication logs, identifying repeated failed login attempts, and documenting suspicious activity using Linux command-line tools.
Project Overview
This project demonstrates basic Security Operations Center (SOC) monitoring and incident analysis using a Linux environment.
The lab uses simulated SSH authentication logs to identify repeated failed login attempts from the same source IP and document the findings in an incident report.
Lab Objectives
Monitor SSH authentication logs
Identify repeated failed login attempts
Analyze source IP addresses
Count suspicious login attempts
Identify successful authentication events
Document findings in an incident report
Log Analysis
The simulated log file contains SSH authentication events, including:
Failed login attempts for invalid users
Multiple attempts from the same source IP
A successful login event
Analysis Results
Source IP: 192.168.1.50
Failed Attempts: 3
Successful Login IP: 192.168.1.10
Incident Report
The activity was documented as:
Incident Type: SSH Brute-Force Simulation
Status: Simulated suspicious activity
Action: Monitor the source IP and review authentication logs
This project uses simulated log data for learning and testing purposes.
Tools & Technologies
Ubuntu Linux
SSH
UFW Firewall
Linux Terminal
grep
wc
journalctl
Skills Demonstrated
Security log monitoring
Basic incident detection
Authentication log analysis
Source IP identification
Command-line investigation
Incident documentation
Basic SOC analysis
