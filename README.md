<div align="center">

# Karan Kurani

**Security Researcher · Offensive Security · Vulnerability Disclosure**

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=safari&logoColor=white)](https://kuranikaran.github.io/Portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karan-kurani/)

<img src="https://readme-typing-svg.demolab.com?font=Inter&weight=400&size=16&duration=3000&pause=2000&color=888888&center=true&vCenter=true&repeat=true&width=500&height=24&lines=I+find+real+vulnerabilities+in+real+systems." alt="Typing SVG" />

</div>

<br>

```
CVEs Published          7x CVE's ( CVE-2026-28970, CVE-2026-28898, CVE-2026-44304, CVE-2026-44305, CVE-2026-35627, CVE-2026-32230 & more )
Organizations           14 (Apple · Meta · NASA · OpenAI · JPMC · Infosys …)
Certs                   CRTA · ISC² CC · NCPT · OCI Architect
TryHackMe               Top 1% | Seven Time League Winner #1
NCL                     Top 7% National · #1 at Pace
PortSwigger             100+ Labs
```

<br>

## CVEs & Credited Findings

🔴 Critical · 🟠 High · 🟡 Medium · 🟢 Low · 🤝 Credited · 🏆 Hall of Fame

| Target | Severity | Finding | ID |
|--------|----------|---------|-----|
| React / Next.js | Critical | RCE via exposed RSC endpoints on The Economic Times Admin Portal | `CVE-2025-55182` |
| Netflix/Lemur | High | LDAP filter injection → post-auth privilege escalation to admin | [`CVE-2026-44304`](https://github.com/Netflix/lemur/security/advisories/GHSA-3r34-vq8m-39gh) |
| Netflix/Lemur | Medium | LDAP TLS verification globally disabled → credential interception (MITM) | [`CVE-2026-44305`](https://github.com/Netflix/lemur/security/advisories/GHSA-vr7c-r5gj-j3w5) |
| Apple/swift-nio | Medium | CRLF injection in outbound request URI / method / reason-phrase → smuggling & response splitting | [`CVE-2026-28970`](https://github.com/apple/swift-nio/security/advisories/GHSA-cq87-8r7h-962v) |
| Uptime Kuma | Medium | Missing authorization on monitor pings | [`CVE-2026-32230`](https://github.com/louislam/uptime-kuma/security/advisories/GHSA-c7hf-c5p5-5g6h) |
| Apple/swift-nio-http2 | Low | HTTP/2 → HTTP/1 request smuggling via unvalidated `:path` pseudo-header | [`CVE-2026-28898`](https://github.com/apple/swift-nio-http2/security/advisories/GHSA-4px2-pw77-vc85) |
| Openclaw | High | Nostr inbound DMs trigger crypto/dispatch work before sender-policy enforcement | [`CVE-2026-35627`](https://github.com/openclaw/openclaw/security/advisories/GHSA-65h8-27jh-q8wv) |
| Microsoft/UFO | Medium | Unowned-session squatting via `COMMAND_RESULTS` → persistent authenticated DoS | [`GHSA-hxjv-fmjf-wmjf`](https://github.com/microsoft/UFO/security/advisories/GHSA-hxjv-fmjf-wmjf) |
| Pretix | Medium | Log injection via `request_id_header` | [PR #5920](https://github.com/pretix/pretix/pull/5920) |
| Pretix OIDC | Medium | PKCE values logged to stdout | Responsible Disclosure |
| Metabase | Medium | Sharing bypass exposing datasets | [`GHSA-j3qp-7mr8-hr55`](https://github.com/metabase/metabase/security/advisories/GHSA-j3qp-7mr8-hr55) |
| Ghidra/NSA | Low | Zip Slip path traversal (CWE-22) in Javadoc extraction; fix merged `9ce5c59`, shipped 12.1.3 | [Issue #9272](https://github.com/NationalSecurityAgency/ghidra/issues/9272) |
| Google/fscrypt | Low | Symlink-following in recovery-file write → root `fchown` of attacker target under sudo | [PR #448](https://github.com/google/fscrypt/pull/448) |
| Directus | Credited | Enumeration oracle via RBAC filter bypass | [GHSA-2xcm-7h22-3m66](https://github.com/directus/directus/security/advisories/GHSA-2xcm-7h22-3m66) |
| JPMorgan Chase | Hall of Fame | Internal hostnames in prod JS | [`Synack RD #690`](https://responsibledisclosure.jpmorganchase.com/hc/en-us/articles/360023828114-Recognition-for-Responsible-Disclosures#:~:text=Subadevan%20C-,Karan%20Kurani,-linkedin.com/in) |

<sub>Additional disclosures to NASA · OpenAI · Microsoft · Mercedes-Benz · Infosys (CERT-In acknowledged)</sub>

<br>

## Tech

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JS](https://img.shields.io/badge/JS-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PowerShell](https://img.shields.io/badge/PS-5391FE?style=flat-square&logo=powershell&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

![Burp](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=hackthebox&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-FF0000?style=flat-square)
![IDA](https://img.shields.io/badge/IDA_Pro-4B275F?style=flat-square)
![Semgrep](https://img.shields.io/badge/Semgrep-4B11A8?style=flat-square)
![ASan](https://img.shields.io/badge/ASan-000000?style=flat-square)

![Kali](https://img.shields.io/badge/Kali-557C94?style=flat-square&logo=kalilinux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-3CBCE8?style=flat-square)
![Splunk](https://img.shields.io/badge/Splunk-000000?style=flat-square&logo=splunk&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/ATT%26CK-ED1C24?style=flat-square)

</div>

<br>

## Now

```
🔬 Fuzzing Fang engine's for memory corruption bugs
🔍 Source code auditing high-star open-source projects
⚡  Manual + Multi-LLM workflow 
🏆 OSCP | BSCP Prep 
🏴󠁡󠁦󠁷󠁡󠁲󠁿 Hands'on Offsec | THM | HTB | Portswigger
```

<br>

<div align="center">

![CRTA](https://img.shields.io/badge/CRTA-DC143C?style=flat-square)
![ISC² CC](https://img.shields.io/badge/ISC²_CC-006400?style=flat-square)
![NCPT](https://img.shields.io/badge/NCPT-FF8C00?style=flat-square)
![OCI](https://img.shields.io/badge/OCI_Architect-F80000?style=flat-square)

<br>

<img src="https://github-readme-stats.vercel.app/api?username=kuranikaran&show_icons=true&theme=transparent&hide_border=true&hide_title=true&text_color=888888&icon_color=888888" width="420" />

<img src="https://komarev.com/ghpvc/?username=kuranikaran&style=flat-square&color=888888" />

</div>
