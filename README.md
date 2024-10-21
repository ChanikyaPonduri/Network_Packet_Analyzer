# PRODIGY_CS_05
# Packet Sniffer
This is a simple packet sniffer implemented in Python using the Scapy library. It captures network packets on a specified interface and displays the source and destination IP addresses, protocol type (TCP/UDP), ports, and payload data.

Features
Packet Capture: Captures packets on a specified network interface.
IP Address Display: Displays source and destination IP addresses for each captured packet.
Protocol Identification: Identifies and displays TCP or UDP protocol information.
Payload Display: Shows the payload of captured packets in hexadecimal format.
Requirements
Python 3.x
Scapy library
Installation
Install Python: Ensure that Python is installed on your system. You can download it from the official Python website.

Install Scapy: You can install the Scapy library using pip:

Copy code
pip install scapy
Usage
Run the Script: Execute the Python script in your terminal or command prompt:

Copy code
python packet_sniffer.py
Select Network Interface: The script will display a list of available network interfaces. Enter the desired interface for packet capturing.

Packet Information Display: The script will start capturing packets on the selected interface and display information for each captured packet, including:

Source IP Address
Destination IP Address
Protocol (TCP or UDP)
Source and Destination Ports
Payload (in hexadecimal format)
Important Notes
Permissions: Running this script may require administrative or root privileges to access network interfaces and capture packets.
Network Interface: Make sure to select the correct network interface for capturing packets. Running the script on a wrong interface may not yield any useful data.
Ethical Use: Use this script responsibly and only on networks for which you have permission to capture traffic.
