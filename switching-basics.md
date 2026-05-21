# Switching Basics

A switch connects devices inside a local network (LAN).

Switches operate mainly at:

```txt
Layer 2 — Data Link Layer
```

---

# What Switches Do

Switches:
- connect devices together
- forward traffic
- use MAC addresses to identify devices

Example devices:
- PCs
- printers
- servers
- access points

---

# MAC Address Table

A switch learns MAC addresses and stores them in a MAC address table.

This allows the switch to send traffic only to the correct device instead of broadcasting to all devices.

---

# Frame Forwarding

When a switch receives a frame:
1. It checks the destination MAC address
2. It looks in the MAC address table
3. It forwards the frame to the correct port

---

# Broadcast Traffic

If the destination MAC address is unknown, the switch floods the frame to all ports except the source port.

---

# Collision Domains

Each switch port is its own collision domain.

This improves network performance compared to older hub-based networks.

---

# Switches vs Routers

## Switch
- operates mainly at Layer 2
- uses MAC addresses
- works inside local networks

## Router
- operates at Layer 3
- uses IP addresses
- connects different networks

---

# Why Switching Matters

Switching is important for:
- local network communication
- enterprise networking
- VLANs
- device connectivity
