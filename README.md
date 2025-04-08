#  Wireshark Home Lab Setup & Network Traffic Analysis  

###  Introduction  
This project demonstrates how to set up a **Wireshark home lab** for **network traffic analysis**.  
It includes practical **packet captures (PCAPs), network filtering techniques, and cybersecurity analysis**.

---

##  Lab Setup  
###  **Requirements:**  
 - **Kali Linux / Any Linux OS**  
 - **Wireshark Installed (`sudo apt install wireshark`)**  
 - **Virtual Machines (Windows, Metasploitable, OWASP BWA)**  
 - **Internet connection**  

###  **Installation Steps:**  ### 
- ### **1.Install Wireshark:   ```sudo apt update && sudo apt install wireshark -y```**
- ### Start Capturing Network Traffic
### **1️⃣ Open Wireshark** ###
![kali-linux-2024 4-vmware-amd64-2025-03-27-20-41-57](https://github.com/user-attachments/assets/8e7df803-0512-46b1-be7a-81f49e441b79)
- ### **2️⃣ Select your network interface (eth0 for Ethernet or wlan0 for Wi-Fi)**

- ### **3️⃣ Click Start Capture (Blue Shark Fin Icon 🦈)**
![kali-linux-2024 4-vmware-amd64-2025-03-27-20-42-24](https://github.com/user-attachments/assets/ed5e73c9-e6a9-4402-a769-0c915826b74d)
![kali-linux-2024 4-vmware-amd64-2025-03-27-20-44-31](https://github.com/user-attachments/assets/57f38ec1-da3c-4882-a8f3-d35fb3bd98d1)
### **Generate Network Traffic**

- ### **To analyze real packets, create traffic**

- ### **Open a browser and visit a website (e.g., http://example.com)**

- ### **Ping another machine (Windows/Linux)**
  
- ### **```ping -c 4 target<IP>```**
![kali-linux-2024 4-vmware-amd64-2025-03-28-13-57-53](https://github.com/user-attachments/assets/876a5cd3-8f22-4342-bbbf-fefc832e2c97)
### **Use ARP Spoofing (Kali Linux)**
![kali-linux-2024 4-vmware-amd64-2025-03-28-13-59-14](https://github.com/user-attachments/assets/8c8d4635-c932-43bf-9df9-961ae654a78e)
-  ### **Filter and Analyze Packets**
 
-  ### **Common Wireshark Filters**
 
- ### **Show only HTTP traffic**
![kali-linux-2024 4-vmware-amd64-2025-03-28-14-00-09](https://github.com/user-attachments/assets/23082d86-50e2-4424-a65d-c428ad35786b)
- ### **Show only DNS queries**
![kali-linux-2024 4-vmware-amd64-2025-03-28-14-00-30](https://github.com/user-attachments/assets/5bbdc1de-0594-415b-8bd5-6c256a983bd0)
### **Show only traffic from a specific IP**
![kali-linux-2024 4-vmware-amd64-2025-03-28-14-01-18](https://github.com/user-attachments/assets/6216ef1b-8dfd-4607-9f46-de758ac51987)
### **Save and Share Your Work**
### **1️⃣ Stop the capture**
### **2️⃣ Save the file (.pcapng)**
![kali-linux-2024 4-vmware-amd64-2025-03-28-14-38-11](https://github.com/user-attachments/assets/e39a20dc-27ae-41a8-a60b-3a202d10b08b)
![kali-linux-2024 4-vmware-amd64-2025-03-28-14-38-46](https://github.com/user-attachments/assets/2cfeda5b-3c86-4721-939c-dabf6609d7bd)

## Conclusion

**This project successfully demonstrates how to set up a Wireshark home lab for practical network traffic analysis. By capturing and analyzing real-time data packets from various activities—like web browsing, pinging, and ARP spoofing—you gain hands-on experience in:**

  - **Identifying different protocols (HTTP, DNS, ICMP, etc.)**

  - **Using Wireshark filters for targeted inspection.**

  - **Understanding packet-level details useful in threat detection and troubleshooting.**

  - **Generating and saving .pcapng files for documentation or further analysis.**

