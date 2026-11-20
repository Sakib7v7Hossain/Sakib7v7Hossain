# Sakib Hossain

Software and DevOps engineer in Dhaka, Bangladesh, moving into cloud and AI-agent security.

I started as a Flutter developer in 2020, moved into cloud and DevOps engineering, and now spend my time on cloud security, networking in depth, and security for AI agents.

---

## Security and research

### AgentTrap: a guard for AI-agent tool calls

A decoy-first, tamper-evident guard that sits at the tool-call boundary of an AI agent, built as a security extension for NLIP (ECMA-430/434). It decides only from the call, earlier session state and a written policy, with no model in the decision path.

- Decoy tools and objects as tripwires, taint tracking after untrusted reads, an egress allowlist, secret tracking and an output check
- Allow / warn / block decisions, an append-only hash-chained log, and an HTML incident report generated from that log
- 81-scenario benchmark against four baselines, plus adaptive attackers. Results include the misses and false positives, and the limits are documented
- Python, 27 tests, Apache-2.0
- Status: prepared as an entry for the NDSS SafeOSE '27 AI Security Hackathon. Agents in the benchmark are scripted; a harness for running a live model is included but live results are not claimed yet

Code and demo video: *link to be added once the repository is public.*

### LLM-based honeypots and attacker behaviour reconstruction

Academic research project on web/API honeypots driven by language models and on reconstructing attacker behaviour from their sessions.

Status: in progress. No public code or paper yet.

---

## Learning and tools I build

### CloudSketch

A diagramming canvas for learning AWS, networking and DevOps, with drill-down diagrams (a block can open into its own diagram), terminal and laptop-part blocks, notes and live rooms. React, @xyflow/react, Firebase.

[Open the app](https://cloudsketch-alpha.vercel.app/app)

### Networking course videos

An 11-episode series that explains networking on one real scenario: a laptop joining Wi-Fi and loading a page, with real IPs, commands and packets.

---

## Product and mobile work

### Fluent Mira (founder)

AI-powered multi-language learning platform. Flutter, React, Vite, TailwindCSS, Firebase, Node.js, Vercel.

[Website](https://www.fluentmira.com/)

### Phictly (Flutter developer)

Educational social platform. I developed and maintained the Flutter mobile app from planning to production release.

- Integrated REST APIs, Firebase, authentication and push notifications
- Wrote tests and fixed production issues
- Published and maintained the app on Google Play and the App Store

[Website](https://phictly.com/) · [Google Play](https://play.google.com/store/apps/details?id=com.phictly.app&hl=en) · [App Store](https://apps.apple.com/in/app/phictly-book-tv-clubs/id6753308823)

### Tasbih

A private, offline dhikr counter and daily dua tracker for Android. No internet permission, no account, no data collected. English, Bangla and Turkish.

[Download](https://github.com/Sakib7v7Hossain/tasbih/releases/latest)

### Algorithm VA

Android app I published on Google Play.

---

## Skills

| Area | Tools |
| --- | --- |
| Cloud and DevOps | AWS, Terraform, Docker, GitHub Actions, CI/CD, Linux, Bash |
| Security | Cloud security fundamentals, networking, AI-agent tool-call security, honeypots |
| Mobile | Flutter, Dart, Android, Firebase, BLoC, GetX, REST APIs |
| Backend | Spring Boot, Node.js, Firebase |
| Frontend | React, Vite, TailwindCSS |
| Languages | Python, Dart, JavaScript/TypeScript, Java |

## Community

- Technical articles on Medium
- Stack Overflow: 27K+ people reached, with 2 gold, 5 silver and 16 bronze badges

---

## Links

- GitHub: https://github.com/Sakib7v7Hossain
- LinkedIn: https://linkedin.com/in/sakibxhossain
- Medium: https://medium.com/@xsakib964
- Stack Overflow: https://stackoverflow.com/users/17184390/sakib-x-hossain
- Email: xsakib964@gmail.com
