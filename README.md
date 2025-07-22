# Audible Recon Case Study (HackerOne)

This project is a full-scope recon case study against Audible's public HackerOne program.

It includes passive subdomain enumeration, live host discovery, and recon documentation — all within legal scope.

## 🛠️ Tools Used
- `whois` for domain registration intel
- `amass` for passive subdomain enumeration
- `httpx` for live subdomain probing
- `git` for version-controlled documentation

## 🧠 Key Findings
- 1,071 subdomains discovered with Amass
- 0 responded to automated scanning (likely WAF-protected)
- Indicates high-level CDN/WAF protection across assets
- All recon conducted within legal HackerOne scope

## 📂 Repo Contents
- `recon.md`: Notes and findings
- `subdomains.txt`: Full subdomain list
- `live.txt`: Result of `httpx` scan (empty due to WAF)
- `scope.md`: HackerOne program scope
- `tools-used.md`: List of tools used

## ✅ Status
Recon complete. This repo is part of my ethical hacking portfolio and demonstrates my ability to:
- Work within scope
- Use real tools
- Document recon results professionally
