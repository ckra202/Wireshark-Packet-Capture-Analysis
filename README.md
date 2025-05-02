# Wireshark-Packet-Capture-Analysis
This project demonstrates my ability to analyze network traffic using wireshark
# What I did
This project showcases my ability to analyze and interpret network traffic captured using Wireshark

- Captured live traffic on my VM using wireshark
- Applied filters to isolate DNS, HTTP, ICMP, TCP and ARP packets
- Inspected packet details ( source IP, destination IP, protocols..)
- Identified and analyzed key network communication patterns

# Key Protocols Analyzed
# DNS ( Domain Name System
* Filtered using DNS
* Captured a DNS query list
* Inspected a packet to view query/response structure, including queried domain and resolved IP

  # HTTP ( Hypertext Transfer Protocol)
  * Filtered using http
  * Analyzed packet headers: method (GET/POST), host, user-agent, and content length
  * Highlighted the frame size and detailed header structure
 
    # ARP (Address RResolution Protocol)
    * Filtered using arp
    * Observed ARP requests and replies on the local network
    * Identified MAC/IP relationships in clear text
   
      # TCP (transmission Control Protocol)
      * Filtered using tcp
      * Captured 3-way handshake:
      * SYN (client request)
      * SYN/ACK (server response)
      * ACK (client confirmation)
      * Demonstrated basic connection establishment in real time
     
        #ICMP (Internet Control Message Protocol)
        * Filtered using icmp
        * Captured ICMP echo requests
        * Showed how network reachability is tested


# What I learned
- How different protocols appear in raw packet form
- Practical use of Wireshark filters to isolate relevant traffic
- Skills in identifying key packet fields: such as source and destination addresses, flags, TTL, MAC/IP bindings
- Reinforced understanding of protocol behavior essential for Security+ and SOC investigations

# Tools I used 
- Wireshark
- Windows 10
- VMware (kali linux Environment)

# Screenshots
![DNS query](https://github.com/user-attachments/assets/57cf1f21-1b39-4807-ae2e-18aa6caaf495)
![icmp packet analysis](https://github.com/user-attachments/assets/3d6577bb-1a70-4283-a9bb-bf6cb7f1fed8)
![Arp packet analysis](https://github.com/user-attachments/assets/e8420484-a0b5-434a-aef9-e650b220f9a4)
![HTTP header](https://github.com/user-attachments/assets/2350f1c3-887f-488a-acfd-d64e1bb07132)
![HTTP Response packet](https://github.com/user-attachments/assets/c0eff112-3bd8-4c07-826a-bd25c3e8a86c)
![TCP](https://github.com/user-attachments/assets/553c1ca8-b784-4b9a-a9d3-b67e550edce1)
![synack packet analysis](https://github.com/user-attachments/assets/075a9fae-fb85-4452-8784-158134668bb3)

# Related Topics
* Comptia Security+
* Comptia Network+
* Soc Tier 1 Packet Analysis
* GRC understanding of data in transit



NOTE: This is part of my ongoing cybersecurity lab portfolio to demonstrate technical fluency and readiness for entry-level roles in cybersecurity.





