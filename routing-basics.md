# Routing Basics

Routing is the process of moving data between different networks.

Routers make decisions about where traffic should go.

---

# What Routers Do

Routers:
- connect networks together
- forward packets
- determine the best path for traffic

Example:

```txt
Home Network → Internet
```

---

# IP Addresses and Routing

Routers use IP addresses to route traffic.

Example:

```txt
192.168.1.10
```

A router checks the destination IP address and forwards the packet toward the correct network.

---

# Default Gateway

The default gateway is the router a device uses to reach other networks.

Example:

```txt
192.168.1.1
```

If a device needs to communicate outside its local network, it sends traffic to the default gateway.

---

# Routing Table

Routers use routing tables to determine where traffic should go.

A routing table contains:
- destination networks
- next hop addresses
- interfaces

---

# Static vs Dynamic Routing

## Static Routing
Routes are manually configured.

## Dynamic Routing
Routers automatically learn routes using routing protocols.

Examples:
- OSPF
- EIGRP
- BGP

---

# Why Routing Matters

Routing is critical for:
- internet communication
- enterprise networks
- VLAN communication
- WAN connections
