# Custom_VPN_Configuration
# OpenVPN Secure VPN Setup
This project demonstrates how to securely configure a Virtual Private Network (VPN) using OpenVPN, implement encryption standards, configure the server and client, and test the connection for integrity and security.

# 🚀 Project Overview
# Objective: 

Configure a secure VPN using OpenVPN and test encrypted communication.
# Approach: 

Manual setup of OpenVPN server and client with cryptographic material generation, firewall configuration, and VPN testing tools.

# 🛠️ Tools & Technologies
OpenVPN
Easy-RSA (for generating CA and certificates)
Linux (Ubuntu/Parrot OS)
Wireshark (for packet analysis)
ping, ifconfig, iptables for testing and setup
🔐 Security Features
AES-256-CBC encryption
RSA certificates (2048/4096 bit)
TLS-auth for control channel protection
Diffie-Hellman parameters for key exchange

# 🧪 Testing
Verified secure tunneling using ping and traceroute
Used Wireshark to analyze encrypted traffic
Checked for IP masking and DNS leaks

