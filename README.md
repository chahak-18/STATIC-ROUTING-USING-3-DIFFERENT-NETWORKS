# 🛰️ Static Routing Simulation – Cisco Packet Tracer

## 📌 Project Overview
This project demonstrates how to set up a **static routing network** using **Cisco Packet Tracer**. The simulation involves **three routers** connected in a **triangular topology**, with each router linked to its own **LAN network** (two PCs per LAN).

The main goal is to configure **static routes** manually and ensure that all networks can communicate with each other. We’ve also added **redundant routes** to ensure the network remains functional even if one connection goes down ✅.

---

## 🗺️ Network Topology
- **Router0** → **Network A**: `192.168.10.0/24` 🖥️🖥️  
- **Router1** → **Network B**: `192.168.11.0/24` 🖥️🖥️  
- **Router2** → **Network C**: `192.168.12.0/24` 🖥️🖥️  

🔄 All routers are connected via **serial links** in a triangle, allowing multiple routing paths and redundancy.

---

## 💡 Features & Skills Practiced
- 🧠 Static routing configuration  
- 🧮 IP addressing & subnet planning  
- 🔌 Serial interface setup with clock rate  
- 🚧 Routing redundancy & fault tolerance  
- 🛠️ Troubleshooting and testing connectivity  

---

## 🛠️ Tools Used
- 🧰 **Cisco Packet Tracer**

---

## 🚀 How to Run the Simulation
1. 📂 Open the `.pkt` file in **Cisco Packet Tracer**.
2. 💻 Access each router’s CLI and verify static routes using:
3. 🧪 Perform **ping tests** between PCs across different networks.
4. 🔁 Test **redundancy**:
- Disable a serial link between two routers.
- Ping again and ensure packets take the alternate route.

---

## 🎯 Learning Outcomes
By completing this project, you will:
- Understand how **static routing** works 🧭
- Gain hands-on experience with **router configuration**  
- Learn to build **resilient and fault-tolerant networks**  
- Practice **real-world troubleshooting techniques** 🔍

---

## 👤 Author
**Your Name**  
📅 *Date of Completion: [Insert Date]*  
