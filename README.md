# Python ARP Spoofer (Python 2.7)

This project is a simple ARP spoofing / ARP manipulation tool written in Python 2.7 using the Scapy library. The script was created for learning purposes to understand how ARP works at Layer 2 and how ARP tables can be updated in real-time.

## Features
- Retrieve MAC addresses using ARP requests
- Send custom ARP replies (op=2)
- Observe ARP table changes instantly
- Dynamic packet counter
- Graceful exit with ARP table restore
- Built for learning networking fundamentals

## What I Learned While Building This
- Creating ARP responses
- Sending ARP packets using Scapy
- Extracting MAC addresses from ARP replies
- Python loops and counters
- Dynamic printing in Python
- Exception handling (CTRL+C handling)
- Writing a restore function to fix ARP tables
- Restoring ARP tables automatically on exit

## Requirements
- Python 2.7
- Scapy (Python 2 version)

Install Scapy:
pip install scapy==2.2.0

## Usage
sudo python2 arp_spoofer.py

## Disclaimer
This project is for educational and research purposes only. Do NOT use it outside your own lab or any network you do not own.
