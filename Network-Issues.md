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
## Issue 2: Unable to Access Internal Network Resources

### Symptoms
- Internet access works
- Cannot access shared folders or internal applications

### Possible Causes
- Incorrect DNS server configuration
- VPN not connected
- Firewall restrictions

### Troubleshooting Steps
1. Verified DNS server settings
2. Tested connectivity to internal servers
3. Confirmed VPN connection was active
4. Temporarily disabled firewall for testing

### Resolution
Connecting to the VPN restored access to internal resources.

### What I Learned
Internal resource access often depends on proper DNS configuration and secure VPN connections.
