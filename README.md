# Incident Monitoring Demo

## Overview

**Objective**: Demonstrate the process of incident monitoring using Datadog, showcasing metrics collection, incident detection, and alert response.

**Tools Used**:
- **IDE**: Visual Studio Code
- **Monitoring Tool**: Datadog
- **Alerting System**: Email Alert Integration
---

## Steps

### Step 1: Setting Up the Environment

<img width="960" alt="datadog 11" src="https://github.com/user-attachments/assets/729c7c07-24bd-4ea1-86c6-e64e4afe518a" />

**Description**:
- Install and configure the Datadog agent on the Linux system.
  
- Verify the agent installation by running `datadog-agent status` and observing logs.

---

### Step 2: Configuring Metrics Collection

<img width="960" alt="DATADOG 2" src="https://github.com/user-attachments/assets/a1cb6739-73ec-400f-8280-b3c32d080af6" />

<img width="960" alt="datadog 3" src="https://github.com/user-attachments/assets/d8269d2b-0797-4f3d-8a8a-bf9dcc58eed5" />

**Description**:
- Set up metric collection by defining key performance indicators (KPIs) such as CPU usage, memory usage, and disk I/O.
- Update configuration files (e.g., `datadog.yaml`) to include metrics sources.
- Use commands like `datadog-agent check` to verify metric collection from configured sources.
- Ensure accurate collection by testing configurations locally before proceeding to dashboard integration.

---

### Step 3: Monitoring Metrics

<img width="960" alt="DATADOG 5" src="https://github.com/user-attachments/assets/3cfbb6ba-1c1f-453c-a242-bc0692543a06" />

**Description**:
- Navigate to the Datadog dashboard and locate the metrics collected from the agents.
- Create dashboards for visualizing metrics like CPU utilization, memory availability, and process monitoring.
- Use widgets such as line graphs and heatmaps for real-time tracking.
- Analyze the trends and identify anomalies by setting baselines for expected performance.

---

### Step 4: Setting Up Alerts

**Description**:
- Configure alert thresholds for critical metrics (e.g., CPU usage exceeding 80%).
- Use the Datadog web interface to define alert conditions, such as `avg(cpu.usage) > 80 for 5m`.
- Test alert functionality by simulating scenarios where metrics exceed thresholds.
- Integrate email or messaging tools (e.g., Slack, PagerDuty) for incident notification.

---

### Step 5: Responding to Alerts

<img width="960" alt="datadog 9" src="https://github.com/user-attachments/assets/a090ed30-8f84-4da4-94fc-38018beffdec" />


**Description**:
  - Identify the root cause using the Datadog dashboard.
  - Mitigate the issue (e.g., restart services, scale infrastructure).
  - Acknowledge and resolve the incident on the dashboard.
- Document actions taken for future reference and learning.

---

### Step 6: Exploring Incident Details

**Description**:
- Access incident details through the Datadog Events panel.
- Review information such as:
  - Timestamp of the incident.
  - Affected metrics and their deviation from thresholds.
  - Links to related dashboards for detailed analysis.
- Use incident tags and logs to trace the origin of the issue.

---

