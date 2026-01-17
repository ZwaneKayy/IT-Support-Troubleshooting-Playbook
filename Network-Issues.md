# Network Troubleshooting

This document covers common network-related issues and how to troubleshoot them in an IT support environment.
## Issue 1: User Cannot Access the Internet

### Symptoms
- Device is connected to Wi-Fi or Ethernet
- Websites do not load
- Error message: "No Internet Access"

### Possible Causes
- Incorrect IP address configuration
- DNS resolution issues
- Router or gateway connectivity problems

### Troubleshooting Steps
1. Checked network configuration using `ipconfig`
2. Verified the device received a valid IP address
3. Renewed IP address using `ipconfig /release` and `ipconfig /renew`
4. Flushed DNS cache using `ipconfig /flushdns`
5. Tested connectivity using `ping 8.8.8.8`

### Resolution
Renewing the IP address and flushing the DNS cache restored internet connectivity.

### What I Learned
Basic network troubleshooting steps such as checking IP configuration and DNS can quickly resolve most connectivity issues.
