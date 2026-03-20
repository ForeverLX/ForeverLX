# Hey, I'm Darrius (ForeverLX) 👋

**Red Team Infrastructure Engineer • Vulnerability Researcher • Founder @ Azrael Security**

I build production-grade offensive security infrastructure and conduct systems-level security research. My focus is on the intersection of low-level Linux behavior and real offensive infrastructure — understanding exactly how isolation boundaries work, where they fail, and what that means for red team operations.

- 🏗 Building: **[Veil](https://github.com/ForeverLX/veil)** — Azrael Security's homelab infrastructure. Mythic C2 on declarative NixOS, WireGuard mesh, Cowrie honeypot, Suricata IDS, rootless Podman on a Chromebook edge node.
- 🔬 Researching: **Container boundary weaknesses** — filesystem/mount abuse, namespace privilege boundaries, `/proc` visibility leaks, and how these primitives apply to offensive infrastructure.
- 🖥 Operating from: **[NightForge](https://github.com/ForeverLX/nightforge)** — reproducible Arch Linux operator workstation with Niri compositor, operator terminal framework, and containerized offensive tooling.
- 📍 Based in Phoenix, Arizona — working fully remote.

---

## 🔒 What I Work On

### Veil — Azrael Security Infrastructure
A three-node offensive security homelab built for real adversary emulation and red team infrastructure research:
- **Cerberus** — Chromebook edge node running Cowrie honeypot, Suricata IDS, Pi-hole, Gitea, Vaultwarden — all rootless Podman Quadlets
- **Tairn** — NixOS 24.11 declarative VM running Mythic C2 with Poseidon agent, WireGuard-only access
- **NightForge** — Arch Linux operator workstation, primary development and ops environment
- WireGuard hub-and-spoke mesh across all nodes — no node reachable from WAN

### Security Research
Documented research at the intersection of Linux systems internals and offensive security:
- Container boundary analysis (Podman rootless, Docker, namespace isolation)
- Linux kernel privilege escalation primitives (long-term track)
- Reverse engineering methodology — documented challenge series building toward binary analysis and CVE research
- AD attack path documentation from CRTA and CRT-ID coursework (CyberWarfare Labs)

### NightForge — Operator Workstation
Reproducible offensive security workstation built as a portfolio artifact:
- Niri Wayland compositor, operator terminal framework with VPN/engagement/MITRE context
- Rootless Podman profiles for isolated AD, RE, and web workflows
- MITRE ATT&CK technique logging built into shell

---

## 🧠 Technical Focus

- **Offensive Security:** red team infrastructure, C2 deployment and hardening, adversary emulation
- **Vulnerability Research:** container boundaries, Linux namespace/capability abuse, kernel exploitation (building toward)
- **Systems:** Linux-first (Arch, NixOS), kernel internals, containers (Podman/Docker), WireGuard
- **Reverse Engineering:** ELF analysis, GDB/GEF, static + dynamic analysis methodology
- **Frameworks:** MITRE ATT&CK, declarative infrastructure (NixOS), rootless container patterns

---

## 🔗 Connect

- 🌐 Website: [darriusgrate.vercel.app](https://darriusgrate.vercel.app/)
- 🧷 LinkedIn: [linkedin.com/in/darrius-grate](https://www.linkedin.com/in/darrius-grate/)
- 📧 Email: [Darrius.G@proton.me](mailto:darrius.g@proton.me)
- 💼 Azrael Security: Red team infrastructure engineering and offensive security research
