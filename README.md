# Cybersecurity-Portfolio - Gustaf

## About Me
Hi, I’m Gustaf (nickname: 9h0staf_), a pentester and SOC analyst based in Indonesia. I’m passionate about cybersecurity and have hands-on experience with tools like Nmap, Wireshark, and Splunk. I’m seeking remote opportunities to apply my skills in penetration testing and security operations.

- **Location**: Jakarta, Indonesia
- **Email**: syiro.digibit@gmail.com
- **Certifications**: Working toward CompTIA PenTest+ & eJPT
## Skills
- **Penetration Testing**: Network scanning (Nmap), traffic analysis (Wireshark), vulnerability assessment
- **SOC Analysis**: Log monitoring and analysis (Splunk), incident response
- **Operating Systems**: Linux (Kali, Ubuntu), Windows
- **Other**: Scripting (learning Python), virtual lab setup (VirtualBox)

## Projects
### Project 1: Network Scanning with Nmap
- **Description**: Set up a lab with Kali Linux and Metasploitable 2 to perform network reconnaissance.
- **Tools Used**: Nmap, VirtualBox
- **What I Did**:
  - Scanned Metasploitable (target IP: 192.168.56.102) using `nmap 192.168.56.102`.
  - Identified open ports: 21 (FTP), 22 (SSH), 80 (HTTP).
  - Used `nmap -sV` to find service versions, e.g., vsftpd 2.3.4 (vulnerable to backdoor).
- **Screenshots**: [Add screenshots here—see Step 3]
- **What I Learned**: How to map a network and identify potential vulnerabilities for further exploitation.

### Project 2: Traffic Analysis with Wireshark
- **Description**: Captured and analyzed network traffic in a lab environment.
- **Tools Used**: Wireshark, VirtualBox
- **What I Did**:
  - Captured traffic between Kali (192.168.56.101) and Metasploitable (192.168.56.102).
  - Generated traffic with `ping 192.168.56.101` and `curl http://192.168.56.101`.
  - Filtered for ICMP (pings) and HTTP traffic in Wireshark.
- **Screenshots**: [Add screenshots here—see Step 3]
- **What I Learned**: How to identify unencrypted traffic (e.g., HTTP) and potential security risks.

### Project 3: Log Monitoring with Splunk
- **Description**: Set up Splunk to monitor logs from a target system, simulating SOC analyst tasks.
- **Tools Used**: Splunk, VirtualBox, Ubuntu
- **What I Did**:
  - Configured Metasploitable to forward logs to Splunk (IP: 192.168.56.103).
  - Used Splunk to search logs: `sourcetype="syslog" nmap` to detect my Nmap scan.
  - Identified HTTP traffic and potential anomalies.
- **Screenshots**: [Add screenshots here—see Step 3]
- **What I Learned**: How to monitor logs for suspicious activity, a key skill for SOC roles.

## Future Projects
- Exploit vulnerabilities on Metasploitable using Metasploit (e.g., vsftpd backdoor).
- Learn web app testing with Burp Suite.
- Participate in bug bounties on HackerOne.

## Contact Me
Feel free to reach out for opportunities or collaboration:
- Email: syiro.digibit@gmail.com
- GitHub: https://github.com/9h0staf
