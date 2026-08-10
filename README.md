## Jorge Flores

Network Administrator working in **network automation and security compliance** — automating the hardening and auditing of Cisco infrastructure against DoD STIG standards.

I like the problems where a mistake takes the device offline, because those are the ones that force you to build the safety in.

---

### 🔭 Featured — [NetworkAutomation](https://github.com/jflores3531/NetworkAutomation)

Python and Ansible tooling that audits and remediates Cisco IOS, IOS-XE, and NX-OS devices against **DISA STIG benchmarks**.

- **155 automated compliance checks** across 6 DISA benchmarks (IOS Switch L2S/NDM, NX-OS L2S/NDM, IOS Router NDM/RTR)
- **Multi-vendor coverage from one inventory** — Cisco IOS, IOS-XE, and NX-OS audited and hardened through a shared engine, with platform differences handled per-driver rather than forked into separate tools
- **No credentials on disk or in argv** — runtime `getpass` prompts, gitignored secrets file, zero device data hardcoded in script logic
- Rules requiring PKI or topology judgment report `NOT AUTOMATED` rather than guessing — a false pass on a compliance tool is worse than no answer

Validated live against a 7-device virtual lab: 2 IOS routers, 3 IOSvL2 switches, 2 NX-OS cores.

---

### 🧰 Working with

**Automation** — Python, Netmiko, Ansible (roles, resource modules, Vault), Jinja2, YAML
**Network** — Cisco IOS / IOS-XE / NX-OS, L2 security (DHCP snooping, DAI, IP Source Guard, BPDU/Root Guard, 802.1X/MAB), routing & switching, VLANs/trunking, NTP/syslog/SNMPv3, AAA & RADIUS
**Security** — DISA STIG hardening, compliance-as-code, uRPF, management-plane ACLs, SSH/FIPS cipher policy
**Tooling** — Git, Linux, virtual lab environments

---

### 📜 Certifications

- **Cisco CCNP Enterprise**
- **CompTIA CySA+** — DoD 8140/8570 IAT Level II
- **CompTIA Pentest+**

The security certs are why the STIG work is more than checkbox automation — reading a benchmark as an attacker's checklist is what surfaces the false passes.

---

### 📫 Reach me

- **Email:** flores.jorge3531@gmail.com

<!-- Add your LinkedIn here when ready:
- **LinkedIn:** https://linkedin.com/in/your-handle
-->
