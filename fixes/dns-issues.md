# Fixing DNS Issues in WSL

## Common Symptoms
- Internet not working inside WSL
- Errors like:
  - `Temporary failure in name resolution`
  - `Could not resolve hostname`

## Why This Happens
WSL auto-generates `/etc/resolv.conf` on startup.
Sometimes the generated DNS server is unreachable.

## Quick Temporary Fix
Edit resolv.conf:
```bash
sudo nano /etc/resolv.conf
