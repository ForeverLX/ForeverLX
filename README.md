# Darrius Grate

**Offensive Security Researcher** — AI-augmented red team infrastructure, adversarial robustness evaluation, container boundary analysis.

Building systems that operate *before* adversaries execute. Proactive security over reactive incident response.

---

## Research Focus

- **Adversarial robustness of AI-augmented security infrastructure** — systematic evaluation of failure modes when LLMs are integrated into operational security tooling
- **Container boundary analysis** — privilege escalation paths in rootless container runtimes, OCI hook execution surfaces, GPU multi-tenant isolation
- **Red team infrastructure architecture** — reproducible C2 deployment pipelines, redirector-as-pivot topologies, OPSEC-hardened operational environments
- **Automated threat intelligence** — behavioral baselining, cross-target correlation, CVE-to-surface mapping with LLM-enriched triage

---

## Background

My path to offensive security research is deliberate and compounding:

**Physical security operations** (4+ years) → developed analytical discipline, incident documentation, structured reporting, and the patience to observe adversary behavior before acting.

**Enterprise technical support** (GetInsured) → honed technical communication across technical and non-technical audiences, HIPAA-regulated process discipline, and high-volume structured triage (120 cases/week). Selected for specialized leadership-development team (6 individuals).

**Practitioner-led apprenticeship** (4Sec-LLC) → hands-on offensive security training under active red team operators and threat intelligence practitioners. Real-world scenario emphasis over certification chasing. Received ROPS-RT1 training kit at HackSpaceCon 2026.

**Independent research & infrastructure** (Azrael Security) → combining operational security experience with deep technical research. Building reproducible infrastructure, publishing vulnerability analysis, and designing proactive evaluation frameworks. Building Azrael Security for Q3 2026 launch.

Each phase compounds into a research approach that is operationally grounded, rigorously documented, and adversary-aware.

---

## Selected Work

### [Veil](https://github.com/ForeverLX/veil) — Red Team Infrastructure
Three-node WireGuard mesh with dedicated Alpine redirector VM (Hermes). NixOS C2 node (Mythic + Poseidon/Apollo agents), Alpine TLS redirector (nginx), Arch edge node (Cerberus). Hub-and-spoke topology built for realistic engagement OPSEC — WireGuard-only C2 access, nftables rate limiting, Cowrie honeypot on external SSH, Suricata IDS, Pi-hole DNS sinkhole. Self-hosted service stack: Gitea, Vaultwarden, SearXNG, Caddy TLS.

### [euphrates](https://github.com/ForeverLX/euphrates) — CVE Research Pipeline
Go-based continuous attack surface monitoring and CVE root cause research. Multi-source feed ingestion (NVD API v2, OSV.dev), behavioral baselining (TLS fingerprinting, header analysis), and LLM-enriched triage via OpenRouter API. Maps published CVEs to live target surfaces with confidence scoring. Single binary, SQLite-backed, systemd-timed.

### [security-research](https://github.com/ForeverLX/security-research) — Container Boundary Research
Analysis of OCI hook execution in rootless Podman deployments. CVE-2025-23266 investigation, threat modeling for GPU-enabled multi-tenant environments. Published whitepaper on container escape primitives and privilege boundary enforcement. Technique library with MITRE ATT&CK mapping: Kerberoasting, AS-REP Roasting, DCSync, Golden Ticket, ADCS abuse.

### [NightForge](https://github.com/ForeverLX/nightforge) — Operator Workstation for Red Team & AI Agent Operations
Reproducible Arch Linux workstation built for red team operators and AI agent orchestration. Niri Wayland compositor with scrolling tiling. Quickshell 0.2.1 UI layer: per-screen glassmorphism bar, widget overlay system (ControlCenter, Music, Network, WallpaperPicker, StatusMonitor, Monitor), morph transitions. Matugen dynamic theming extracts Catppuccin Mocha palette from wallpaper. Real-time services: VPN status (WireGuard), Podman containers, MPD media, system health. Operator terminal framework surfaces engagement context, MITRE ATT&CK technique logging, and container status on every shell launch. Rootless Podman profiles (ad, re, web, toolbox) for isolated offensive workflows.

### [ACLGuard](https://github.com/ForeverLX/ACLGuard-Active-Directory-Permission-Auditor) — AD ACL Analyzer
C-based Active Directory permission analyzer identifying DACL misconfigurations and privilege escalation paths. CSV/JSON export for integration with continuous assessment workflows. Lightweight single binary with minimal dependencies.

### [azrael-ops-dashboard](https://github.com/ForeverLX/azrael-ops-dashboard) — Operations Dashboard
Go operations dashboard monitoring Veil infrastructure: Mythic C2 health, WireGuard tunnel status, Suricata alerts, Cowrie honeypot events, Pi-hole metrics, nftables rule visualization. Single-pane operational awareness for red team lab environments. SQLite-backed, SSE live updates, templ templates.

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
- **DEF CON Red Team Village** — Volunteer (upcoming)

---

## Connect

- **Site:** [azraelsec.dev](https://azraelsec.dev)
- **LinkedIn:** [linkedin.com/in/darrius-grate](https://linkedin.com/in/darrius-grate)
- **Email:** Darrius.G@proton.me

---

*Independent security researcher. Building Azrael Security — "Below the abstraction."*
