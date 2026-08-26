Python Port Scanner

Simple TCP port enumeration tool for network reconnaissance.

Features
* Scans target IP for open ports
* Real-time scan output with timestamps
* Error handling for connection issues


Requirement

Python 3.x
Target IP or hostname

Usage
python3 scanner.py <ip>

Example:

python3 scanner.py 192.168.1.1

How It Works
Resolves target hostname to IP
Scans ports 50-85 with TCP connections
Reports open ports in real-time
Handles errors gracefully (Ctrl+C to exit)
Current Scan Range

Ports 50-85 (customizable in code)
