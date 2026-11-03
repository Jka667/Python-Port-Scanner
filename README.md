# Python Port Scanner

Minimal TCP connect scanner written with the Python standard library (`socket`).

## Skills demonstrated
- Socket programming, DNS resolution, error handling (timeouts, unknown host, Ctrl+C)
- Network reconnaissance basics (ATT&CK T1046 Network Service Discovery)

## Value for an employer
- Understands what a port scan looks like on the wire, which helps write detections for it (many connection attempts from one source in a short window)
- Quick check of exposed services during troubleshooting or asset reviews

## Quick start
```bash
python3 Scanner.py <ip-or-hostname>
```
Scans ports 50–84 by default (change `range(50, 85)` in the code).

> Scan only systems you own or are authorized to test.
