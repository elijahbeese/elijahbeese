[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=00FF41&background=000000&center=true&vCenter=true&width=700&lines=Elijah+Beese;National+Guard+Cyber+Warfare+Officer+(17A);Cybersecurity+Engineer+%40+Textron+Systems;Building+my+own+AI+on+hardware+I+set+up+myself.)](https://git.io/typing-svg)

---

## About Me

```python
profile = {
    "name":         "Elijah Beese",
    "role":         "Cyber Warfare Officer (17A), Vermont Army National Guard",
    "civilian":     "Cybersecurity Engineer @ Textron Systems | AI x Security Builder",
    "location":     "Baltimore, MD",
    "education":    {
        "BS":       "Cybersecurity, University of Tampa (NSA CAE-CD)",
        "MS":       "Computer Engineering, Florida International University (in progress)",
    },
    "focus":        ["Blue Team Ops", "AI x Security", "Homelab Infrastructure",
                     "Applied ML", "Network Defense"],
    "status":       "Drilling. Building. Fine-tuning my own AI on hardware I set up myself.",
}
```

---

## Currently Building

> **[D.A.V.E.](https://github.com/elijahbeese/dave-web)** -- a self-hosted, LoRA fine-tuned AI assistant running on hardware I set up myself. Llama 3.1 8B served through **Ollama**, retrained nightly on real conversations through a full pipeline (distill -> judge -> train -> eval -> promote only if it actually scores better, never auto-promoted blind). Persistent memory is split between structured facts and embedded conversation history, so it genuinely remembers past exchanges instead of starting cold every session. A password+MFA-walled dashboard ([dave-web](https://github.com/elijahbeese/dave-web)) sits on top with live vulnerability intel ([threatwatch](https://github.com/elijahbeese/dave-web/tree/main/threatwatch): CISA KEV, NVD, MITRE ATT&CK, vendor feeds), a personal Reddit/X brief ([pulse](https://github.com/elijahbeese/pulse)), and D.A.V.E.-written daily summaries with follow-up chat on every brief. Storage backend is a **Dell PowerVault NX3200** running **TrueNAS SCALE**, RAIDZ1 across 4 drives, ZFS end to end. Currently extending it with computer vision -- a PoE door camera and a pan-tilt window camera feeding into the same Pi -- so it can actually see what's happening, not just answer what it's asked.

---

## The Arsenal

| Repo | What It Does | Stack |
|------|--------------|-------|
| **[D.A.V.E.](https://github.com/elijahbeese/dave-web)** | Self-hosted, LoRA fine-tuned AI assistant with a nightly automated retraining pipeline, persistent memory, email + web access, and an in-progress computer vision extension | `Python` · `Llama 3.1` · `Ollama` · `LoRA` · `ChromaDB` · `TrueNAS/ZFS` |
| **[dave-web](https://github.com/elijahbeese/dave-web)** | Password+MFA-walled dashboard/chat frontend onto D.A.V.E. -- live threatwatch dashboard, zero-day tracking, daily LLM-generated briefs with clickable follow-up chat, exposed only via Tailscale Funnel | `Python` · `Flask` · `gunicorn` · `SQLite` · `Tailscale Funnel` |
| **[pulse](https://github.com/elijahbeese/pulse)** | Manual-pull-only Reddit + X collector feeding dave-web's Pulse brief -- real metered API calls only on demand, never scheduled | `Python` · `PRAW` · `X API v2` |
| **[homelab](https://github.com/elijahbeese/homelab)** | Segmented home network and server infrastructure -- FortiGate firewall, VLAN-isolated zones, multiple rack servers, ZFS storage, and a dedicated GPU box for AI training | `FortiGate` · `TrueNAS/ZFS` · `VLAN` · `Ollama` · `Tailscale` |
| **[sitrep](https://github.com/elijahbeese/sitrep)** | AI job intel platform -- 9-source parallel discovery, AI scoring, recruiter recon, outreach, gap & interview prep | `Python` · `Flask` · `OpenAI` · `Hunter.io` · `Railway` |
| **[scambusters-agent](https://github.com/elijahbeese/scambusters-agent)** | Autonomous OSINT pipeline for crypto scam investigation + takedown drafting | `Python` · `GPT-4o` · `URLScan` · `WHOIS` · `Passive DNS` |
| **[lab5-vuln-mgmt](https://github.com/elijahbeese/lab5-vuln-mgmt)** | Offline ACAS/Tenable.sc-style vulnerability management toolchain for RHEL 9. OpenSCAP -> SQLite -> NIST 800-53 mapping. **Stdlib Python only -- no pip, no internet at runtime.** | `Python stdlib` · `OpenSCAP` · `SQLite` · `NIST 800-53` · `RHEL 9` |
| **[AAvsD-Sim](https://github.com/elijahbeese/AAvsD-Sim)** | RL network security simulation. **Q-Learning attacker vs Deep Q-Network defender** competing in real time across Linux network namespaces over a GRE-over-IPSec tunnel. | `Python` · `numpy` · `nftables` · `GRE/IPSec` · `Q-Learning` · `DQN` |
| **[dotfiles](https://github.com/elijahbeese/dotfiles)** | Personal dev environment configs. Because muscle memory beats mouse memory. | `shell` · `config` |

---

## Certifications & Credentials

[![CompTIA Security+](https://img.shields.io/badge/CompTIA-Security%2B-FF0000?style=for-the-badge&logo=comptia&logoColor=white)](https://www.comptia.org/certifications/security)
[![ISC2 CC](https://img.shields.io/badge/ISC2-Certified_in_Cybersecurity-006400?style=for-the-badge&logo=isc2&logoColor=white)](https://www.isc2.org/certifications/cc)
[![AWS CCP](https://img.shields.io/badge/AWS-Cloud_Practitioner-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com/certification/certified-cloud-practitioner/)
[![Microsoft AZ-900](https://img.shields.io/badge/Microsoft-AZ--900-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/)
[![OSCP](https://img.shields.io/badge/OSCP-In_Progress-000000?style=for-the-badge&logo=offensive-security&logoColor=white)](#)
[![Active Clearance](https://img.shields.io/badge/Clearance-Active_TS%2FSCI-00FF41?style=for-the-badge&logo=shield&logoColor=black)](#)

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
[![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)](https://ollama.com)
[![TrueNAS](https://img.shields.io/badge/TrueNAS-0095D5?style=for-the-badge&logo=truenas&logoColor=white)](https://truenas.com)
[![Fortinet](https://img.shields.io/badge/FortiGate-EE3124?style=for-the-badge&logo=fortinet&logoColor=white)](https://fortinet.com)
[![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)](https://splunk.com)
[![Wazuh](https://img.shields.io/badge/Wazuh-3578E5?style=for-the-badge&logo=wazuh&logoColor=white)](https://wazuh.com)
[![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)](https://aws.amazon.com)
[![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://azure.microsoft.com)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://kernel.org)
[![RHEL](https://img.shields.io/badge/RHEL-EE0000?style=for-the-badge&logo=redhat&logoColor=white)](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux)
[![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)](https://wireshark.org)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
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
[######### ] AI x Security / LLM Infrastructure
[######### ] Threat Detection & SIEM
[########  ] Security Automation
[########  ] Network Segmentation & Defense
[#######   ] OSINT & Threat Intelligence
[#######   ] Vulnerability Management & Compliance
[######    ] Incident Response
[#####     ] Adversarial ML & RL Security
```

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-elijah--beese-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/elijah-beese)
[![Website](https://img.shields.io/badge/Web-elijahbeese.com-00FF41?style=for-the-badge&logo=firefox&logoColor=black)](https://elijahbeese.com)

---

[![Visitor Count](https://komarev.com/ghpvc/?username=elijahbeese&color=00ff41&style=for-the-badge&label=PROFILE+VIEWS)](https://github.com/elijahbeese)

*"The best defense is knowing where to look."*
