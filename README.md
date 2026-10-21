
<!-- ANIMATED PROFILE -->

<div align="center">

<img src="./contrib-heatmap.svg" width="100%" alt="Shiva's animated GitHub contributions" />

<br>

<table>
  <tr>
    <td width="50%" align="center" valign="top">
      <img src="./shiva-ascii.svg" width="100%" alt="Shiva Sathvik ASCII portrait" />
    </td>
    <td width="50%" align="center" valign="top">
      <img src="./stats.svg" width="100%" alt="Shiva's GitHub statistics" />
    </td>
  </tr>
</table>

</div>

<!-- END ANIMATED PROFILE -->

# Shiva Sathvik

**Software engineering · Security · Systems**

<sub>Computer Science undergraduate · Class of 2027 · Hyderabad, India</sub>

I build software to understand what happens beneath the interface: how data moves, where trust boundaries sit, and what a system does when things go wrong.

My work spans Python and TypeScript applications, applied security, and Linux systems. Lately, I've been spending more time on encryption, detection engineering, and tools that make complex behavior easier to inspect.

[GitHub](https://github.com/shivasathvik44) · [Email](mailto:posanishiva6@gmail.com)

---

## Selected work

### 01 / [VaultSync](https://github.com/shivasathvik44/pswdMngr)

**A password manager built around client-side encryption.**

A self-hosted project with a FastAPI backend, a Fedora desktop client, and a native Android client. The central design decision is to separate account authentication from the password that protects the vault.

- Uses **Argon2id**, **AES-256-GCM**, and key wrapping to protect encrypted vault records.
- Implements account sessions, encrypted-record APIs, and synchronization infrastructure.
- Builds toward offline access and cross-device workflows with **PySide6** and **Kotlin** clients.

`Python` · `FastAPI` · `PySide6` · `Kotlin` · `SQLite` · `Cryptography`

[Explore the code and architecture →](https://github.com/shivasathvik44/pswdMngr)

<sub>Active development · Android device validation and end-to-end synchronization testing are ongoing.</sub>

---

### 02 / [SentinelForge](https://github.com/shivasathvik44/SOC-PROJECT)

**From Linux activity to security incidents you can investigate.**

A self-hosted security operations platform that collects host telemetry, detects suspicious behavior, and turns related alerts into incident timelines with supporting evidence.

- Normalizes Linux authentication logs and **eBPF** process/network telemetry.
- Maps detections to **MITRE ATT&CK** and correlates alerts into incidents.
- Includes an investigation dashboard, human-approved containment actions, and synthetic detection validation.

`Python` · `Linux` · `eBPF` · `SQLite` · `Detection Engineering`

[Explore the project →](https://github.com/shivasathvik44/SOC-PROJECT)

---

### 03 / [URL-PD](https://github.com/shivasathvik44/URL-PD)

**Phishing URL detection with reasons, not just a score.**

A layered URL-analysis tool that combines quick structural checks, domain intelligence, machine learning, and optional page-content analysis to explain why a URL may be suspicious.

- Examines URL structure alongside **DNS, RDAP/WHOIS, and TLS** signals.
- Uses a **Random Forest** classifier, with optional local LLM-assisted analysis.
- Produces evidence-based results, including an **uncertain** outcome when signals are inconclusive.

`Python` · `Machine Learning` · `DNS` · `TLS` · `Threat Analysis`

[Explore the project →](https://github.com/shivasathvik44/URL-PD)

---

## Other work

**[CyberShield](https://github.com/shivasathvik44/cybershield44)** — A full-stack security dashboard for vulnerability intelligence, IP reputation checks, and threat investigation. `React` · `TypeScript` · `Node.js` · `PostgreSQL`

**[AFOW](https://github.com/shivasathvik44/AFOW)** — A Python file organizer with dry-run previews, undo support, and collision-safe handling. `Python` · `Flask` · `Pytest`

---

## Toolbox

| Area | Technologies |
| :--- | :--- |
| **Languages** | Python, TypeScript, JavaScript, C, C++, Bash |
| **Applications** | FastAPI, React, Node.js, Express, Flask, PySide6 |
| **Data** | SQLite, PostgreSQL |
| **Systems & workflow** | Fedora Linux, Docker, Git, GitHub Actions, Pytest |
| **Security** | Authentication, applied cryptography, network analysis, threat detection |

## Currently exploring

Linux internals, networking, systems programming, and lower-level observability. I'm interested in the boundary between building a system and understanding whether it behaves the way we think it does.

---

<sub>Build. Break. Understand. Secure.</sub>

<sub>[GitHub](https://github.com/shivasathvik44) · [Get in touch](mailto:posanishiva6@gmail.com)</sub>
