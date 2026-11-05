# Petr Hromádka

SOC analyst based in Ostrava, Czechia. I moved into security operations from enterprise IT support, where I handled incidents under SLAs and managed identities and access in Active Directory and Microsoft Entra ID. In my own time I build small, offline security tools for CI pipelines, container hosts and AI coding agents.

## What I do

- **Alert triage:** review SIEM and EDR alerts, separate real threats from noise, and escalate with clear evidence.
- **Detection:** turn recurring suspicious patterns into queries and rules, and tune the noisy ones.
- **Incident response:** investigate, contain, and write up what happened with a timeline others can follow.
- **Identity and access:** a background in Active Directory and Entra ID, which helps with account compromise, MFA and sign-in investigations.

## Security projects

| Project | What it does | Status |
| --- | --- | --- |
| [gha-warden](https://github.com/petrhromadka/gha-warden) | Static auditor for GitHub Actions workflows: script injection, pwn requests, unpinned actions, over-broad permissions. Runs offline, outputs SARIF for code scanning. | v0.1.2 |
| [container-audit](https://github.com/petrhromadka/container-audit) | Read-only audit of a Docker host: root and privileged containers, mounted Docker socket, secrets in environment variables, exposed ports. Text, JSON, Markdown or SARIF; on PyPI as `docker-host-audit`. | v0.2.0 |
| [claude-code-firewall](https://github.com/petrhromadka/claude-code-firewall) | PreToolUse hook for Claude Code that denies or asks before tool calls matching your own policy rules, and keeps a redacted JSONL audit log. | 0.1.0, no release yet |
| [mcp-warden](https://github.com/petrhromadka/mcp-warden) | Offline scanner for MCP servers and client configs (tool poisoning, rug pulls, tool shadowing, leaked secrets) as a single Rust binary with SARIF output. | In progress |

I also run a self-hosted homelab for AI agent automation.

## Certifications

- Microsoft Certified: Security, Compliance, and Identity Fundamentals ([SC-900](https://learn.microsoft.com/api/credentials/share/en-us/PetrHromdka-3880/1BFA530612DB6FB8?sharingId=D7380B88B57A1857)), March 2025
- Microsoft Certified: Azure Fundamentals ([AZ-900](https://learn.microsoft.com/api/credentials/share/en-us/PetrHromdka-3880/20F65684959F55AE?sharingId=D7380B88B57A1857)), February 2025
- Preparing for SC-200 (Security Operations Analyst)

## Tools and skills

- **Security operations:** SIEM, EDR, alert triage, incident response, threat hunting, OSINT, TryHackMe labs
- **Identity:** Active Directory, Microsoft Entra ID, MFA, Microsoft 365
- **Systems and networking:** Linux, Docker, TCP/IP, DNS, DHCP
- **Code and automation:** Python, PowerShell, SQL, Rust, GitHub Actions, SARIF
- **IT service management:** ServiceNow, ITIL

## Links

- Website: [petrhromadka.cz](https://petrhromadka.cz/en)
- Blog: [petrhromadka.cz/en/blog](https://petrhromadka.cz/en/blog)
- LinkedIn: [Petr Hromádka](https://www.linkedin.com/in/petr-hrom%C3%A1dka-49b4a91a5/)
- Contact: [petrhromadka.cz/en/contact](https://petrhromadka.cz/en/contact)
