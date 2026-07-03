# Hi, I'm Ryan 👋

Windows infrastructure administrator who automates the boring parts.
I work with Windows Server, VMware vSphere, Active Directory, and Dell
server hardware — and I'd rather write a script that does it right every
time than click through the same console twice.

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
`Dell iDRAC / Redfish` · `Pester + PSScriptAnalyzer CI` · `GitHub Actions`

## 📐 How I write scripts

- Read-only by default; anything destructive is opt-in and confirmed
- Parameters over hard-coded values, reports over silent changes
- Works on Windows PowerShell 5.1 *and* PowerShell 7 — because servers
