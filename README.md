# Hey, I'm Darrius (ForeverLX)
Offensive Security Engineer • Vulnerability Researcher • Founder @ Azrael Security

I build red team infrastructure and conduct original security research. My focus is the boundary between userspace and kernel — how isolation mechanisms work, where they fail, and what that means for offensive operations.

## What I'm Working On

**Veil** — Three-node WireGuard mesh running live red team infrastructure. Mythic C2 on declarative NixOS, rootless Podman Quadlets on an Arch Linux edge node, Alpine Linux redirector with TLS termination. Every decision is documented and version controlled.

**Container Boundary Research** — Published investigation into OCI hook execution in rootless Podman deployments. Examines whether nvidia-container-runtime executes hooks with privileges exceeding the container's user namespace mapping. Threat model: compromised agentic workload in a GPU-enabled multi-tenant environment. Builds on CVE-2025-23266.

**NightForge** — Arch Linux operator workstation. Niri WM, Neovim, Ghostty, operator terminal framework. Version controlled throughout.

## Technical Focus

- Red team infrastructure: C2 deployment, WireGuard mesh, redirector architecture, rootless containers
- Vulnerability research: container boundary analysis, OCI runtime behavior, namespace privilege boundaries
- Active Directory: Kerberoasting, AS-REP Roasting, DCSync, Golden Ticket, ADCS abuse — documented end-to-end with ATT&CK mapping
- Reverse engineering: ELF analysis, GDB/GEF, static and dynamic methodology

## Connect

- Site: foreverlx.github.io
- LinkedIn: linkedin.com/in/darrius-grate
- Email: Darrius.G@proton.me
