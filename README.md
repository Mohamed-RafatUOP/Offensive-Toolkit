# Offensive-Toolkit
Recon & SSH Toolkit

Simple Python toolkit for learning cybersecurity scripting and networking in a safe lab environment.

Features
WHOIS lookup
DNS enumeration
Banner grabbing
SSH interaction testing
SFTP file transfer testing
Localhost-only reverse shell demo
Files
recon_tool.py
WHOIS lookup
DNS record enumeration
HTTP banner grabbing
Saves results to JSON
ssh_interaction.py
SSH login testing
Remote command execution
SFTP upload testing
sandboxed_payload.py

Educational localhost-only reverse shell demonstration.

Restricted to 127.0.0.1 for safe testing.

Requirements

pip install python-whois dnspython paramiko

Usage

python recon_tool.py

python ssh_interaction.py

python sandboxed_payload.py
