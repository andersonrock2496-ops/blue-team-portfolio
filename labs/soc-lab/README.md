# SOC Lab – Splunk Enterprise + Kali Linux + pfSense

## 📌 Overview
This project demonstrates a basic Security Operations Center (SOC) lab focused on
log ingestion and visibility using Splunk Enterprise and Splunk Universal Forwarder.

The lab simulates a realistic environment where a Linux host forwards system logs
to a centralized SIEM for analysis.

---

## 🧱 Lab Architecture

- **Splunk Server (Indexer + Search Head)**
  - IP: `192.168.10.104`
  - Receiving data on TCP `9997`

- **Kali Linux**
  - Splunk Universal Forwarder installed
  - System logs forwarded from `journal.log`

- **pfSense**
  - Acts as the network perimeter firewall
  - Provides realistic SOC lab topology

---

## 🔎 What Was Implemented

- Installed and configured Splunk Enterprise
- Installed Splunk Universal Forwarder on Kali Linux
- Configured secure forwarding to Splunk Server
- Verified data ingestion via Splunk Search
- Confirmed active forwarder connection

---

## 🖼️ Evidence

Screenshots demonstrating:
- Splunk server running
- Active forwarder connection
- Log events successfully indexed
- Virtualized lab environment

See `/evidence` directory.
