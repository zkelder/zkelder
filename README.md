# Zac Kelder

**Infrastructure & Systems Engineer** · Linux, VMware, identity, networking, AWS and automation

Eight years operating infrastructure where reliability matters: U.S. Army deployable field systems, networks and communications, then enterprise Linux, Windows, VMware and identity services for a global workforce. I bring that operational perspective to the systems I design and build end to end.

Portfolio and case studies: **[zkelder.dev](https://zkelder.dev)** · [Résumé (PDF)](https://zkelder.dev/assets/resume/zac-kelder-resume.pdf) · [LinkedIn](https://linkedin.com/in/zkelder) · zachkelder@gmail.com

## Professional experience

- **Systems Administrator, Trilliant Networks (2023–2025).** Linux (RHEL, Rocky, Ubuntu) and Windows servers on VMware vCenter; Red Hat IdM/FreeIPA, LDAP, Kerberos and SSSD; Microsoft 365, Active Directory, Entra ID and Intune/Autopilot; email security, privileged-credential protection and security-audit remediation for roughly 400 employees and 300 endpoints across multiple sites.
- **Systems Maintainer / Technical Team Lead, U.S. Army (2017–2023).** Led a nine-person team responsible for mission-critical IT and communications equipment. Deployed and restored field environments end to end: power, bare-metal Windows and Linux servers, Cisco networking, SATCOM and endpoints.
- CompTIA Security+ · CompTIA A+ · ITIL Foundation

Full record: [zkelder.dev/#experience](https://zkelder.dev/#experience)

## Engineering work

Four systems, each designed, built and operated end to end. The case studies carry the architecture, design decisions, evidence and limitations.

| Project | What it is | Engineering | Case study |
|---|---|---|---|
| **Apex** | Quantitative research platform: scheduled collection of real public market data into append-only PostgreSQL evidence, point-in-time strategy evaluation, PAPER trials with a double-entry ledger and an Operator Console. Research and simulated capital only. | Python 3.12 (`mypy --strict`), PostgreSQL + Alembic, systemd timers, Docker Compose, React + TypeScript | [zkelder.dev/apex](https://zkelder.dev/apex/) · [interactive demo](https://zkelder.dev/apex/demo/) · source: [apex-showcase](https://github.com/zkelder/apex-showcase) |
| **MockingBird** | Local-first wildlife observation platform: cameras and footage in, a searchable record of a place out. Detection and tracking on an ONNX runtime, a Raspberry Pi Camera Node, SQLite with verified backup and restore. Pre-release. | FastAPI, React, ONNX Runtime, SQLite, Raspberry Pi edge node under systemd | [zkelder.dev/mockingbird](https://zkelder.dev/mockingbird/) · source: [mockingbird](https://github.com/zkelder/mockingbird) |
| **ArenaOps** | AWS backend that woke on demand, reported readiness to the visitor, ran its WebSocket workload and returned to zero. Retired in 2026 with its architecture and cost record preserved. | Terraform, ECS/Fargate, ALB, ECR, IAM/OIDC, EventBridge Scheduler, GitHub Actions, CloudWatch | [zkelder.dev/arenaops](https://zkelder.dev/arenaops/) |
| **Food Checker** | iOS app that scans a food label and flags the ingredients you choose to watch for, with a hardened FastAPI OCR service, Supabase auth and data, and private monitoring. In TestFlight beta. | Expo / React Native, FastAPI + Tesseract, Terraform + Ansible, GitHub Actions OIDC + SSM deploys, Prometheus + Grafana | [zkelder.dev/foodchecker](https://zkelder.dev/foodchecker/) · source: [food-checker](https://github.com/zkelder/food-checker) |

## How I work

- Check health before declaring success.
- Make failure states legible to users and operators.
- Prefer controlled, repeatable delivery paths.
- Document boundaries, recovery and limitations.

Open to systems administration, infrastructure engineering, cloud operations, and identity and access roles.
