<p align="center">
  <img src="https://capsule-render.vercel.app/render?type=soft&color=001a0d&height=180&section=header&text=Industrial%20IT-Security%20%26%20SRA&fontSize=42&fontColor=00ff88&desc=Bielefeld%2C%20Deutschland&descSize=18&descAlignY=75&descColor=888888" width="100%" />
</p>

<p align="center">
  <b style="font-size:18px">Moin!</b> Ich entwickle sichere Fernwartungs-Infrastrukturen für den industriellen Mittelstand.<br /><br />
  Mein Fokus liegt auf der Verbindung von <b>IT-Inventarisierung</b> und <b>sicherem Remote Access</b> –<br />
  von der PKI-Zertifikatsverwaltung bis zum Hardware-Binding auf Embedded-Systemen.
</p>

---

## 🔐 Aktuelles Projekt: SRA-Dashboard

Ein **Enterprise Secure Remote Access Dashboard** für die Verwaltung von OpenVPN-Zertifikaten und Embedded-Maschinen (Exor EX707).

```
Mitarbeiter → OpenVPN (Port 1194) → Raspberry Pi 5 → OpenVPN (Port 1195) → EX707 beim Kunden
```

**Key Features:**
- 🔑 Automatisierte PKI-Zertifikatsverwaltung (2h Gültigkeit, Auto-Revoke)
- 🔒 Kryptografisches Hardware-Binding (HWID via MAC + CPU-Serial)
- 🛡️ Bedrohungserkennung (Nacht-Alarm, Reconnect-Spam, Double-IP Auto-Sperrung)
- 📊 BSI Security-Health Monitoring (TLS 1.3, CrowdSec, Fail2Ban, Audit-Log)
- 🖥️ Browser-VNC für Remote-Wartung direkt im Dashboard
- 📦 Snipe-IT Asset Management Integration

**Standards:** BSI TR-02102 · CIS Controls v8 · ISO 27001 · MITRE ATT&CK

---

## 🛠️ Tech Stack

<h3>Backend & Security</h3>
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenVPN-EA7E20?style=for-the-badge&logo=openvpn&logoColor=white" />
  <img src="https://img.shields.io/badge/argon2id-CC0000?style=for-the-badge&logo=letsencrypt&logoColor=white" />
</p>

<h3>Infrastructure & DevOps</h3>
<p align="left">
  <img src="https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=for-the-badge&logo=raspberry-pi&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" />
</p>

<h3>Security Tools</h3>
<p align="left">
  <img src="https://img.shields.io/badge/CrowdSec-4B0082?style=for-the-badge&logo=crowdsec&logoColor=white" />
  <img src="https://img.shields.io/badge/Fail2Ban-CC0000?style=for-the-badge&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/easy--rsa-PKI-006400?style=for-the-badge&logo=openssl&logoColor=white" />
  <img src="https://img.shields.io/badge/Snipe--IT-0075C2?style=for-the-badge&logo=snipeit&logoColor=white" />
</p>

<h3>Frontend</h3>
<p align="left">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/noVNC-Browser_VNC-333333?style=for-the-badge&logo=vnc&logoColor=white" />
</p>

---
graph TD
    %% Akteure und Dashboard
    Techniker((Mitarbeiter)) -- MFA Login --> Dashboard[SRA Dashboard]
    Dashboard -- API Request --> SnipeIT[(Snipe-IT Asset Mgmt)]
    

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ba9624&show_icons=true&theme=chartreuse-dark&count_private=true&hide_border=true" height="170" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=ba9624&layout=compact&theme=chartreuse-dark&hide_border=true" height="170" />
</div>

---

## 🛡️ Sicherheits-Philosophie

```
Sicherheit ist kein Feature – sie ist die Architektur.
```

- 🔐 **Zero Trust:** Jedes Gerät wird verifiziert – Zertifikat + Hardware-ID + Zeitfenster
- ⏱️ **Minimale Exposition:** Zertifikate gelten nur 2 Stunden, kein dauerhafter Zugang
- 📝 **Revisionssicherheit:** Append-only Audit-Log, unveränderbar nach BSI-Vorgaben
- 🚨 **Aktive Bedrohungserkennung:** Automatische Sperrung bei verdächtigen Aktivitäten

---

## 📫 Kontakt

<p align="left">
  📍 <b>Standort:</b> Bielefeld, NRW, Deutschland<br />
  💼 <b>LinkedIn:</b> <a href="#">Profil-Link einfügen</a><br />
  📧 <b>E-Mail:</b> E-Mail einfügen
</p>
