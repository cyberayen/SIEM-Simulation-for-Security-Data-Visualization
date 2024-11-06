# SIEM-Simulation-for-Security-Data-Visualization
This project simulates a Security Information and Event Management (SIEM) system by collecting and visualizing security data from a ThingSpeak channel, including intrusion attempts, antivirus status, security alerts, CPU usage, login attempts, failed logins, firewall blocks, and Microsoft Defender usage.
# Project Overview
The goal of this project is to replicate the data analysis and visualization capabilities of a SIEM system, which typically collects, monitors, and analyzes security events in real-time. By using data from an IoT-based platform like ThingSpeak, this project demonstrates how a SIEM-like system can visualize key security parameters such as:

Intrusion Attempts: Tracking any attempts to breach the system.
Antivirus Status: Monitoring antivirus status to assess system health.
Security Alerts: Reviewing alerts triggered by various security mechanisms.
CPU Usage: Analyzing system resource utilization, which can indicate abnormal activity.
Login Attempts: Counting the number of login attempts to detect brute-force attacks.
Failed Logins: Identifying potential unauthorized access attempts.
Firewall Blocks: Observing the effectiveness of the firewall in preventing attacks.
Microsoft Defender Usage: Monitoring the use and efficiency of Microsoft Defender in defending against threats.
# Features
* Data Retrieval: The project uses the ThingSpeak API to collect the most recent security data.
* Line Graphs: Visualization of security data over time with various metrics plotted.
* Pie Charts: Distribution of total values for each field, showing the overall status of the system.
* Real-time Simulation: Simulating a SIEM system with real-time data fetching and visualization.
# Tools & Libraries
* Requests: For making HTTP requests to fetch data from ThingSpeak.
*Matplotlib: For plotting line graphs and pie charts to visualize the security data.
* NumPy: For handling numerical data and generating custom ticks on the graphs.
 # Purpose
This project is intended for:

* Security professionals who want to visualize and monitor security events and behaviors over time.
* Students and researchers studying SIEM systems and cybersecurity.
* Developers interested in simulating the analysis and monitoring of security events.
By simulating a SIEM, this project helps in understanding the role of data visualization in enhancing the effectiveness of security monitoring, which is crucial for detecting threats, managing risks, and improving overall security posture.
