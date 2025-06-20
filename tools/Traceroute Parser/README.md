# Traceroute Automation Script

This PowerShell script performs a traceroute and extracts each hop's latency and network path data.

##  Usage

1. Add target IPs/FQDNs to `targets.txt`
2. Edit the file path for input and output locations `tracert.ps1`
3. Run `tracert.ps1`
4. Outputs to `traceroute_results.csv`

###  Output Fields

- TargetHost
- HopNumber
- Latency1 / Latency2 / Latency3
- Hostname
- IP Address

> Used for network diagnostics, routing verification, and latency tracking.
