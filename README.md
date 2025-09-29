# Wireshark-
Capturing and Analyzing packets using Wireshark.

# Traffic Capture Report

**Task:** Capture and analyze network traffic.  
**Date:** 29-09-2025  
**Tool Used:** Wireshark  

<img width="1643" height="796" alt="Screenshot 2025-09-29 114109" src="https://github.com/user-attachments/assets/c5f02ff7-0f54-44f8-99a7-14bdef3a844b" />

---

## Protocols Identified
1. **DNS**
   - Used for resolving domain names (e.g., google.com → IP).
   - Example: Query for `www.google.com`.

2. **HTTP / HTTPS**
   - Traffic observed while loading a webpage.
   - Example: TCP stream on port 443.

3. **ICMP**
   - Observed while running `ping 8.8.8.8`.
   - Request and reply packets confirmed.

---

## Sample Packet Details
- **DNS Packet**  
  - Source: 192.168.1.5  
  - Destination: 8.8.8.8  
  - Query: `www.google.com`

- **HTTP Packet**  
  - Method: GET  
  - Host: `www.google.com`

- **ICMP Packet**  
  - Type: Echo (ping) request  
  - Reply received from 8.8.8.8

<img width="695" height="415" alt="Screenshot 2025-09-29 120537" src="https://github.com/user-attachments/assets/4054d5d4-a4fb-4857-903a-b7ae4698d205" />

---

## Outcome
- Successfully captured live traffic.
- Identified multiple protocols (DNS, HTTP, ICMP).
- Learned to filter, analyze, and export `.pcap` file.


