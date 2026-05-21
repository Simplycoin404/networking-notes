# NAT (Network Address Translation)

NAT allows private IP addresses to communicate with the internet using a public IP address.

Routers commonly use NAT in home and business networks.

---

# Private vs Public IP Addresses

## Private IP Addresses

Private IPs are used inside local networks.

Examples:
- 192.168.x.x
- 10.x.x.x
- 172.16.x.x

Private IPs are NOT directly accessible from the internet.

---

## Public IP Addresses

Public IPs are used on the internet.

These addresses are assigned by an ISP.

---

# How NAT Works

1. A device sends traffic to the router
2. The router replaces the private IP with its public IP
3. The traffic is sent to the internet
4. The router keeps track of the connection
5. Responses are sent back to the correct device

---

# Why NAT Matters

NAT:
- conserves public IP addresses
- improves security
- allows multiple devices to share one public IP

---

# Example

```txt
PC IP:
192.168.1.10

Router Public IP:
73.x.x.x
```

The router translates the private address into the public address before sending traffic to the internet.
