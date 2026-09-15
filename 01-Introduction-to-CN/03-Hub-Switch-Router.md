# Hub, Switch, and Router

Hub, Switch, and Router are network devices used to connect devices and manage communication in a network.

## 1. Hub

A **Hub** is a basic networking device that connects multiple devices in a network.

When a hub receives data, it broadcasts the data to **all connected devices**.

### Key Points

- Works mainly at the **Physical Layer (Layer 1)**.
- Does not understand MAC addresses.
- Sends data to all connected devices.
- Creates more network traffic.
- Less secure and less efficient than a switch.

---

## 2. Switch

A **Switch** connects multiple devices within a network and forwards data to the intended device.

It uses **MAC addresses** to determine where to forward the data.

### Key Points

- Works mainly at the **Data Link Layer (Layer 2)**.
- Maintains a MAC address table.
- Sends data only to the required destination port.
- Reduces unnecessary network traffic.
- More efficient than a hub.

---

## 3. Router

A **Router** connects different networks and forwards packets between them.

It uses **IP addresses** to determine the best path for forwarding packets.

### Key Points

- Works mainly at the **Network Layer (Layer 3)**.
- Uses IP addresses.
- Connects different networks.
- Determines routes for packets.
- Commonly connects a local network to the Internet.

---

## Comparison

| Feature | Hub | Switch | Router |
|---|---|---|---|
| Main Layer | Physical | Data Link | Network |
| Address Used | None | MAC Address | IP Address |
| Connects | Devices in a network | Devices in a network | Different networks |
| Data | Broadcasts to all ports | Forwards to destination port | Routes between networks |
| Efficiency | Low | High | High |

## Simple Example

Consider a college network:

- **Hub:** Sends the data to every connected computer.
- **Switch:** Sends the data to the specific computer using its MAC address.
- **Router:** Sends the data between different networks using IP addresses.

## Interview Questions

### Q1. What is the difference between a hub and a switch?

A hub broadcasts data to all connected devices, whereas a switch uses MAC addresses to forward data to the intended device.

### Q2. What is the difference between a switch and a router?

A switch primarily connects devices within the same network using MAC addresses, while a router connects different networks and forwards packets using IP addresses.

### Q3. Which layer does a hub, switch, and router work on?

- Hub → Physical Layer
- Switch → Data Link Layer
- Router → Network Layer

### Q4. Which address does a switch use?

A switch uses **MAC addresses** to forward frames.

### Q5. Which address does a router use?

A router uses **IP addresses** to route packets between networks.
