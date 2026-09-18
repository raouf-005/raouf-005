# Abderraouf Derardja

**Systems & Network Engineering, moving toward DevOps** &nbsp;·&nbsp; M2 Systemes & Reseaux, Paris Saclay 

I build and automate network infrastructure, and I spend my spare time taking apart the binaries that run on it.

My most recent work is the full Ansible automation of a redundant L2/L3 lab: VLANs, STP/RSTP convergence, MLAG with server-side bonding, VRRP gateway failover and NFS, across Debian hosts and Cumulus Linux switches. Before moving into systems and networks I shipped several full-stack products, which is why this profile mixes infrastructure work with React and Next.js.

**Open to opportunities in France and Europe** — infrastructure, network engineering, systems administration, DevOps.

---

## What I work with

| | |
|---|---|
| **Networking** | VLANs · STP / RSTP · MLAG · VRRP · LACP bonding · L3 routing · NFS · tcpdump / Wireshark |
| **Systems** | Linux (Debian, CentOS) · Cumulus Linux · VMware lab infrastructure · Bash |
| **Automation & IaC** | Ansible — roles, inventories, `group_vars` / `host_vars`, Jinja2 templates, handlers · Docker · Docker Compose |
| **Security** | Binary exploitation — stack & heap overflows, format strings, ret2libc, ROP · x86 Assembly · GDB · pwntools · network and log forensics |
| **Development** | JavaScript / TypeScript · React · Next.js · Node / Express · Prisma · PostgreSQL · MongoDB · React Native |
| **Testing** | Jest · Selenium |

---

## Selected work

### [Redundant network automation with Ansible](https://github.com/raouf-005/AnsibleProject)
A campus network built and torn down entirely from playbooks. NFS export with VLAN segmentation, spanning tree convergence compared between STP and RSTP, access-layer fault tolerance through MLAG plus bonded server links, and VRRP router redundancy. Written as reusable roles with Jinja2-templated `/etc/exports` and interface configs, and a rollback playbook that returns Cumulus switches to a clean baseline via `net rollback` so any scenario can run on the same hardware.
`Ansible` `Jinja2` `Cumulus Linux` `Debian` `NFS` `VRRP` `MLAG`

### [ERMVEHICULE](https://github.com/raouf-005/ERMVEHICULE) — vehicle fleet & invoicing ERP
Customers, vehicles, parts and invoices with duplication and status workflow, role-based administration over users and groups, generated PDF invoices, and a PostgreSQL database provisioned through Docker Compose with Prisma migrations.
`Next.js` `TypeScript` `Prisma` `PostgreSQL` `NextAuth` `Docker Compose` — [live demo](https://ermvehicule.vercel.app)

### [Knowlo](https://github.com/raouf-005/Knowlo-FrontEnd) — e-learning platform
A course marketplace with three distinct roles (student, teacher, affiliate), each with its own dashboard, course creation flow, cart and checkout. Containerized, with a Jest component suite and Selenium end-to-end tests.
`Next.js` `Docker` `Jest` `Selenium` — [live demo](https://knowlo-front-end.vercel.app)

### [ctfs](https://github.com/raouf-005/ctfs) — binary exploitation archive
Solutions and exploit scripts from several years of CTF play, kept with the vulnerable source, the compiled binary and the shipped libc so each one is reproducible. Stack and heap overflows, format-string primitives, ret2libc and ROP chains, plus x86 assembly coursework.
`Python` `C` `x86 Assembly` `pwntools` `GDB`

### [Vyvix](https://github.com/raouf-005/Vyvix-Project) — full-stack SaaS
React dashboard over an Express/MongoDB API, session auth with Passport, and a Gemini-backed generation feature.
`React` `Express` `MongoDB` `Passport` — [live demo](https://vyvix.vercel.app)

### [SimulatorWindowsLinux](https://github.com/raouf-005/SimulatorWindowsLinux)
An interactive side-by-side simulation of the Windows and Linux desktop experience — taskbar, terminal, system monitor, simulated lag, and a narrative flow that makes the comparison something you feel rather than read.
`Next.js` `React` `JavaScript` — [live demo](https://simulator-windows-linux.vercel.app)

---

## Capture The Flag

I play the **pwn** category — binary exploitation. Each write-up below keeps the vulnerable source, the exploit script and the reasoning that got there.

- [picoCTF 2024](https://github.com/raouf-005/picoCTF2024-writeup) — format strings and heap exploitation
- [Hackini 2K24](https://github.com/raouf-005/Hackini_2K24_writeups) — buffer overflows, format strings, ret2libc
- [CSCC 2024](https://github.com/raouf-005/CSCC24-writeup) — ret2win and controlled-call chains
- [Ramadan Spark 2024](https://github.com/raouf-005/Ramadan-Spark2024-writeup) — pwn, plus network and access-log forensics
- [Hackfest 2k24](https://github.com/raouf-005/Hackfest-2k24-writeup)

---

## Contact

[LinkedIn](https://www.linkedin.com/in/abderraoufderardja/) &nbsp;·&nbsp; raouf.ard@gmail.com
