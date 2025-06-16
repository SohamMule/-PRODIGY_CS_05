# PRODIGY_CS_05
Packet Sniffer (Command-Line) – Educational Use Only
This Python script uses Scapy to capture and display key information about network packets. It capture packets of protocols UDP TCP and all.

Features
Captures and analyzes:
Source & Destination IPs
Protocol (TCP/UDP/all)
First 50 bytes of raw payload (if available)

Requirements
Scapy
Install Scapy if not already installed:
pip install scapy

Example output:
Packet Sniffer Tool (educational use only)
tcp/udp/all protocols
Capturing  packet(s)... (Press shift+F5 to stop early)

Packet:
   From: 192.168.1.5
   To:   93.184.216.34
   Protocol: TCP
   Payload (first 50B): b'GET / HTTP/1.1\r\nHost: example.com\r\n\r\n'
   
Disclaimer
This tool is strictly for educational and authorized network analysis.
Unauthorized packet sniffing may violate privacy laws and network policies.
Always obtain permission before using on any network.
