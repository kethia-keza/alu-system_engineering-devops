# Firewall

This project configures the ufw firewall on web-01 to block all incoming traffic except SSH, HTTP and HTTPS.

## Tasks

### 0. Block all incoming traffic but
File: `0-block_all_incoming_traffic_but`

Installs ufw and applies these rules:
- Deny all incoming traffic by default
- Allow TCP port 22 (SSH)
- Allow TCP port 80 (HTTP)
- Allow TCP port 443 (HTTPS SSL)
