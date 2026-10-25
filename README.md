# SOC Playbook

Command references and step-by-step procedures for SOC triage, phishing analysis, and Windows host investigation.

## Playbooks

| Section | Covers |
|---|---|
| `Identify/` | Network discovery and packet capture with nmap and tcpdump |
| `Phishing/` | Email header examination, content examination, and static malware analysis |
| `Windows Investigation/` | Host investigation of accounts, processes, services, scheduled tasks, registry, network connections, and logs |
| `Log Analysis/` | Reviewing and correlating logs during an investigation |

## How to use

Start with **Identify** to scope the activity, then move to the playbook that matches the incident. For a suspected compromised Windows host, begin with `Windows Investigation/Investigation.txt` and work through each area for signs of persistence or lateral movement.

## License

GPL-3.0
