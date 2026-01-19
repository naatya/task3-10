# task3-10
Networking Basics for Cyber Security

Networking Fundamentals: Wireshark Analysis Summary

**1. Core Concepts**

I learned that an IP Address acts as a digital mailing address, while a MAC Address is a permanent hardware ID. I also understood that DNS acts as the internet's phonebook, translating website names into IP addresses.

**2. Traffic Capture**

I successfully installed Wireshark and identified my active network interface (Wi-Fi/Ethernet). I learned how to start a live capture to monitor the data packets entering and leaving my computer.

**3. Using Filters**

I practiced using Display Filters to manage large amounts of data. By typing commands like http, dns, or tcp, I was able to isolate specific types of traffic.

**4. TCP Three-Way Handshake**

I observed the connection process between my PC and a server. I identified the SYN, SYN-ACK, and ACK sequence, which is the "handshake" required to establish a reliable connection.

**5. Plain-Text vs. Encryption**

I compared two types of web traffic:

**HTTP**: I observed that data is sent in plain-text and can be easily read using "Follow TCP Stream."

**HTTPS (TLS**): I saw that modern traffic is encrypted, appearing as unreadable random characters to protect user privacy.

**6. DNS Analysis**

I captured DNS Queries and Responses. I observed my computer asking for a website's IP address and the DNS server providing the correct destination IP.

**7. Saving Files**

I learned how to stop a capture and save the data as a .pcapng file. This allows me to store the network logs for future troubleshooting or security analysis.

**8. Conclusion**

This project demonstrated how data moves across a network and highlighted the critical importance of encryption (HTTPS) in keeping our online information secure.
