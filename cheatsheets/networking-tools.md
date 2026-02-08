# Networking Tools Cheat Sheet (Linux / WSL)

## Connectivity Checks
- `ping google.com` → test internet connectivity
- `ping <ip>` → test host reachability
- `traceroute google.com` → trace network path
- `mtr google.com` → live traceroute + ping (if installed)

Install traceroute:
```bash
sudo apt install traceroute -y
