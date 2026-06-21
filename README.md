# 👋 I'm Darrius Grate — `@CR1MS0N`

**Red team operator, security tool builder, reverse engineer.**  
I build the tools that make offensive security operations faster, stealthier, and more automated.

---

## 🏛️ Three Pillars

```
┌─────────────────────────────────────────────────────────────┐
│                                                             │
│   🛡️ Red Team Infrastructure     (primary)                 │
│   🤖 Agentic Security Architecture (secondary)              │
│   🔬 RE & Threat Intelligence     (sustaining)              │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```
---
*Building offensive tools, one commit at a time."Below the abstraction."*
---

### [Veil](https://github.com/CR1MS0N-Operator/veil) — Red Team Infrastructure
Three-node WireGuard mesh with dedicated Alpine redirector VM (Hermes). NixOS C2 node (Mythic + Poseidon/Apollo agents), Alpine TLS redirector (nginx), Arch edge node (Cerberus). Hub-and-spoke topology built for realistic engagement OPSEC — WireGuard-only C2 access, nftables rate limiting, Cowrie honeypot on external SSH, Suricata IDS, Pi-hole DNS sinkhole. Self-hosted service stack: Gitea, Vaultwarden, SearXNG, Caddy TLS.

### [security-research](https://github.com/CR1MS0N-Operator/security-research) — Container Boundary Research
Analysis of OCI hook execution in rootless Podman deployments. CVE-2025-23266 investigation, threat modeling for GPU-enabled multi-tenant environments. Published whitepaper on container escape primitives and privilege boundary enforcement. Technique library with MITRE ATT&CK mapping: Kerberoasting, AS-REP Roasting, DCSync, Golden Ticket, ADCS abuse.

### [NightForge](https://github.com/CR1MS0N-Operator/nightforge) — Operator Workstation for Red Team & AI Agent Operations
Reproducible Arch Linux workstation built for red team operators and AI agent orchestration. Niri Wayland compositor with scrolling tiling. Quickshell 0.2.1 UI layer: per-screen glassmorphism bar, widget overlay system (ControlCenter, Music, Network, WallpaperPicker, StatusMonitor, Monitor), morph transitions. Matugen dynamic theming extracts Catppuccin Mocha palette from wallpaper. Real-time services: VPN status (WireGuard), Podman containers, MPD media, system health. Operator terminal framework surfaces engagement context, MITRE ATT&CK technique logging, and container status on every shell launch. Rootless Podman profiles (ad, re, web, toolbox) for isolated offensive workflows.

### [ACLGuard](https://github.com/CR1MS0N-Operator/ACLGuard-Active-Directory-Permission-Auditor) — AD ACL Analyzer
C-based Active Directory permission analyzer identifying DACL misconfigurations and privilege escalation paths. CSV/JSON export for integration with continuous assessment workflows. Lightweight single binary with minimal dependencies.

---

## Philosophy

**Proactive over reactive.** The security industry spends most of its energy responding to incidents that have already happened. I build tooling and research that anticipates adversary behavior — counter-reconnaissance, adversary emulation, behavioral baselining, and continuous attack surface validation.

**Depth over breadth.** One thoroughly understood system is worth more than ten superficially known. Every component in my infrastructure is justified, documented, and manually validated before automation wraps it.

**Local-first.** Self-hosted toolchain where possible. Gitea, SearXNG, Vaultwarden, Open WebUI on internal infrastructure. Cloud when necessary, local when feasible.

**OPSEC-conscious.** Lab infrastructure mirrors real engagement constraints — WireGuard-only C2 access, dedicated redirector VMs, network segmentation, honeypot layers. Security research should not compromise the researcher.

---

## Certifications & Training

**Completed:**
- **Active Directory Red Team Specialist (AD-RTS)** — CyberWarfare Labs, 2025

**In Progress:**
- **Certified Red Team Analyst (CRTA)** — CyberWarfare Labs
- **Red Team Operator Specialist (ROPS-RT1)** — Rogue Labs

**Planned:**
- **CRT-ID, MCRTA, OCO-AI** — CyberWarfare Labs (post-CRTA pipeline)
- **BTF, PTF, CPIA, CRT-COI** — CyberWarfare Labs (long-term track)

---

## Community

- **OWASP Las Vegas** — Chapter Leader (Dec 2025 – Mar 2026)
- **HackSpaceCon 2026** — Volunteer

---

## 📊 GitHub Stats

![CR1MS0N-Operator's GitHub stats](https://github-readme-stats.vercel.app/api?username=CR1MS0N-Operator&show_icons=true&theme=dark&hide_border=true)

---

*Independent security researcher.*
---
