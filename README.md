# 📊 Azure Monitoring & Log Analytics

## 🎯 Objective
This lab demonstrates how to **monitor and analyze infrastructure performance** in Microsoft Azure using **Log Analytics, Azure Monitor, and Alerts**.  
The goal was to create a centralized monitoring system capable of collecting metrics, visualizing real time data, and triggering alerts when thresholds are exceeded.

---

## ⚙️ Environment Setup
**Resource Group:** `Lab3-MonitorRG`  
**Region:** `West Europe`  
**Main Resources:**
- Virtual Machine (connected via Azure Monitor Agent)  
- Log Analytics Workspace (`lab3-logworkspace`)  
- Data Collection Rule  
- Azure Monitor Alerts  
- Custom Dashboard for visualization  

---

## 🧩 Steps & Screenshots

### 1️⃣ Resource Group
Resource group created to isolate all monitoring components.  

![Resource Group](01-resource-group.png)

---

### 2️⃣ Log Analytics Workspace
Centralized workspace created to store logs and performance metrics.  

![Log Workspace](02-log-workspace.png)

---

### 3️⃣ Connecting the VM
The VM was connected through the **Azure Monitor Agent (AMA)** and linked to the workspace using a **Data Collection Rule**.  

![Logs Heartbeat](03-logs-heartbeat.png)  

---

### 4️⃣ Alert Rule
Created an alert that triggers when **CPU usage exceeds 80%**, demonstrating proactive monitoring and incident detection.  

![Alert Rule](04-alert-rule.png)

---

### 5️⃣ Dashboard Visualization
Built a custom **Azure Monitor Dashboard** to visualize:
- CPU percentage (Average)  
- Memory usage  
- Heartbeat frequency  

![Dashboard](05-dashboard.png)

---

## 🔍 Results
✅ VM connected to Log Analytics Workspace  
✅ Real time data collection verified through heartbeat logs  
✅ Automatic alert configured for CPU threshold  
✅ Custom dashboard displaying live performance metrics  

---

## 🧠 Key Concepts Learned
- **Azure Monitor** for real time metric tracking  
- **Log Analytics** and **KQL queries** for data analysis  
- **Alerts and Action Groups** for automated responses  
- **Heartbeats** as indicators of resource health  
- **Dashboard creation** for visual performance insights  

---

## 👤 Author
**Xavier Mota**  
Microsoft Certified: Azure Fundamentals (AZ-900)  
AZ-104 in Progress | SOC Level 1 Certified  
[LinkedIn](https://linkedin.com/in/xaviermota7) 
