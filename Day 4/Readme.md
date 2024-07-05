# Welcome back to my Cyber Security Internship Diary 

# Day4: Nmap and Network Scanning

Today's session was focused on the topic of network scanning using the powerful tool Nmap. We covered a variety of related concepts and explored essential Nmap commands. Additionally, we performed a practical example by scanning the website ```sppu.ac.in```

## The key topics discussed include:

### 1. Nmap Overview
Nmap (Network Mapper) is a free and open-source utility for network discovery and security auditing. It can be used to identify hosts and services on a network, perform port scanning, detect operating systems, and more.

### 2. Reconnaissance and OSINT
Reconnaissance, or gathering information about a target, is the first step in ethical hacking. This can involve Open Source Intelligence (OSINT) techniques to collect data from publicly available sources.

### 3. IDS and IPS
We also discussed the concepts of Intrusion Detection Systems (IDS) and Intrusion Prevention Systems (IPS). These systems monitor network traffic and can potentially detect and block network scanning activities.

### 4. Practical Example: Scanning sppu.ac.in
During the session, we performed a practical example by scanning the website sppu.ac.in using Nmap. This allowed us to gain insights into the target network and the services running on it.

# Practical Example
## We used Nmap to scan ```sppu.ac.in``` with the following command:
```
sudo nmap -Pn -p21,22,53,80,81,8080 -sV oN test.txt sppu.ac.in
Starting Nmap 7.94SVN ( https://nmap.org ) at 2024-07-05 02:07 EDT
Nmap scan report for sspu.ac.in (52.1.201.23)
Host is up (0.48s latency).
rDNS record for 52.1.201.23: ec2-52-1-201-23.compute-1.amazonaws.com

PORT     STATE    SERVICE    VERSION
21/tcp   filtered ftp
22/tcp   filtered ssh
53/tcp   filtered domain
80/tcp   open     http       Microsoft IIS httpd 8.5
81/tcp   filtered hosts2-ns
8080/tcp filtered http-proxy
Service Info: OS: Windows; CPE: cpe:/o:microsoft:windows

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
```
Nmap done: 1 IP address (1 host up) scanned in 17.53 seconds 


# Detailed Anylasis

## Key Concepts Explained

1. **Reconnaissance (Recon):**
   - Definition: Gathering preliminary data on a target.
   - Example: Using Nmap to identify open ports on a target system.

2. **Open-Source Intelligence (OSINT):**
   - Definition: Collecting publicly available information about a target.
   - Example: Using Google to find information about a target organization or individual.

3. **Intrusion Detection System (IDS) and Intrusion Prevention System (IPS):**
   - IDS Example: Snort, a popular open-source IDS.
   - IPS Example: Cisco Firepower, a commercial IPS solution.

4. **Why Not to Ping:**
   - Reason: Pinging a target can alert IDS/IPS systems, potentially leading to blocking or tracking of the source IP address.
   - Diagram: Illustrating the difference between a subtle TCP scan and a more obvious ping.

5. **Service Detection Flowchart:**
   - Nmap can be used to perform service detection, which involves identifying the services running on open ports.
   - The flowchart demonstrates the process of service detection, including TCP/UDP port scanning, version detection, and vulnerability identification.

6. **Scanning:**
   - Scanning involves using tools like Nmap to gather information about a target network or system.
   ![image](https://github.com/Nayan5161/Cyber-security-90-Days/assets/157983492/5426fb92-2723-43f7-8c92-a811f623c808)

   - This can include viewing the headers sent by the server in response to various scan types.

7. **Wafw00f:**
   - Wafw00f is a tool used to identify the web application firewall (WAF) service used by a website.
   - By analyzing the website's responses, Wafw00f can detect the presence and type of WAF, which is valuable information for planning further attacks or testing the effectiveness of the firewall.
   ![image](https://github.com/Nayan5161/Cyber-security-90-Days/assets/157983492/603f5767-673e-403b-85bf-ae728919f60a)


