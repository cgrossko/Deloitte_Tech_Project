**Project Overview**

Daikibo Industrials, a global leader in heavy machinery manufacturing, headquartered in Tokyo, Japan, has recently signed with Deloitte to address various challenges within their operations. As they integrate Industrial Internet-of-Things (IIoT) devices into their manufacturing processes, they require solutions for data unification, analysis, and security. This document outlines the tasks completed to support Daikibo in their transformation journey.

**Task 1: Data Integration for IIoT Devices**

Objective: Daikibo Industrials needed assistance in combining telemetry data from two different IIoT device formats.

Approach:

Developed an algorithm to standardize data formats from both sets of devices, ensuring compatibility and coherence in data streams.

The unified data format allows for seamless monitoring, measurement, and analysis across all IIoT devices within their manufacturing infrastructure.

**Task 2: Telemetry Data Analysis in Tableau**

Objective: Analyze the unified telemetry data to provide insights into Daikibo’s manufacturing processes.

Approach:

Imported the combined telemetry data into Tableau.

Created dashboards and visualizations to highlight key metrics and operational performance indicators.

Analyzed trends and patterns to assist in predictive maintenance and optimize manufacturing workflows.

**Task 3: Development Proposal for Private Dashboard**

Objective: Develop a private dashboard for real-time monitoring of machine health across Daikibo's factories.

Proposal Summary:

Dashboard Scope: The dashboard will display the health status of 9 machines across 4 factories (Berlin, Meiyo, Seiko, and Shenzen).

Access Control: Restricted to Daikibo’s intranet, with authentication synced to the internal authentication server to utilize company-wide user accounts.

Features: A single-page view listing all monitored devices, with expandable sections at the factory and device levels to show the status history.

User Experience: Designed to provide a clear and concise view of machine health, enabling quick response to any anomalies detected.

**Task 4: Cyber Security Analysis**

Objective: Assess the possibility of an alleged security breach and analyze web activity logs for suspicious behavior.

Approach:

Access Assessment: Reviewed the access requirements for the status dashboard and confirmed that access is limited to authenticated users within Daikibo’s intranet, making an external breach unlikely without VPN access.

Log Inspection: Analyzed the web_requests.log file for any irregular patterns that could indicate unauthorized access attempts or automated requests. Identified and documented potential security concerns based on log analysis.

**Task 5: Equality Analysis and Classification**

Objective: Process and classify employee compensation data to evaluate equality across different roles and factories.

Approach:

Processed the "Equality Table.xlsx" containing data on factory, job role, and equality scores.

Added a fourth column, “Equality Class,” to classify each score based on predefined criteria:

Fair: Scores within ±10.

Unfair: Scores outside the range of ±10 but within ±20.

Highly Discriminative: Scores less than -20 or greater than 20.
