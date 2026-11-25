# Sakib Hossain

Flutter developer and cloud/AI-agent security researcher in Dhaka, Bangladesh. I started as an Android developer in 2020, moved to Flutter and shipped apps to the App Store and Google Play, and now work on cloud security and AI-agent security.

---

## Security and research

### AgentTrap: a guard for AI-agent tool calls

A decoy-first, tamper-evident guard that sits at the tool-call boundary of an AI agent, built as a security extension for NLIP (ECMA-430/434). It decides only from the call, earlier session state and a written policy, with no model in the decision path.

- Decoy tools and objects as tripwires, taint tracking after untrusted reads, an egress allowlist, secret tracking (including decoding encoded exfiltration) and an output check
- Allow / warn / block decisions, an append-only hash-chained log, and an HTML incident report generated from that log
- 81-scenario benchmark against four baselines (stops 43 of 45 attacks vs 31 for an allowlist), ablations, and adaptive attackers; a replay of all 1,054 InjecAgent cases; and a live-model evaluation where a real model (gpt-4.1-mini) acts as the agent and as an adaptive attacker
- The adaptive LLM attacker found two real bypasses, which drove concrete fixes and raised coverage; misses, false positives and limits are documented, with confidence intervals on every sampled number
- Python, 38 tests, Apache-2.0
- Status: entry for the NDSS SafeOSE '27 AI Security Hackathon (Area 03). Idea and research design are mine; I used Claude to build the prototype and harness quickly and verified every result on my own machine

Code and demo: https://github.com/Sakib7v7Hossain/agenttrap

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
