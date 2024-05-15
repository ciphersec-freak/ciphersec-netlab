CipherSec-Netlab for Kali Linux OS

CipherSec-Netlab is a versatile toolkit tailored for networking and network hacking scenarios, specifically designed for Kali Linux OS. Featuring a collection of Python scripts, CipherSec-Netlab empowers users with diverse network functionalities, facilitating exploration, analysis, and security testing. Harnessing popular Python libraries such as subprocess, os, time, scapy, socket, random, fcntl, and struct, CipherSec-Netlab offers a comprehensive suite of tools to address various networking challenges.

Installation Instructions(Requires root permissions - sudo su):

```
$ apt update -y && apt upgrade -y
$ pkg install git
$ pkg install figlet
$ apt install lolcat
$ apt install python
$ apt-get install macchanger
$ apt-get install tor torsocks   //if it throw error kindly manually install the torsock from this link :- https://gitlab.torproject.org/tpo/core/torsocks
$ apt-get install tcpdump
$ git clone https://github.com/ciphersec-freak/ciphersec-netlab.git
$ cd ciphersec-netlab
$ pip install scapy
$ git pull
$ python ciphersec_netlab.py
```

---

### Tool Functionalities:

---

1. MAC Address Spoofing
   - unctionality: Enhances anonymity and security by allowing users to change the MAC address of a network interface to any desired MAC address.

---

2. Tor Routing
   - Functionality:Routes network connections through the Tor network, ensuring enhanced privacy and security in communication.

---

3. ARP Spoofing
   - Functionality: Executes ARP spoofing attacks, enabling interception of network traffic or redirection of network connections for various purposes.

---

4. Deauthentication
   - Functionality: Sends deauthentication packets to target access points or clients, effectively disconnecting them from the network.

---

5. Network Device Discovery
   - Functionality:Discovers connected devices within a network, providing information such as IP and MAC addresses along with device names.

---

6. HTTP Traffic Sniffing
   - Functionality: Captures and analyzes HTTP packets within a network, facilitating further analysis or security testing.

---

7. UDP Flood Attack
   - Functionality: Performs a UDP flood attack by sending a large number of UDP packets to overwhelm the target, causing denial of service.
 
---

8. Scan IP Range
   - Functionality: Scans a range of IP addresses to identify active hosts using ICMP ping requests.

---
![ciphersec-netlab](https://github.com/ciphersec-freak/ciphersec-netlab/assets/77842676/eb9bda86-0d08-4c5f-b17b-d114f1d379ef)




### Overview:

CipherSec-Netlab presents a comprehensive array of network functionalities vital for exploration, analysis, and security testing across diverse network environments. Whether you are a network administrator, security researcher, or ethical hacker, CipherSec-Netlab equips you with the necessary tools to perform network-related tasks effectively in your daily activities.
