# HVAC Case Controller Playbook (Educational)

Python **stdlib-only** playbook for refrigerated cases: probes-first order of ops, defrost history (TIME vs TEMP), EEV hunting as upstream symptom.

> **Educational only — verify with OEM docs/apps (e.g. Cold Chain Connect).**

## Quick start

```bash
cd hvac-case-controller-playbook
python3 case_controller_playbook.py --focus full
python3 case_controller_playbook.py --focus defrost-history
python3 case_controller_playbook.py -i
```
