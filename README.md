# Enhancing Wazuh SIEM with Cross-Layer Security and AI-Based Anomaly Detection

## Overview

This Final Year Project (FYP) enhances the capabilities of **Wazuh SIEM** by integrating **Suricata IDS** and **AI-based anomaly detection** to improve security monitoring and incident detection. The system collects security logs from multiple sources, analyzes them using SIEM and machine learning techniques, and presents the results through a centralized dashboard for efficient threat investigation.

The project demonstrates how host-based monitoring, network intrusion detection, and AI can work together to detect suspicious activities more effectively than traditional signature-based detection alone.

---

# Objectives

* Deploy and configure Wazuh SIEM.
* Integrate Suricata IDS for network monitoring.
* Collect logs from multiple security sources.
* Detect suspicious activities using AI models.
* Visualize alerts using OpenSearch Dashboards.
* Improve incident detection through cross-layer security monitoring.

---

# Features

* Centralized log collection
* Host security monitoring
* Network intrusion detection
* AI-based anomaly detection
* Real-time alert generation
* Interactive dashboards
* Security event investigation
* Multi-source log analysis

---

# System Architecture

The project consists of the following components:

* Wazuh Manager
* Wazuh Agent
* OpenSearch Indexer
* OpenSearch Dashboards
* Suricata IDS
* AI Detection Module
* Ubuntu Linux
* Kali Linux
* Windows Machine

### Workflow

1. Wazuh Agent collects logs from endpoints.
2. Suricata monitors network traffic.
3. Logs are forwarded to Wazuh Manager.
4. Wazuh processes and normalizes security events.
5. Logs are stored in OpenSearch.
6. AI models analyze logs for anomalies.
7. Alerts are displayed in OpenSearch Dashboards.
8. Security analysts investigate generated alerts.

---

# Technologies Used

## SIEM

* Wazuh

## Search & Visualization

* OpenSearch
* OpenSearch Dashboards

## IDS

* Suricata

## Programming

* Python

## Operating Systems

* Ubuntu Linux
* Kali Linux
* Windows

## Virtualization

* VMware Workstation
* VirtualBox

---

# Project Structure

```
FYP/
│
├── AI_Model/
│   ├── train.py
│   ├── predict.py
│   ├── dataset/
│   └── models/
│
├── Suricata/
│
├── Wazuh/
│
├── OpenSearch/
│
├── Screenshots/
│
├── Documentation/
│
├── Reports/
│
├── README.md
│
└── requirements.txt
```

---

# Installation

## Step 1

Install Ubuntu Server.

---

## Step 2

Install Wazuh Manager.

---

## Step 3

Install OpenSearch Indexer.

---

## Step 4

Install OpenSearch Dashboards.

---

## Step 5

Install Wazuh Agent on monitored machines.

---

## Step 6

Install and configure Suricata IDS.

---

## Step 7

Connect Suricata logs with Wazuh.

---

## Step 8

Install Python dependencies.

Example:

```
pip install -r requirements.txt
```

---

## Step 9

Train the AI model.

Example:

```
python train.py
```

---

## Step 10

Run the anomaly detection module.

Example:

```
python predict.py
```

---

# AI Module

The AI component analyzes security logs collected by Wazuh to identify anomalous behavior that may indicate cyber attacks.

### Functions

* Data preprocessing
* Feature extraction
* Model training
* Anomaly prediction
* Alert generation

---

# Log Sources

The project monitors logs from:

* Linux system logs
* Windows Event Logs
* Suricata alerts
* Authentication logs
* Network traffic
* Security events

---

# Attack Simulations

The following activities were performed to validate the solution:

* Port scanning
* Failed login attempts
* Brute-force simulation
* Network intrusion detection
* Security alert generation

These simulations verified that Wazuh, Suricata, and the AI module successfully detected and reported suspicious activities.

---

# Dashboard

OpenSearch Dashboards provide visualizations for:

* Security alerts
* Event timeline
* Log analysis
* Network activity
* Threat trends
* Host monitoring
* System health

---

# Results

The implemented solution successfully:

* Collected security logs from multiple sources.
* Detected suspicious network activity.
* Generated real-time alerts.
* Improved threat visibility through centralized monitoring.
* Demonstrated AI-assisted anomaly detection.
* Simplified security event investigation using a unified dashboard.

---

# Future Improvements

* Integrate SOAR for automated incident response.
* Add threat intelligence feeds.
* Support cloud log monitoring.
* Improve AI model accuracy.
* Deploy in production-scale environments.
* Add automated reporting and notifications.

---


