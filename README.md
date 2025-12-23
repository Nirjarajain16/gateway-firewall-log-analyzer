# Gateway Firewall Log Analyzer

## Overview
This project focuses on analyzing gateway-level firewall logs to extract meaningful security insights.  
The tool processes raw firewall logs and generates structured reports that help understand network security events such as blocked or denied traffic over time.

The project simulates real-world firewall log analysis tasks typically performed in enterprise and government network environments.

---

## Objectives
- Parse gateway firewall log files
- Extract key security information such as timestamps, actions, and IP addresses
- Identify blocked/denied traffic patterns
- Generate readable summary reports for analysis and monitoring

---

## Technologies Used
- Python 3
- Linux (Kali Linux / Ubuntu)
- Firewall log concepts
- Basic log parsing and analysis

---

## How It Works
1. Firewall logs are stored in a raw text format.
2. The Python script reads the log file line by line.
3. Each log entry is validated to handle malformed or incomplete records.
4. Relevant fields such as date, action, source IP, and destination IP are extracted.
5. Parsed data is written into a structured CSV report for further analysis.

---

## Output
- CSV report containing parsed firewall events
- Data can be used for hourly, daily, or monthly security analysis
- Useful for detecting repeated blocked attempts or suspicious traffic

---

## Learning Outcomes
- Understanding of gateway firewall operations
- Hands-on experience with log analysis
- Error handling for real-world log inconsistencies
- Foundational skills for SOC and network security roles

---

## Future Enhancements
- Hour/day/week/month-based aggregation
- Graphical visualization of blocked traffic
- Integration with SIEM tools (ELK stack)
- Automated alert generation

---

## Author
**Nirjara Jain**  
Final Year Computer Engineering Student  
Ahmedabad Institute of Technology (GTU)  

