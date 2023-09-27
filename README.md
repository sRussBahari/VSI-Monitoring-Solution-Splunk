# Project Title: VSI-Monitoring-Solution-Splunk
Date: Aug 2023- Sep 2023


## Overview
Creation of a monitoring environment for incident response, ensuring the security of a mock organization (VSI) via Splunk

## Key Achievements
1) Analyzed activity logs (Windows and Apache Server logs) to understand what activities are happening within the server as well as selecting a baseline for the organization to detect anything suspicious for any subset of data analyzed ie: severity, signature, IP address etc...

2) Developed and executed custom alerts/reports/dashboard accodingly to the baseline that was set and those information will directly be reported to the person in charge of the security by email as soon as the baseline exceed the threshold selected. This is very helpful to detect and counter anomalies in real time.

3) Enhanced the monitoring capabilities by integrating a Splunk "add-on" app, chosen specifically to make a more friendly-user dashboard environment and fortify defense against a certain type of cyber attack.

## Technologies Used
-Splunk


## Screenshots
4 sets of logs: 
-Windows server  
-Windows server attack logs
-Apache server
-Apache server attack logs

Comparison of data from the server before and after an attack:
1) Changes in windows logs for severity data?
-After loading the logs of the Windows server both the attack and non attack, there were suspicious changes in severity as the informational severity went from 93% from the normal Windows logs to 79% and the high severity from 6% from the normal Windows logs to 20% within the new file which shows a higher severity.
![Severity data report](./Severity_normal_logs.png)
![Severity data report](./Severity_attack_logs.png)

2) Changes in windows logs for failed activities?
-![Failed/Success activites](./Success_Failed_Activities_normal_logs.png)
-![Failed/Success activites](./Success_Failed_Activities_attack_logs.png)








