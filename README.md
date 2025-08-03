# 📡 Network Topology Simulation with Cisco Packet Tracer

## 📝 Subtitle  
*A hands-on demonstration of configuring multi-level network topologies and router-based inter-switch communication using Cisco Packet Tracer for educational and practical networking scenarios.*

---

## 📘 Overview

This repository contains the configuration details and steps for two networking tasks implemented using **Cisco Packet Tracer**. The tasks simulate real-world network setups, including a **multi-level network topology** with hubs, switches, and bridges, and a **router-based inter-switch communication** setup.

These simulations are designed to help users understand:
- Network device configurations  
- IP addressing  
- Data packet transmission  
...in an intuitive and beginner-friendly way.

---

## 📦 What’s Included

### 🔷 Task 1: Multi-Level Network Topology
- Configures a network with **8 PCs**, a **hub**, **two switches**, and a **bridge**  
- Demonstrates **data transmission** from **PC0 to PC5** through multiple network devices

### 🔶 Task 2: Router-Based Inter-Switch Communication
- Configures a network with **4 PCs**, **two switches**, and a **router**  
- Demonstrates **packet routing between two subnets** (PC0 to PC2) using a router

---

## 🛠️ Tools & Devices Used

### 🧰 Tools
- **Cisco Packet Tracer** – Network simulation and design

### 💻 End Devices
- **Task 1**: PC0–PC7  
- **Task 2**: PC0–PC3

### 🔌 Networking Devices
- Hub  
- Switches  
- Bridge  
- Router

### ⚙️ Cables
- **Copper Straight-Through**: For connecting different devices (e.g., PC to switch)  
- **Copper Crossover**: For connecting similar devices (e.g., switch to hub)

### 🌐 IP Configuration
- Static IP addressing  
- Subnet masks  
- Default gateways

---

## ✨ Features

- 🧑‍🎓 **Beginner-Friendly**: Step-by-step instructions for each setup
- 🎞️ **Visual Simulation**: Cisco Packet Tracer’s Simulation Mode to see data movement
- 🏗️ **Real-World Application**: Practical LAN and inter-subnet scenarios
- 🧪 **Customizable**: Modify devices, IPs, or topology to suit your needs
- 📚 **Educational**: Perfect for students, IT learners, or CCNA aspirants

---

## ⚙️ How It Works

### ✅ Task 1: Multi-Level Network Topology
- **Setup**: Add PCs, a hub, two switches, and a bridge. Assign IPs (e.g., 192.168.1.1–192.168.1.8).
- **Connect**: Use appropriate cables (straight-through/crossover).
- **Simulation**: Send a PDU from PC0 to PC5. Watch it traverse Hub0 → Switch1 → Bridge0 → Switch0.
- **Result**: Successful delivery confirms setup is correct.

### ✅ Task 2: Router-Based Inter-Switch Communication
- **Setup**: Configure two subnets (192.168.10.0 & 192.168.20.0) with PCs, switches, and a router.
- **Router Config**: Assign IPs to FastEthernet0/0 and FastEthernet1/0 for routing.
- **Simulation**: Send a PDU from PC0 to PC2 through Switch0 → Router0 → Switch1.
- **Result**: Packet arrives successfully, confirming router functionality between subnets.

---

## ❓ Why Use This Project?

- 🧠 Learn the basics of IP addressing, subnetting, device roles
- 🧪 Hands-on lab experience in a virtual, risk-free environment
- 📈 Scalable for larger, more complex scenarios
- 🧩 Engaging visual feedback through simulation
- 🎓 Useful for CCNA certification prep or general IT networking education

---

## Screenshots
<img width="1430" height="805" alt="Image" src="https://github.com/user-attachments/assets/e04274ec-39dc-4e0f-b642-a75fb0cb421b" />

<img width="624" height="351" alt="Image" src="https://github.com/user-attachments/assets/75cd7eb6-7203-4a1e-b6bd-466c5a991485" />
