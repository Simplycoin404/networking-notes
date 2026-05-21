# VLAN Basics

A VLAN (Virtual Local Area Network) separates devices into different logical networks.

VLANs help:
- organize networks
- improve security
- reduce broadcast traffic
- isolate devices

---

# Why VLANs Matter

Without VLANs, all devices are on the same network.

Example:

```txt
192.168.1.x
```

This can create:
- unnecessary traffic
- security risks
- poor organization

---

# Example VLAN Setup

| VLAN | Purpose |
|------|---------|
| VLAN 10 | Staff |
| VLAN 20 | Guests |
| VLAN 30 | Security Cameras |

Devices in different VLANs are separated unless routing is configured.

---

# VLANs and Switches

Switches commonly manage VLANs.

A switch can assign ports to different VLANs.

Example:

```txt
Port 1 → VLAN 10
Port 2 → VLAN 20
```

---

# Trunk Ports

Trunk ports carry traffic for multiple VLANs between networking devices.

Trunks are commonly used between:
- switches
- routers
- access points

---

# Benefits of VLANs

VLANs improve:
- security
- organization
- performance
- scalability

---

# Real World Example

A business may separate:
- employee devices
- guest WiFi
- security cameras
- servers

using VLANs.
