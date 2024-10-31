# Network Traffic Analyzer

## Objective
The **Network Traffic Analyzer** project captures and analyzes network traffic to detect potential security anomalies, such as port scanning, brute-force attacks, and DNS spoofing. This tool provides network administrators and security analysts with valuable insights to monitor and secure network activity.

## Features
- Capture network traffic using Wireshark.
- Analyze `.pcap` files with Python and Scapy for common network anomalies.
- Generate structured anomaly reports for further analysis.

## Prerequisites
- **Wireshark**: For capturing network traffic. Download it from [Wireshark.org](https://www.wireshark.org/download.html).
- **Python 3.x**: Required to run the analysis script.
- **Scapy**: Python library for packet manipulation.

## Directory Structure
- `/captures`: Stores network capture files (`.pcap`) for analysis.
- `/scripts`: Contains Python scripts for analyzing network traffic.
- `/reports`: Contains generated reports on detected anomalies.

## Setup and Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Bhavanaa02/Network-Traffic-Analyzer.git
   cd Network-Traffic-Analyzer
