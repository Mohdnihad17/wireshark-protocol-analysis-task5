#  Task 5: Capture and Analyze Network Traffic Using Wireshark

##  Tools Used
- **Wireshark **
- Operating System: Windows
- Network Interface: Wi-Fi

---

##  Objective
To capture live network packets using Wireshark, identify at least 3 different protocols, and understand basic packet structures and communication over the internet.

---

##  Protocols Identified

### 1. **QUIC**
- A modern transport protocol used mainly by Google services.
- Faster than TCP and includes built-in encryption.
- **Ports:** Dynamic (UDP-based)
- **Example:**  
  - Source IP: `142.250.182.68`  
  - Destination IP: `192.168.1.6`  
  - Info: `QUIC Initial, CRYPTO, PADDING`

---

### 2. **TCP (Transmission Control Protocol)**
- Ensures reliable communication.
- Used for HTTP(S), file transfers, emails, etc.
- **Port Example:**  
  - Source IP: `192.168.1.6`  
  - Destination IP: `142.251.175.188`  
  - Info: `TCP Keep-Alive, ACK`

---

### 3. **TLSv1.2 (Transport Layer Security)**
- Used for secure communication over HTTPS.
- Encrypts the data between client and server.
- **Port:** 443
- **Example:**  
  - Source IP: `192.168.1.6`  
  - Destination IP: `103.10.124.4`  
  - Info: `TLS Application Data`

---

##  Packet Summary

- **QUIC**: Encrypted and fast communication with services like Google.
- **TCP**: Reliable transport layer connection for sessions.
- **TLSv1.2**: Secures communication over HTTPS.

---

##  Summary
Using Wireshark, I captured and analyzed live network traffic from my system. I successfully identified multiple network protocols (QUIC, TCP, TLSv1.2). This task helped me understand how protocols function across network layers and improved my skills in packet filtering and traffic inspection.

---

##  Submitted By
**Name**: Mohammed Nihad  
**Institution**: Royal College of Engineering and Technology
