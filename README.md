# Hi, I'm Ryan 👋

Security & infrastructure operations — 17 years defending Windows, Active
Directory, and VMware environments in government, defense-industrial, and
regulated spaces.

**Currently:** Managing systems administration and security operations at
Unisys, supporting a major U.S. naval shipbuilding customer. Vulnerability
management, incident investigation, CIS/NIST/FedRAMP hardening.

**Building:** Detection engineering skills in public — Sigma rules, Windows
event log analysis, and Atomic Red Team-driven detection testing for Active
Directory attack techniques. Watch this space.

**Background:** Prior DoD Secret clearance · HIPAA and state-regulated gaming
environments · PowerShell, Puppet, Ansible automation

## 🔧 What I build

- **[VMware-Admin-Toolkit](https://github.com/rynoman03/VMware-Admin-Toolkit)** —
  safe, report-driven PowerCLI scripts for vSphere: health & compliance
  checks and update remediation that's read-only by default and
  `-WhatIf`-guarded when it isn't.
- **[Maintenance](https://github.com/rynoman03/Maintenance)** — my working
  toolbox for Windows systems administration. Home of **AdminHub**, an
  interactive server admin menu (htop-style live process monitor, 20+
  health checks with Nagios-style exit codes, event-log search, guarded
  service/process/reboot actions) that deploys as a PowerShell module and
  autoloads in remote sessions. Plus iDRAC management via Redfish, TLS
  hardening scripts, and AD tooling.

## 🧰 Tools of the trade

`PowerShell` · `PowerCLI / vSphere` · `Windows Server` · `Active Directory` ·
`Puppet` · `Ansible` · `Dell iDRAC / Redfish` · `Pester + PSScriptAnalyzer CI` ·
`GitHub Actions`

## 📐 How I write scripts

- Read-only by default; anything destructive is opt-in and confirmed
- Parameters over hard-coded values, reports over silent changes
- Works on Windows PowerShell 5.1 *and* PowerShell 7 — because servers
  don't all get to choose their PowerShell version
