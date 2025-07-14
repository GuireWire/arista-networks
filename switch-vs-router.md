<!--
  ~ Writing Exercise – Arista Networks Content Designer Application
  ~ Author: Anthony Maguire
  ~ Date: 2025-07-11
  ~ Purpose: Demonstration of Writing and Research Skills
-->

# What’s the difference between a Switch and a Router?

In a computer network, **switches** and **routers** play different - but equally important - roles in how data travels between devices.

![Network Switch Diagram](./network-switch.svg)

---

## Switch: Connecting devices on the same network

A **switch** is like a local connector. It links devices - such as computers, printers, or servers - within a single network (typically a Local Area Network, or **LAN**). When one device sends data, the switch determines where it should go and passes it directly to the correct recipient.

Switches use **MAC (Media Access Control)** addresses to identify devices. Over time, they “learn” which device is connected to which port, allowing them to forward traffic more efficiently. This reduces congestion and speeds up internal communication.

---

## Router: Connecting different networks

A **router**, on the other hand, connects separate networks - such as your home network to the internet. Routers use **IP (Internet Protocol)** addresses to determine where to send data across longer distances and across different networks.

In addition to routing traffic, routers may also manage network security (like firewalls), assign IP addresses via DHCP, and handle network traffic based on priority or quality-of-service rules.

---

## Summary

- A **switch** connects devices **within** the same network.
- A **router** connects **different networks** and directs data between them.

Together, they form the backbone of digital communication - whether that’s sending a file across the office or streaming a video from halfway around the world.
