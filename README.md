# Network Reconnaissance Lab

## Overview

A controlled cybersecurity lab designed to practice
network reconnaissance, host discovery, port scanning,
service identification, and security analysis.

## Objectives

- Discover active hosts
- Identify exposed TCP ports
- Identify running services
- Understand TCP and UDP scanning
- Analyze exposed services
- Develop security recommendations

## Lab Architecture

Kali Linux
    |
    | Host-only Network
    |
Ubuntu Server

## Tools

- Kali Linux
- Nmap
- VirtualBox
- Ubuntu Server

## Network

192.168.56.0/24

## Target

Ubuntu Server

## Reconnaissance Process

1. Host discovery
2. Port scanning
3. Service identification
4. Service investigation
5. Security analysis
6. Recommendations

## Findings

| Port | Service | Purpose |
|------|---------|---------|
| 22 | SSH | Remote administration |
| 80 | HTTP | Web service |

## Security Implications

SSH provides remote administration and should be
restricted to trusted networks.

HTTP provides a web service and should be securely
configured and regularly updated.

## Recommendations

- Minimize exposed services
- Restrict administrative access
- Keep services updated
- Monitor authentication activity
- Review firewall rules

## Skills Demonstrated

- Network reconnaissance
- Nmap
- TCP/UDP concepts
- Service enumeration
- Linux administration
- Security analysis
- Security documentation
