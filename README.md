# soc-detection-engineering-lab
Home SOC lab for detection engineering — Wazuh, Shuffle, TheHive, Cortex

## About This Project
This lab simulates a real-world SOC pipeline to practice detection engineering, alert triage, and automation. It demonstrates how endpoint telemetry can be transformed into actionable security cases using SIEM and SOAR tooling.

## Key Capabilities
- Endpoint telemetry collection via Sysmon + Wazuh
- Alert triage using severity-based filtering
- Automated enrichment using threat intelligence APIs
- Case creation and management in TheHive
- Detection development mapped to MITRE ATT&CK

## Stack
| Component | Role | Host |
|---|---|---|
| Wazuh | SIEM / log collection | Vultr cloud VM |
| Shuffle | SOAR / automation | Vultr cloud VM |
| TheHive + Cortex | Case management / enrichment | Vultr cloud VM |
| Windows 10 VM | Victim endpoint | Local (VMware) |
| Atomic Red Team | Attack simulation | Local (VirtualBox) |

## Architecture
![Lab Architecture](docs/architecture/lab-architecture-v1.png)

## Build Phases
- [x] Phase 0 — Architecture design + cloud account setup
- [ ] Phase 1 — Wazuh manager + Windows agent + Sysmon
- [ ] Phase 2 — TheHive + Cortex deployment
- [ ] Phase 3 — Shuffle SOAR integration
- [ ] Phase 4 — Custom detection rules + attack simulation

# Detections
Each detection is organized by MITRE ATT&CK tactic.
Folders are created as detections are written.

| Detection | Tactic | Status |
|---|---|---|
| Coming soon | — | — |
