# Network Troubleshooting

This document covers common network-related issues and how to troubleshoot them in an IT support environment.
## Issue 1: User Cannot Access the Internet

### Scenario
A user reports that they cannot access the internet while connected to Wi-Fi.

### Severity: High

### Symptoms
- Device is connected to Wi-Fi
- Websites do not load
- Ping tests fail

### Expected Result
User should have full internet connectivity

### Actual Result
No connectivity; error: "No Internet Access"

### Troubleshooting Steps
1. Checked network configuration using `ipconfig`
2. Verified the device received a valid IP address
3. Renewed IP address using `ipconfig /release` and `/renew`
4. Flushed DNS cache using `ipconfig /flushdns`
5. Tested connectivity using `ping 8.8.8.8`

### Resolution
Renewing the IP address and flushing DNS restored internet connectivity.

### Skills Demonstrated
- TCP/IP troubleshooting
- DNS & DHCP understanding
- Problem-solving
- Documentation skills

### Lessons Learned
- Always check adapter status first
- Document each step for future reference

### Lab Simulation (No Hardware Required)
| Step | Action | Expected Outcome |
|------|--------|----------------|
| 1 | Run `ipconfig` to check IP | Verify valid IP assigned |
| 2 | Release/Renew IP | Connectivity restored |
| 3 | Flush DNS | Ensure name resolution works |
| 4 | Ping external site | Confirm internet access |

### Next Steps / Improvements
- Build scripts to automate IP release/renew tasks
- Explore PowerShell for advanced network troubleshooting
- Simulate multiple network issues in a home lab

