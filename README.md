<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Petr Hromádka, SOC analyst in Ostrava, Czechia" src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://petrhromadka.cz/en"><img alt="Website" src="https://img.shields.io/badge/petrhromadka.cz-0e7490?style=for-the-badge&logo=astro&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/petr-hrom%C3%A1dka-49b4a91a5/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0iI2ZmZiI%2BPGNpcmNsZSBjeD0iNSIgY3k9IjUiIHI9IjIuMyIvPjxyZWN0IHg9IjMiIHk9IjkiIHdpZHRoPSI0IiBoZWlnaHQ9IjEyIi8%2BPHBhdGggZD0iTTEwIDloMy44djEuOGMuNi0xLjEgMi0yLjEgNC0yLjEgMy42IDAgNC4yIDIuNCA0LjIgNS40VjIxaC00di02YzAtMS40IDAtMy4yLTItMy4ycy0yLjIgMS41LTIuMiAzLjFWMjFIMTB6Ii8%2BPC9zdmc%2B"></a>
  <a href="https://petrhromadka.cz/en/blog"><img alt="Blog" src="https://img.shields.io/badge/Blog-24292f?style=for-the-badge&logo=rss&logoColor=white"></a>
  <a href="https://petrhromadka.cz/en/contact"><img alt="Contact" src="https://img.shields.io/badge/Contact-24292f?style=for-the-badge&logo=minutemailer&logoColor=white"></a>
</p>

I work in a security operations center: I triage alerts, investigate what is real, and escalate with evidence. I came from enterprise IT support, where I handled incidents under SLAs and managed identities in Active Directory and Microsoft Entra ID, so account compromise and sign-in investigations are where I feel at home.

Outside work I build small, offline security tools and run a homelab for AI agent automation.

## Security tools

<table>
  <tr>
    <td colspan="2" valign="top">
      <h3><a href="https://github.com/petrhromadka/agent-canary">agent-canary</a></h3>
      <p>Canary tokens for AI coding agents. Plants decoy API keys, SSH keys and config files in a workspace, then flags when an agent sends them out over DNS or HTTP or leaks them into its transcript. Built for red-team and prompt-injection testing; standard library only.</p>
      <img alt="Version 0.1.0" src="https://img.shields.io/badge/version-0.1.0-0e7490?style=flat-square">
      <img alt="Python" src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white">
      <img alt="Honeytokens" src="https://img.shields.io/badge/honeytokens-6e7781?style=flat-square">
      <img alt="Prompt injection" src="https://img.shields.io/badge/prompt%20injection-6e7781?style=flat-square">
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/petrhromadka/gha-warden">gha-warden</a></h3>
      <p>Static auditor for GitHub Actions workflows. Finds script injection, pwn requests, unpinned actions and over-broad permissions, offline, with SARIF output for code scanning.</p>
      <img alt="Latest release" src="https://img.shields.io/github/v/release/petrhromadka/gha-warden?style=flat-square&label=release&color=0e7490">
      <img alt="Python" src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white">
      <img alt="SARIF" src="https://img.shields.io/badge/SARIF-6e7781?style=flat-square">
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/petrhromadka/container-audit">container-audit</a></h3>
      <p>Read-only audit of a Docker host: root and privileged containers, a mounted Docker socket, secrets in environment variables, exposed ports. On PyPI as <code>docker-host-audit</code>.</p>
      <img alt="Latest release" src="https://img.shields.io/github/v/release/petrhromadka/container-audit?style=flat-square&label=release&color=0e7490">
      <img alt="Python" src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white">
      <img alt="Docker" src="https://img.shields.io/badge/Docker-1d63ed?style=flat-square&logo=docker&logoColor=white">
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/petrhromadka/claude-code-firewall">claude-code-firewall</a></h3>
      <p>Policy hook for Claude Code that blocks or asks before tool calls matching your rules, and keeps a redacted JSONL audit log you can ship to a SIEM.</p>
      <img alt="Version 0.1.0" src="https://img.shields.io/badge/version-0.1.0-0e7490?style=flat-square">
      <img alt="Python" src="https://img.shields.io/badge/Python-3776ab?style=flat-square&logo=python&logoColor=white">
      <img alt="AI agents" src="https://img.shields.io/badge/AI%20agents-6e7781?style=flat-square">
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/petrhromadka/mcp-warden">mcp-warden</a></h3>
      <p>Offline scanner for MCP servers and client configs: tool poisoning, rug pulls, tool shadowing and leaked secrets, as a single Rust binary.</p>
      <img alt="Status: in progress" src="https://img.shields.io/badge/status-in%20progress-9a6700?style=flat-square">
      <img alt="Rust" src="https://img.shields.io/badge/Rust-b7410e?style=flat-square&logo=rust&logoColor=white">
      <img alt="SARIF" src="https://img.shields.io/badge/SARIF-6e7781?style=flat-square">
    </td>
  </tr>
</table>

## What I work with

| | |
| :-- | :-- |
| **Security operations** | `SIEM` `EDR` `Alert triage` `Incident response` `OSINT` `TryHackMe` |
| **Identity** | `Active Directory` `Microsoft Entra ID` `MFA` `Microsoft 365` |
| **Systems** | `Linux` `Docker` `TCP/IP` `DNS` `DHCP` |
| **Automation** | `Python` `PowerShell` `SQL` `GitHub Actions` |
| **Service management** | `ServiceNow` `ITIL` |

## Certifications

<p>
  <a href="https://learn.microsoft.com/api/credentials/share/en-us/PetrHromdka-3880/1BFA530612DB6FB8?sharingId=D7380B88B57A1857"><img alt="SC-900" src="https://img.shields.io/badge/SC--900-Security%2C%20Compliance%20%26%20Identity-0078d4?style=flat-square"></a>
  <a href="https://learn.microsoft.com/api/credentials/share/en-us/PetrHromdka-3880/20F65684959F55AE?sharingId=D7380B88B57A1857"><img alt="AZ-900" src="https://img.shields.io/badge/AZ--900-Azure%20Fundamentals-0078d4?style=flat-square"></a>
  <img alt="SC-200 in progress" src="https://img.shields.io/badge/SC--200-in%20progress-6e7781?style=flat-square">
</p>
