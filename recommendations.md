# Security Recommendations

## 1. Minimize exposed services

Only services required for business operations should be
accessible.

## 2. Secure SSH

- Use strong authentication
- Prefer SSH keys where appropriate
- Disable unnecessary authentication methods
- Restrict SSH access using firewall rules

## 3. Secure the web server

- Keep Apache updated
- Remove unnecessary modules
- Avoid exposing sensitive information
- Review web server configuration

## 4. Network segmentation

Administrative services such as SSH should preferably be
restricted to trusted management networks.

## 5. Continuous monitoring

Monitor authentication logs and network activity for
unexpected connections.

## 6. Regular reconnaissance

Periodically review exposed services to identify
unnecessary or newly exposed ports.
