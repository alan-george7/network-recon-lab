# Reconnaissance Notes

## Target

Ubuntu Server

## Target IP

192.168.56.102

## Discovered Services

| Port | Protocol | Service | Purpose |
|------|----------|---------|---------|
| 22 | TCP | SSH | Remote administration |
| 80 | TCP | HTTP | Web service |

## Observations

Port 22 is exposed for SSH administration.

Port 80 is exposed and hosts an Apache web server.

## Security Considerations

SSH should only be accessible from trusted administrative networks.

The web server should be kept updated and configured securely.

Only required services should be exposed.
