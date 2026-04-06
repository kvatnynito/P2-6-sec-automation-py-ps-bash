# P2-6: Cybersecurity Automation & Scripting

## Overview

This repo is planned to document practical cybersecurity automation across Python, PowerShell, and Bash.

It is intended to focus on small tools and scripts for log parsing, alert enrichment, evidence collection, and repeatable security tasks that support SecOps, SOC, and incident response workflows.

This project is part of Portfolio 2 and is planned as a follow-on phase after completion of Portfolio 1, which provides the lab environment, telemetry sources, and security workflows that can later feed automation use cases.

---

## Status

**Current state:** Planned  
**Execution state:** Not yet started  
**Prerequisite:** Portfolio 1 completion

This repo is being prepared in advance so that the project scope, script categories, sample use cases, and expected deliverables are already defined before hands-on scripting work begins.

---

## Planned Objectives

This project is intended to build practical automation skills, including:

- creating cross-platform security scripts
- parsing and normalizing Windows, Linux, and Sysmon logs
- automating alerting and enrichment tasks
- detecting suspicious patterns with scripting
- building reusable utilities that support SOC and IR workflows

---

## Planned Repository Structure

- `docs/` — script explanations, usage notes, templates, and workflow documentation
- `scripts/` — Python, PowerShell, and Bash automation tools
- `lab/` — sample logs, test datasets, screenshots, and script output
- `.github/` — issue or pull request templates (optional)

---

## Planned Lab Setup

This project is planned to use systems and data sources built through the earlier portfolio work.

### Planned Source Systems
Potential script inputs or automation targets may include:

- Windows 10 or Windows 11 systems
- Linux systems such as Ubuntu or Debian
- Sysmon log sources
- exported logs from the Proxmox-based lab
- optional Azure-based logs or cloud-related outputs later where useful

### Planned Runtime Environments
Planned script execution may occur on:

- Windows systems
- Linux systems
- Kali Linux
- WSL where useful
- lab virtual machines hosted in Proxmox

### Planned Tools
Expected tooling may include:

- Python 3.x
- PowerShell
- Bash
- standard system utilities available in Windows or Linux environments

The goal is to build scripts that are practical and easy to test inside the existing lab rather than dependent on heavy external infrastructure.

---

## Planned Automation Focus Areas

### Python Automation
Planned Python automation may include:

- log parsing and normalization
- suspicious pattern detection
- JSON event parsing
- regex-based matching
- simple automated reporting
- enrichment of selected indicators using external sources where appropriate

### PowerShell Automation
Planned PowerShell automation may include:

- failed login review
- Windows Event Log parsing
- security log export
- Defender or security-setting checks
- Sysmon evidence collection
- detection support for brute-force or suspicious activity patterns

### Bash Automation
Planned Bash automation may include:

- SSH log review
- file integrity or configuration checks
- firewall verification
- auditd-related checks
- parsing Linux authentication logs
- user or permission auditing
- simple command-history or suspicious-command review

---

## Planned Workflow

Once execution begins, the intended workflow for this repo is:

### 1. Define a small automation use case
Planned examples may include:

- parsing logs for suspicious activity
- extracting evidence from Windows or Linux systems
- converting raw output into cleaner summaries
- automating repetitive analyst review tasks

### 2. Build the script
Planned activities may include:

- creating a script in Python, PowerShell, or Bash
- testing it against sample logs or live lab output
- improving input handling and output readability
- documenting the script purpose and expected usage

### 3. Validate the output
Planned activities may include:

- running the script against sample data
- comparing results against known lab activity
- saving screenshots or output examples
- refining the logic when false positives or weak parsing are observed

### 4. Store supporting evidence
Planned artifacts may include:

- sample logs in `lab/`
- output screenshots
- markdown usage notes
- script-specific documentation in `docs/`

---

## Planned Example Usage

Example command patterns may later include:

### Python
```bash
python3 scripts/python/log_parser.py sample.log
```

### PowerShell
```powershell
pwsh scripts/powershell/failed_login_detector.ps1
```

### Bash
```bash
bash scripts/bash/update_audit.sh
```

Actual filenames and script structure will be defined as implementation begins.

---

## Planned Deliverables

This repo is expected to eventually include:

- Python log parsing or enrichment tools
- PowerShell Windows analysis or evidence-collection scripts
- Bash Linux auditing or review scripts
- sample logs for testing
- documentation explaining what each script does
- saved output or screenshots showing successful execution

---

## Planned Skill Areas

This project is intended to help build experience in:

- automating repetitive security tasks
- parsing and normalizing logs
- pattern matching and simple detection logic
- Windows, Linux, and Sysmon log handling
- scripting for analyst efficiency
- evidence collection and response support
- using automation to improve repeatability in security workflows

---

## Planned Next Steps

When work begins on this repo, the initial implementation focus will likely be:

- choose the first few automation use cases from the lab
- prepare sample log data and test inputs
- build one Python, one PowerShell, and one Bash script
- document how each script works and what problem it solves
- save execution evidence and sample outputs in a repeatable format

Future expansion may include:

- a Python tool to detect brute-force patterns
- a PowerShell script to export and compress Sysmon logs
- a Bash script to check Linux hardening status
- scripts that query external enrichment sources where appropriate
- a small menu-based toolkit or bundled automation set

---

## Planned Related Projects

### Repo 1 — Security Operations & Detection Engineering
This repo may later use automation to generate, enrich, or support detection-related workflows.

### Repo 2 — Vulnerability Management
This repo may later use automation to help parse scan data, summarize findings, or support risk classification.

---

## License

MIT — see `LICENSE`.
