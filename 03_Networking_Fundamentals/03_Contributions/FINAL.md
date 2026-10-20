# MINI PROJECT 3: NorthWest Architecture Studio Network 
## Networking Fundamentals: LAN and external/cloud network basics, IP addressing, protocols, and client-server architecture built and tested in Filius 

# FILIUS BUILD.

<img width="1880" height="997" alt="FILIUS PUT TOGETHER" src="https://github.com/user-attachments/assets/4f728133-2aa1-4497-bad4-bfea4be2b805" />




## *ICMP / ping*

|**ICMP / ping (Ping tests)** |
|---------------|
|A ping test is a network diagnostic tool which is used to conclude how quickly a specific host, such as a server or router responds and whether it is reachable. The ping tests above test the connectivity between the client and the server. The client being the computer sending requests to the server. These tests check whether a destination device responds over the network. These tests also show packet loss, showing if some test packets fail the receive a response.|




### *PING 1. Lan PC-to-PC*

<img width="917" height="880" alt="PING 1" src="https://github.com/user-attachments/assets/1105fea8-cb6d-4eb3-9315-5a2fa14107c4" />


### *PING 2. PC to Office Server*

<img width="923" height="881" alt="PING 2" src="https://github.com/user-attachments/assets/66d877e3-9ba5-4fad-b303-023e40e08cab" />




### *PING 3. PC to DNS Server*


<img width="905" height="875" alt="PING 3" src="https://github.com/user-attachments/assets/534fe900-18ce-4791-ab94-afa0e2ba9238" />

## *DNS*
| DNS (Domain Name System) |
|----------|
|DNS is a process where human readable domain names, such as 'domainname.com, is trasnlated into a machine-readable IP address which computers use to communicate. A short step by step can be where, if someone wants to connect to a website, the domain name will be entered into a search engine, instead of an IP address, where a DNS resolver will then translate the domain name into the IP address and return it for the PC to connect to the correct server.|





### *PING 4. Internal web by IP*

<img width="924" height="986" alt="PING 4" src="https://github.com/user-attachments/assets/f762e82d-3991-4c7d-8eb2-964faee4e9f5" />






### *PING 5. Internal web by name*


<img width="915" height="991" alt="PING 5" src="https://github.com/user-attachments/assets/d39ffe8a-ca65-4f63-b139-38496a5bebb8" />



### *PING 6. External server ping*

<img width="893" height="923" alt="PING 6" src="https://github.com/user-attachments/assets/ad4f2476-5142-43d8-bbc7-2e730825ea0d" />



### *PING 7. External web by IP*

<img width="921" height="985" alt="PING 7" src="https://github.com/user-attachments/assets/cb0562cb-2b66-4004-9b06-2a0a3234a735" />

## *IP addressing*

|IP addressing (Every device has a unique IP)|
|---------------|
| IP addresses are used by the router to forward packets between different networks and identifies its network interface and provides the location for the host in the network and supports essential functions such as resource sharing and communication across the internet. |





### *PING 8. External web by name*

<img width="927" height="959" alt="PING 8" src="https://github.com/user-attachments/assets/d30a328f-9578-46b0-92d6-2096929d2310" />



## *IP ADDRESS TABLE*

<img width="1920" height="1030" alt="FILIUS IP ADRESS TABLE  ADMIN PC" src="https://github.com/user-attachments/assets/2cbeaaed-5664-4e0c-bc8a-d25a7b9c64be" />




## *Switch vs Router*

<img width="1914" height="1000" alt="M P 3  SWITCH vs ROUTER" src="https://github.com/user-attachments/assets/e8d2ac58-8bd5-4790-985a-4822f5018701" />



### *(Office/External switch; Office Router)*
|**Switch vs Router. (Office/External Switch; Office Router**|
|---------|
| A local switch connects devices within the same LAN (local area network), whereasa router operates at the Network Layer (layer 3). The switch operates at the Data Link Layer (layer 2) and connects devices such as, computers and servers in a LAN, within the same network segment. The Router, however, directs data packets (a small, structured unit of data) based on IP addresses.     |






## *GATEWAY*
| Gateway. |
|-----------|
|A gateway is a way for a client PC to connect to the internet. For example, the IP address  192.168.10.10 sends data to the gateway 192.168.10.1 which then forwards data, for example, to a remote destination. A gateway decides the best route for transmitting packets between networks, prioritising reliability and speed. The IP address serves as a unique numeric label, for a client PC, which works together with a public IP address which is directly linked to the internet. Network Address Translation (NAT) is used in network design which allows private IP addresses to communicate with the internet by converting these private IP addresses into public ones. This allows internal devices to access external resources securely.|

## *OFFICE LAN VS EXTERNAL NETWORK*
|**LAN vs EXTERNAL NETWORK and CLIENT-SERVER MODEL**|
  |-----------------------------------------------|
  |A LAN (local area network) is a network which connects devices within a limited area, such as an office, a home, school or hospital. The Lan allows devices to communicate and share resources, such as internal systems, files and printers. The LAN allows users to share files and a single internet connection efficiently. On the other hand, external network refers to a network outside of the local network, for example, the internet or another organisations work. External networks are designed to facilitate a broader collaboration and connectivity between multiple locations and networks. The client-server model is a way in which computers or clients request services and servers provide them. This happens via a request-response communication pattern which is defined by application-layer protocols such as SQL or HTTP. To explain it a bit simpler, a device or program, called the 'client', requests information or a service and another program or device, named the 'server' provides it.|
