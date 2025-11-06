#  RIPv2 Routing Protocol Lab

This project demonstrates the implementation of **RIPv2 (Routing Information Protocol version 2)** in **Cisco Packet Tracer**.  
The goal of this lab was to understand how RIPv2 enables routers to exchange routing information dynamically in a **classless** network environment.

---

##  **Project Overview**

I built a small topology with **three routers** and **three LANs** to simulate a real-world multi-network environment.  
The focus was on configuring RIPv2, verifying route propagation, and testing connectivity across all networks.

---

##  **Key Configurations**

- **RIPv2 (Classless)** with **no auto-summary**  
- Configured all relevant networks under the RIPv2 routing process  
- Verified learned routes using `show ip route` (routes marked with “R”)  
- Successfully tested end-to-end connectivity using **ping**
- Successfully verified that protocol is implemented by ' show ip protocols '. 
---

##  **Learning Outcomes**

Through this lab, I learned:
- How RIPv2 exchanges routing information dynamically.  
- The difference between **classful** and **classless** routing.  
- How to verify and troubleshoot RIP configurations using show commands.  
- How disabling auto-summary ensures correct route advertisement in discontiguous networks.

---

##  **Tools Used**

- Cisco Packet Tracer  
- Routers, Switches, and PCs  

---

##  **How to Use**

1. Download the `.pkt` file from this repository.  
2. Open it using **Cisco Packet Tracer**.  
3. View router configurations and test connectivity between LANs.  


---

##  **About This Project**

This lab was created as part of my ongoing **CCNA learning journey** to practice and understand **dynamic routing protocols** like RIPv2.  
It helped me visualize how routers share routes automatically and maintain up-to-date routing tables.

---
