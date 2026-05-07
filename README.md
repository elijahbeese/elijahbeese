[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=00FF41&background=000000&center=true&vCenter=true&width=700&lines=Elijah+Beese;National+Guard+Cyber+Warfare+Officer+(17A);Cybersecurity+%2B+Computer+Engineering;Building+tools+that+fight+back.)](https://git.io/typing-svg)

---

## About Me

```python
profile = {
    "name":         "Elijah Beese",
    "role":         "National Guard Cyber Warfare Officer (17A)",
    "civilian":     "Cybersecurity Engineer | AI x Security Builder",
    "location":     "Tampa, FL",
    "education":    {
        "BS":       "Cybersecurity, University of Tampa (NSA CAE-CD)",
        "MS":       "Computer Engineering, Florida International University (in progress)",
    },
    "focus":        ["Blue Team Ops", "Threat Detection", "Security Automation",
                     "AI x Security", "ICS / Critical Infra"],
    "clearance":    "Active",
    "status":       "Drilling. Building. Learning in public.",
}
```

---

## Currently Building

> **[homelab](https://github.com/elijahbeese/homelab)** — Enterprise-grade security lab built from commodity hardware. **Proxmox VE 9** hypervisor running OPNsense, Kali, and Splunk on a Dell OptiPlex; an HP ProLiant DL360 in Iowa carrying Wazuh on the heavy-lift side; a Raspberry Pi 5 doing Pi-hole + Zeek at the perimeter. Tailscale stitches it all together over apartment NAT — no port forwarding, outbound-only. Splunk is currently indexing 40k+ events shipped from Kali via Universal Forwarder. **Next up:** Wazuh stand-up on the ProLiant, then a full Active Directory lab (Server 2022 DC + Win10/11 victims) for Kerberoasting, Pass-the-Hash, and DCSync detection scenarios.

---

## The Arsenal

| Repo | What It Does | Stack |
|------|--------------|-------|
| **[homelab](https://github.com/elijahbeese/homelab)** | Multi-site security lab — attack VMs, SIEM, network monitoring, IDS, and overlay networking spanning FL and IA | `Proxmox` · `OPNsense` · `Splunk` · `Wazuh` · `Zeek` · `Tailscale` |
| **[sitrep](https://github.com/elijahbeese/sitrep)** | AI job intel platform — 9-source parallel discovery, AI scoring, recruiter recon, outreach, gap & interview prep | `Python` · `Flask` · `OpenAI` · `Hunter.io` · `Railway` |
| **[scambusters-agent](https://github.com/elijahbeese/scambusters-agent)** | Autonomous OSINT pipeline for crypto scam investigation + takedown drafting | `Python` · `GPT-4o` · `URLScan` · `WHOIS` · `Passive DNS` |
| **[lab5-vuln-mgmt](https://github.com/elijahbeese/lab5-vuln-mgmt)** | Offline ACAS/Tenable.sc-style vulnerability management toolchain for RHEL 9. OpenSCAP → SQLite → NIST 800-53 mapping. **Stdlib Python only — no pip, no internet at runtime.** Custom XLSX parser, custom HTTP server, append-only triage audit log. | `Python stdlib` · `OpenSCAP` · `SQLite` · `NIST 800-53` · `RHEL 9` |
| **[AAvsD-Sim](https://github.com/elijahbeese/AAvsD-Sim)** | RL network security simulation. **Q-Learning attacker vs Deep Q-Network defender** competing in real time across Linux network namespaces over a GRE-over-IPSec tunnel. Raw socket packet construction with `struct` — no scapy, no hping3. Built at TECO TOC. | `Python` · `numpy` · `nftables` · `GRE/IPSec` · `Q-Learning` · `DQN` |
| **[dotfiles](https://github.com/elijahbeese/dotfiles)** | Personal dev environment configs. Because muscle memory beats mouse memory. | `shell` · `config` |

---

## Certifications & Credentials

[![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-FF0000?style=for-the-badge&logo=comptia&logoColor=white)](https://www.comptia.org/certifications/security)
[![ISC2 CC](https://img.shields.io/badge/ISC2-Certified_in_Cybersecurity-006400?style=for-the-badge&logo=isc2&logoColor=white)](https://www.isc2.org/certifications/cc)
[![AWS CCP](https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/certified-cloud-practitioner/)
[![Microsoft AZ-900](https://img.shields.io/badge/Microsoft-AZ--900-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/)
[![Active Clearance](https://img.shields.io/badge/Clearance-Active-00FF41?style=for-the-badge&logo=shield&logoColor=black)](#)

---

## Education

[![UTampa](https://img.shields.io/badge/B.S._Cybersecurity-University_of_Tampa-9E1B32?style=for-the-badge&logo=academia&logoColor=white)](https://www.ut.edu/academics/sykes-college-of-business/centers-and-institutes/center-for-cybersecurity/cybersecurity-programs)
[![FIU](https://img.shields.io/badge/M.S._Computer_Engineering-Florida_International_University-081E3F?style=for-the-badge&logo=academia&logoColor=gold)](https://www.fiu.edu)
[![NSA CAE-CD](https://img.shields.io/badge/NSA-CAE--CD_Designated-003366?style=for-the-badge&logo=nsa&logoColor=white)](#)

---

## Tech Stack

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)](https://openai.com)
[![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)](https://splunk.com)
[![Wazuh](https://img.shields.io/badge/Wazuh-3578E5?style=for-the-badge&logo=wazuh&logoColor=white)](https://wazuh.com)
[![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)](https://proxmox.com)
[![OPNsense](https://img.shields.io/badge/OPNsense-D94F00?style=for-the-badge&logo=opnsense&logoColor=white)](https://opnsense.org)
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com)
[![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://azure.microsoft.com)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://kernel.org)
[![RHEL](https://img.shields.io/badge/RHEL-EE0000?style=for-the-badge&logo=redhat&logoColor=white)](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux)
[![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)](https://wireshark.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)](https://railway.app)
[![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=for-the-badge&logo=tailscale&logoColor=white)](https://tailscale.com)
[![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com)

---

## GitHub Stats

<a href="https://github.com/elijahbeese">
  <img src="https://github-readme-stats.vercel.app/api?username=elijahbeese&show_icons=true&theme=matrix&hide_border=true&bg_color=000000&title_color=00FF41&icon_color=00FF41&text_color=00FF41&ring_color=00FF41" alt="GitHub Stats" />
</a>
<a href="https://github.com/elijahbeese">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=elijahbeese&layout=compact&theme=matrix&hide_border=true&bg_color=000000&title_color=00FF41&text_color=00FF41" alt="Top Languages" />
</a>

[![GitHub Streak](https://streak-stats.demolab.com?user=elijahbeese&theme=matrix&hide_border=true&background=000000&ring=00FF41&fire=00FF41&currStreakLabel=00FF41)](https://git.io/streak-stats)

[![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=elijahbeese&bg_color=000000&color=00FF41&line=00FF41&point=00FF41&area=true&hide_border=true)](https://github.com/elijahbeese)

---

## Focus Areas

```
[##########] Blue Team Operations
[######### ] Threat Detection & SIEM
[######### ] Security Automation & AI
[########  ] Incident Response
[########  ] OSINT & Threat Intelligence
[#######   ] Vulnerability Management & Compliance
[#######   ] Network Security
[######    ] Critical Infrastructure / ICS
[#####     ] Adversarial ML & RL Security
```

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-elijah--beese-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/elijah-beese)
[![Website](https://img.shields.io/badge/Web-elijahbeese.com-00FF41?style=for-the-badge&logo=firefox&logoColor=black)](https://elijahbeese.com)

---

[![Visitor Count](https://komarev.com/ghpvc/?username=elijahbeese&color=00ff41&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/elijahbeese)

*"The best defense is knowing where to look."*
