<!-- Terminal theme, matching nazibullahnoyon.me: ink #050806 · signal #39ff88 · alert #ff3b5c · warn #ffcc00 · trace #00e5ff -->

<p align="center">
  <img src="./assets/hero.svg" width="100%" alt="Nazibullah Noyon — ethical hacker and software engineer"/>
</p>

<p align="center">
  <a href="https://nazibullahnoyon.me">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2400&pause=1100&color=39FF88&center=true&vCenter=true&width=700&lines=root%40noyon%3A~%24+whoami;%3E+I+break+systems+to+secure+them%2C+and+build+the+apps.;%3E+Think+like+an+attacker.+Build+like+an+engineer.;%3E+Authorized+scope.+Responsible+disclosure.+Always." alt="Terminal intro"/>
  </a>
</p>

<p align="center">
  <a href="https://nazibullahnoyon.me"><img src="https://img.shields.io/badge/%E2%96%B8%20portfolio-nazibullahnoyon.me-39ff88?style=for-the-badge&labelColor=050806" alt="Portfolio"/></a>
  <a href="https://nazibullahnoyon.me/case-study"><img src="https://img.shields.io/badge/%E2%96%B8%20case%20files-5-00e5ff?style=for-the-badge&labelColor=050806" alt="Case studies"/></a>
  <img src="https://img.shields.io/badge/%E2%96%B8%20status-white%20hat-ffcc00?style=for-the-badge&labelColor=050806" alt="White hat"/>
</p>

---

### `$ cat ./profile.txt`

```bash
name        : Nazibullah Noyon
role        : Cyber Security Researcher & Software Engineer
base        : Gazipur, Bangladesh  (UTC+06:00)
focus       : vulnerabilities · malware analysis · zero-days · ML-based defence
builds      : 35+ cross-platform apps live on Google Play & App Store
stack       : Flutter client  <->  NestJS / Firebase backend
team        : leading 14 engineers @ ScaleUp Ads Agency
thesis      : ML network intrusion detection — 98% accuracy (XGBoost, RF)
alignment   : white hat — every test authorised, every finding reported
```

---

### `$ cat ./mindset.md`

> **Attackers only need one gap. Defenders need to understand all of them.**
> I study how systems break so I can build ones that don't — and I write the apps myself, so I know where the weak seams hide.

| Phase | Hacker's mind | Engineer's discipline |
|---|---|---|
| 🔎 **Recon** | Map every input, endpoint and assumption | Know the architecture before writing a line |
| 🧪 **Probe** | Ask *"what if this is wrong?"* — then test it | Unit, widget, integration and golden tests |
| 🔐 **Harden** | Close the gap, then look for the next one | Auth guards, token refresh, secure storage |
| 📝 **Report** | Clear, reproducible, responsibly disclosed | Code review standards for a 14-person team |
| 🔁 **Repeat** | Curiosity doesn't clock out | CI/CD — 6 releases a month, 99% crash-free |

<p align="center">
  <img src="./assets/defense-stack.svg" width="100%" alt="Defense in depth: client, API, data and infra layers, with untrusted input stopped at the shield"/>
</p>

<details>
<summary><b>📜 Rules of engagement</b></summary>

```text
[01] Only test what I'm authorised to test.
[02] Find it, prove it, report it — never exploit it for gain.
[03] Disclose responsibly; give owners time to fix.
[04] Protect user data as if it were my own.
[05] Share what I learn so others can defend better.
```

</details>

---

### `$ ls ./toolkit/`

| | |
|---|---|
| 🛡️ **offense → defense** | <img src="https://skillicons.dev/icons?i=kali,python,linux,bash&theme=dark" height="34"/> &nbsp; Burp Suite · Nmap · Metasploit · MobSF · OWASP Juice Shop · PortSwigger Labs |
| 🧠 **ml security** | <img src="https://skillicons.dev/icons?i=sklearn,py&theme=dark" height="34"/> &nbsp; XGBoost · Scapy · pandas · Jupyter |
| 📱 **client** | <img src="https://skillicons.dev/icons?i=flutter,dart,ts,firebase&theme=dark" height="34"/> &nbsp; Clean Architecture · MVVM · Bloc · Riverpod · GetX |
| ⚙️ **server** | <img src="https://skillicons.dev/icons?i=nestjs,nodejs,express,mongodb,mysql,redis&theme=dark" height="34"/> &nbsp; REST · Socket.IO · BullMQ · Stripe · ffmpeg/HLS |
| 🚀 **ops** | <img src="https://skillicons.dev/icons?i=githubactions,aws,git&theme=dark" height="34"/> &nbsp; Codemagic · Shorebird OTA · PM2 · VPS |

---

### `$ ls ./case-files/`

Scroll-driven 3D investigations on [nazibullahnoyon.me/case-study](https://nazibullahnoyon.me/case-study):

| File | Incident | Lesson |
|---|---|---|
| [`001`](https://nazibullahnoyon.me/case-study/academic-portal-disclosure) | Knowing where to stop | Responsible disclosure |
| [`002`](https://nazibullahnoyon.me/case-study/npm-supply-chain-attack) | One install command, four servers | Supply-chain trust |
| [`003`](https://nazibullahnoyon.me/case-study/mongodb-ransomware-attack) | Nineteen months with the door open | Exposed databases |
| [`004`](https://nazibullahnoyon.me/case-study/shwapno-data-breach) | The Shwapno data breach | Data protection |
| [`005`](https://nazibullahnoyon.me/case-study/wannacry-eternalblue) | WannaCry and EternalBlue | Patch management |

---

### `$ ls ./builds/`

| Project | What it does | Stack |
|---|---|---|
| **BeatX** | Solo-built streaming backend: multi-GB uploads → S3 → 4 HLS renditions on a job queue | NestJS · BullMQ · ffmpeg · S3 |
| **Exodus** | Bus booking: QR tickets, live bus tracking, pay on arrival | Flutter · Socket.IO · Stripe |
| **[AzloTV](https://github.com/noyon-360/flutter_flimsa_v2)** | Streaming app: series, reels, resume-where-you-stopped player | Flutter · GetX · Chewie |
| **[Envielite](https://github.com/FSDTeam-SAA/flutter_envielite)** | Offline in-flight tour guide, 300 m GPS geofences, 8 languages | Flutter · Geolocator |
| **[CosmoQuest](https://github.com/noyon-360/CosmoQuest)** | Learn exoplanets from NASA data, quizzes and leaderboards | Flutter · Firebase · NASA APIs |
| **[Couplio](https://github.com/noyon-360/couplio)** | Calorie tracker for two, QR pairing and live sync | Flutter · Firestore · Gemini |

Other: [ML in Cyber Security (thesis)](https://github.com/noyon-360/ML-in-Cyber-security) · [Dhikr Application](https://github.com/noyon-360/Dhikr-Application) · [Primeasia CSE Waiver Calculator](https://github.com/noyon-360/primeasia-waiver)

---

### `$ ./stats --live`

<p align="center">
  <img src="https://img.shields.io/badge/35%2B-apps%20shipped-39ff88?style=flat-square&labelColor=0a110c"/>
  <img src="https://img.shields.io/badge/14-engineers%20led-ffcc00?style=flat-square&labelColor=0a110c"/>
  <img src="https://img.shields.io/badge/99%25-crash--free-00e5ff?style=flat-square&labelColor=0a110c"/>
  <img src="https://img.shields.io/badge/98%25-IDS%20accuracy-ff3b5c?style=flat-square&labelColor=0a110c"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=noyon-360&hide_border=true&background=050806&ring=39ff88&fire=ff3b5c&currStreakLabel=39ff88&sideLabels=d9f7e3&currStreakNum=d9f7e3&sideNums=d9f7e3&dates=7a9984&stroke=0a110c" alt="GitHub streak" height="165"/>
</p>

<!-- 3D contribution calendar — generated daily by .github/workflows/profile-3d.yml -->
<p align="center">
  <img src="./profile-3d-contrib/profile-night-green.svg" alt="3D contribution calendar" width="100%"/>
</p>

---

### `$ ping noyon`

<p align="center">
  <a href="https://nazibullahnoyon.me"><img src="https://img.shields.io/badge/portfolio-050806?style=for-the-badge&logo=googlechrome&logoColor=39ff88" alt="Portfolio"/></a>
  <a href="mailto:nazibullahnoyon19.20@gmail.com"><img src="https://img.shields.io/badge/email-050806?style=for-the-badge&logo=gmail&logoColor=ff3b5c" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/nazibullah3nsn/"><img src="https://img.shields.io/badge/linkedin-050806?style=for-the-badge&logo=linkedin&logoColor=00e5ff" alt="LinkedIn"/></a>
</p>

<p align="center"><code>// found a vulnerability in something I built? report it — I'll thank you, not fight you.</code></p>
