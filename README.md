# Network-Reconnaisance-and-Scanning

## 🧠 Skills Learned
- **WHOIS Lookup:** Mastered the technique of conducting WHOIS lookups to gather crucial network information, including ownership details and registration status.
- **Masscan Port Scanning:** Acquired proficiency in using Masscan for efficient and rapid port scanning, enabling the identification of open ports across large IP ranges.
- **Accessing IP Addresses:** Learned methods to access IP addresses with open ports, facilitating further analysis and potential exploitation.
- **Shodan.io Reconnaissance:** Explored the capabilities of Shodan.io for comprehensive reconnaissance, including device enumeration, service identification, and vulnerability assessment.

## 👀 Observations
- **Efficiency of Masscan:** Noticed the remarkable speed and accuracy of Masscan in scanning a wide range of ports, aiding in the swift detection of potential entry points.
- **Insight from Shodan.io:** Appreciated the depth of insight provided by Shodan.io, particularly in understanding the exposed services, geographical distribution, and potential security risks associated with target IP addresses.
- **Importance of WHOIS Lookups:** Recognized the importance of WHOIS lookups in understanding the organizational structure, ownership details, and registration history of target domains, aiding in the formulation of targeted attack strategies.
- **Challenges in Accessing IP Addresses:** Encountered challenges in accessing IP addresses with open ports, highlighting the importance of proper authentication and authorization mechanisms to prevent unauthorized access and exploitation.


# Network Reconnaisance
![https://i.imgur.com/SQrGAYa.png](https://i.imgur.com/SQrGAYa.png)
<p align="center"><em>Figure 1: https://www.sans.org/robots.txt</em></p>

![https://i.imgur.com/KyhF4ep.png](https://i.imgur.com/KyhF4ep.png)
<p align="center"><em>Figure 1.1: Found the admin page</em></p>

![https://i.imgur.com/vi3c8ER.png](https://i.imgur.com/vi3c8ER.png)
<p align="center"><em>Figure 1.2: wayback machine 1997 capture of sans.org website</em></p>

![https://i.imgur.com/P2UaF1R.png](https://i.imgur.com/P2UaF1R.png)
<p align="center"><em>Figure 1.3: ICANN Lookup of sans.org website</em></p>


# Network Scanning
![https://i.imgur.com/oOGoTlK.png](https://i.imgur.com/oOGoTlK.png)
<p align="center"><em>Figure 2: whois 122.248.192.0/18 / Country: Singapore</em></p>

![https://i.imgur.com/6hl3fet.png](https://i.imgur.com/6hl3fet.png)
<p align="center"><em>Figure 2.1: whois 122.248.192.0/18 / more information</em></p>

![https://i.imgur.com/gGYCB0f.png](https://i.imgur.com/gGYCB0f.png)
<p align="center"><em>Figure 2.2: sudo masscan -p80,443,445 122.248.192.0/18</em></p>

![https://i.imgur.com/ekl0iYm.png](https://i.imgur.com/ekl0iYm.png)
<p align="center"><em>Figure 2.3: https://122.248.246.195/</em></p>

![https://i.imgur.com/KXBMDPv.png](https://i.imgur.com/KXBMDPv.png)
<p align="center"><em>Figure 2.4: https://122.248.215.171/</em></p>

![https://i.imgur.com/luSdpi6.png](https://i.imgur.com/luSdpi6.png)
<p align="center"><em>Figure 2.5: shodan.io scan on IP Address: 122.248.227.148 </em></p>
