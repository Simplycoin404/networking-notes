# Subnetting

Subnetting divides a network into smaller sections called subnets.

Subnetting helps:
- organize networks
- improve performance
- reduce broadcast traffic
- improve security

---

# CIDR Notation

CIDR represents the subnet mask using a slash.

Example:

```txt
/24
```

This means:
- 24 bits are used for the network portion
- 8 bits are available for hosts

---

# Common Subnets

| CIDR | Subnet Mask | Usable Hosts |
|------|-------------|--------------|
| /24 | 255.255.255.0 | 254 |
| /25 | 255.255.255.128 | 126 |
| /26 | 255.255.255.192 | 62 |
| /27 | 255.255.255.224 | 30 |
| /28 | 255.255.255.240 | 14 |

---

# Network Address

The network address identifies the subnet.

Example:

```txt
192.168.1.0/24
```

Network Address:
```txt
192.168.1.0
```

---

# Broadcast Address

The broadcast address is used to communicate with all devices in the subnet.

Example:

```txt
192.168.1.255
```

---

# Usable Hosts

Usable hosts are the assignable IP addresses inside a subnet.

Formula:

```txt
2^(host bits) - 2
```

The subtraction of 2 accounts for:
- network address
- broadcast address

---

# Why Subnetting Matters

Subnetting is important for:
- enterprise networks
- VLANs
- routing
- IP address management
- network efficiency
