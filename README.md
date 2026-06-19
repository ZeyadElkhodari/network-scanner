# Network Scanner Tool

A Python-based network scanner built with Scapy to discover active devices on a local network using ARP requests.

---

## Features

- ARP-based network scanning  
- Detects active hosts on the network  
- Displays IP and MAC addresses  
- Fast and lightweight  

---

## Requirements

- Python 3.x  
- Scapy  

---

## Installation

```bash
pip install -r requirements.txt
```
## Usage
```
bash python network_scanner.py -r YOUR_IP_RANGE
```

## Example Output IP Address
MAC Address
-----------------------------------------
192.168.1.1         AA:BB:CC:DD:EE:FF
192.168.1.10        11:22:33:44:55:66

## Example
```
bash python network_scanner.py -r 192.168.1.0/24
```

## How It Works
The tool sends ARP requests to detect active devices on the network.

## Disclaimer
This tool is for educational purposes only and authorized use only.
