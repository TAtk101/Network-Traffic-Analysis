# Network Traffic Analysis Using Splunk & Wireshark

## Overview
This project demonstrates hands-on network traffic analysis using Wireshark and Splunk. Network packet data was captured locally, exported to CSV format, and analyzed in Splunk using SPL queries and visual dashboards. The goal of this project is to simulate real-world IT and SOC analyst workflows for monitoring, investigating, and understanding network behavior.

---

## Objectives
- Identify top destination IP addresses on the network
- Analyze network protocol usage and distribution
- Visualize network traffic patterns using Splunk dashboards
- Establish a baseline of normal network activity

---

## Tools & Technologies
- **Wireshark** – Network packet capture and inspection
- **Splunk** – Log ingestion, search, and visualization
- **SPL (Search Processing Language)** – Data analysis queries
- **CSV** – Exported packet capture format

---

## Data Collection
- Network traffic was captured using Wireshark on a local system
- Packet capture data was exported as a CSV file
- The CSV file was ingested into Splunk as a data source

---

## Analysis Performed

### Top Destination IP Addresses
- Identified the most frequently contacted IP addresses

### Network Protocol Distribution
- Analyzed protocol usage such as TCP, UDP, and ICMP
- Established a baseline of normal protocol activity

### Traffic Volume Analysis
- Measured frequency of communication between source and destination IPs
- Identified high-volume traffic patterns

### Dashboard Visualization
- Built Splunk dashboards using tables and bar charts
- Enabled quick interpretation of network activity trends

---

## Sample SPL Queries
All SPL queries used for analysis and visualization are documented in:
- **`Splunk_Queries.txt`**

These include searches for:
- Top destination IP addresses
- Protocol distribution
- Source-to-destination traffic mapping

---

## Project Structure
