# NETWORKWALKS-Zaharan-Siaka-B084-WK2-PM1-CYBERSECURITY-FOOTPRINTING


## WEEK 2 PENETRATION TESTING REPORT
## Networkwalks Cybersecurity Internship – Batch B084

**Project:** Footprinting and Network Scanning  
**Participant:** Siaka Zaharan Onoruoiza  
**Week:** 2  
**Modules:** PM1 – Footprinting and PM5 – Zenmap

---

## 1. Liability Disclaimer

This report documents cybersecurity practical exercises conducted for educational purposes as part of the Networkwalks Cybersecurity Internship. Activities were performed within the scope of the assigned exercises and authorized network environment.

No unauthorized access or exploitation was attempted.

## 2. Introduction

The purpose of this project was to gain practical experience in information gathering, network footprinting, host discovery and network topology visualization.

Two practical modules were completed: PM1, which involved using multiple footprinting tools, and PM5, which involved network scanning with Zenmap.

## 3. Tools Used

### PM1 – Footprinting
- WHOIS – Domain registration information.
- WhatWeb – Website technology identification.
- NSLookup – DNS information lookup.
- cURL – HTTP response header inspection.
- WAFW00F – Web Application Firewall detection.
- DNSRecon – DNS reconnaissance.

### PM5 – Network Scanning
- Zenmap – Graphical interface for Nmap network scanning.

## 4. Activities Performed

### 4.1 Footprinting (PM1)

The following commands were used during the footprinting exercise:

```bash
whois networkwalks.com
whatweb networkwalks.com
nslookup networkwalks.com
curl -I https://networkwalks.com
wafw00f networkwalks.com
dnsrecon -d networkwalks.com
```

The tools were used to gather domain registration information, identify website technologies, inspect DNS records, review HTTP headers and check for web application firewall indicators.

Screenshots and text outputs were saved as evidence.

### 4.2 Zenmap Network Scanning (PM5)

Zenmap was used in Kali Linux to perform host discovery on an authorized local network.

**Command syntax:**

```bash
nmap -sn <authorized-network-range>
```

The scan reported 28 hosts up out of 256 addresses. The topology diagram displayed 30 IP-address entries.

The scan results and topology diagram were reviewed and saved as evidence.

## 5. Risk Analysis / Impact

Information gathered during footprinting can help security professionals understand a website's publicly available information and technologies.

Network discovery can also reveal active devices within a network.

If such information is exposed or improperly handled, it may increase an organization's exposure to reconnaissance and security risks.

This exercise focused on identifying and understanding information, not exploiting vulnerabilities.

## 6. Recommendations

- Regularly review publicly available domain information.
- Keep website technologies and software updated.
- Review DNS configurations for unnecessary information exposure.
- Use appropriate web application security controls.
- Monitor network devices and maintain an updated network inventory.
- Protect private network information when sharing evidence publicly.

## 7. Conclusion

The Week 2 exercises provided practical experience with footprinting tools and Zenmap.

I learned how to gather domain information, inspect website technologies, examine DNS information, review HTTP headers and perform network host discovery.

The exercises also improved my understanding of documenting technical activities and handling cybersecurity evidence responsibly.

## 8. Evidences Collected

The following evidence is available in this repository:

### PM1 – Footprinting
- Six text output files.
- Screenshots of the footprinting activities.

### PM5 – Zenmap
- Zenmap topology PDF (redacted copy for public sharing).
- PM5 README documenting the exercise.

**Note:** The original topology PDF is retained privately. Individual Zenmap scan screenshots were not saved.

---

**End of Report**
