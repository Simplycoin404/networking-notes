# Ports and Protocols

Ports help devices identify specific network services.

Protocols define the rules for communication.

---

# Common Ports

| Port | Protocol | Purpose |
|------|-----------|---------|
| 20/21 | FTP | File Transfer |
| 22 | SSH | Secure Remote Access |
| 23 | Telnet | Remote Access |
| 25 | SMTP | Email Sending |
| 53 | DNS | Domain Name Resolution |
| 67/68 | DHCP | Automatic IP Addressing |
| 80 | HTTP | Web Traffic |
| 443 | HTTPS | Secure Web Traffic |
| 3389 | RDP | Remote Desktop |

---

# TCP vs UDP Ports

Some protocols use TCP.
Some use UDP.

Examples:
- HTTP uses TCP
- DNS commonly uses UDP
- HTTPS uses TCP

---

# Why Ports Matter

Ports allow multiple services to run on the same device.

Example:
- A server can host:
  - HTTPS on port 443
  - SSH on port 22
  - DNS on port 53
