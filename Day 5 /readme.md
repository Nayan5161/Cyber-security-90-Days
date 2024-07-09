# Cyber Internship Dairy

# Day 5: Unraveling TryHackMe and the Fundamentals of Ethical Hacking

## Exploring the TryHackMe Platform
### Today, we embarked on an exciting journey with TryHackMe, a platform that fosters cybersecurity skills through interactive learning. We created a new profile, serving as our central hub for various cybersecurity challenges and learning modules.
[Tryhackme Profile Setup](https://tryhackme.com/p/NayanGaikwad)

## **Setting Up our TryHackMe Account**
### Creating a New Profile
- 1.Sign Up: We started by signing up for a TryHackMe account. This was a straightforward process requiring an email and a password.
- 2.Profile Setup: After registration, we set up our profile, filling out necessary details and preferences.

## Diving into Beginner-Level Cybersecurity Challenges
### We ventured into the beginner-level challenges, with a particular focus on the "Basic Penetration Testing" room. This module aims to impart fundamental penetration testing skills through engaging, hands-on exercises, providing a solid foundation for aspiring cybersecurity professionals to develop their ethical hacking abilities in a safe and controlled environment.
![image](https://github.com/Nayan5161/Cyber-security-90-Days/assets/157983492/8b314751-3458-4bdf-a99a-d12a34bed3b5)


## Understanding the OWASP Top Ten Security Risks
### As part of our learning, we reviewed the OWASP Top security risks. Here is a brief explanation of each:
 #### 1.Broken Access Control:Users can access data or perform actions they shouldn't be allowed to.
 #### 2.Cryptographic Failures:Inadequate protection of sensitive data through weak encryption or poor key management.
 #### 3.Injection:Malicious data tricks the app into executing unintended commands.
 #### 4.Insecure Design:Lack of proper security measures in the design phase, leading to vulnerabilities.
 #### 5.Security Misconfiguration:Incorrectly configured security settings that expose the system to attacks.
 #### 6.Vulnerable and Outdated Components:Using software with known vulnerabilities due to outdated versions.
 #### 7.Identification and Authentication Failures:Weaknesses in the login systems that allow unauthorized access.
 #### 8.Software and Data Integrity Failures:Using untrusted software or updates that compromise data integrity.
 #### 9.Security Logging and Monitoring Failures:Inadequate logging and monitoring, making it hard to detect breaches.
 #### 10.Server-Side Request Forgery (SSRF):An attacker tricks the server into accessing internal resources.
 #### 11.Cryptographic Failures: Inadequate protection of sensitive data through weak encryption or poor key management.
 #### 12.Security Misconfiguration: Incorrectly configured security settings that expose the system to attacks.

## Exploring New Cybersecurity Tools and Concepts
## **SearchSploit**

### SearchSploit is a command-line tool included in Kali Linux, part of the Exploit Database (exploit-db.com). It aids in finding known exploits and vulnerabilities for software, essential for penetration testing. This tool is particularly useful for offline searches, making it a valuable asset for security assessments.
![image](https://github.com/Nayan5161/Cyber-security-90-Days/assets/157983492/4c5dda81-c3d7-4c32-90e2-986d9cb49c67)

## Understanding CVE and CVSS

We delved into the Common Vulnerabilities and Exposures (CVE) system and the Common Vulnerability Scoring System (CVSS) on the [NIST website](https://nvd.nist.gov/). The CVE system provides a standardized identification system for publicly known cybersecurity vulnerabilities, assigning each a unique identifier. Meanwhile, the CVSS offers a framework to assess the severity of these vulnerabilities, enabling security professionals to prioritize and address the most critical issues.

## Exploit Database
The [Exploit Database](https://www.exploit-db.com/) is another valuable resource, housing a comprehensive collection of exploits and vulnerabilities for diverse software, serving as a crucial tool for penetration testing.

## Key Techniques for Basic Penetration Testing
As we delved into the "Basic Penetration Testing" challenge on TryHackMe, we focused on three essential techniques:
1. **Brute Force**: Systematically attempting multiple passwords or keys to gain unauthorized access to a system or account.
2. **Hash Cracking**: Decoding hashed passwords to obtain the original text, which can be used to compromise secured accounts.
3. **Service Enumeration**: Identifying the services running on a target system, which can help uncover potential vulnerabilities and entry points for further exploration.

## **Hands-On Practice**
We reinforced our learning through practical exercises, applying brute force, hash cracking, and service enumeration techniques in simulated environments.

## Introducing  to Ngrok
### Downloading ngrok
We learned about ngrok, a tool that creates secure tunnels to localhost, making it accessible over the internet. Here's how to get started:

Download ngrok: Visit ngrok's download page and download the appropriate version for your operating system.
Install ngrok: Follow the installation instructions provided on the website.

## Deploying a Basic HTML Page
To begin our exploration of web application security, we created a simple index.html file with the text "I'm from the ngrok". Here is the code for the HTML file:
```
<!DOCTYPE html>
<html>
<head>
  <title>My HTML Page</title>
</head>
<body>
  <h1>I'm from the ngrok</h1>
</body>
</html>
```
## Exposing Local Servers with ngrok

1. **Run a Local Server**: Start a local web server using a command like `python -m http.server 8080`.

2. **Establish a Tunnel**: Utilize ngrok to create a secure tunnel to the local server with the command `ngrok http 8080`.

3. **Access Remotely**: ngrok generates a public URL that allows you to access your local server from the internet.

