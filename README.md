# Basic Network Scanning with Nmap

## Objective

The objective of this task is to perform a basic network scan
to identify open ports and services running on a local Windows
machine using Nmap.

## Tool Used

- Nmap 7.98
- Windows PowerShell

## Target

Target IP: 172.20.77.112

The scan was performed only on the user's own local machine
for educational and security analysis purposes.

## Scans Performed

### 1. Basic Scan

Command:

```text
nmap 172.20.77.112
## Security Analysis

The scan identified the following open ports:

- Port 135: Microsoft Windows RPC service.
- Port 139: NetBIOS session service.
- Port 445: Microsoft-DS, commonly associated with SMB.

These services may be necessary for Windows networking. If exposed unnecessarily, they can increase security risks. Unused services should be disabled, and firewall rules should restrict access where appropriate.

## Conclusion

This project demonstrated basic network scanning using Nmap on my local Windows machine. I performed a basic scan, service version detection, and OS detection. The results helped me identify open ports and understand potential security risks.

All scans were performed on my own machine for educational purposes.

## Files Included

- `nmap_scan_results.txt` – Scan results.
- `basic_scan.png` – Basic scan screenshot.
- `service_scan.png` – Service detection screenshot.
- `os_detection.png` – OS detection screenshot.
- `nmap_demo.mp4` – Demonstration video.
