## Subdomain Discovery (Amass)

Ran: `amass enum -passive -d audible.com -o subdomains.txt`

Discovered 1,071 unique subdomains related to audible.com using passive reconnaissance.

Subdomains saved to `subdomains.txt`

Examples:
- www.audible.com
- api.audible.com
- mobile.audible.com
- help.audible.com

# WHOIS Results for audible.com

- Registrar: MarkMonitor Inc.
- Registrant Organization: Audible, Inc.
- Domain Status:
  - clientDeleteProhibited
  - clientTransferProhibited
  - clientUpdateProhibited
- Name Servers:
  - ns1.p24.dynect.net
  - ns2.p24.dynect.net
  - ns3.p24.dynect.net
  - ns4.p24.dynect.net
- Updated: 2024-07-12
- Created: 1995-10-31
- Expiry: 2025-10-30

## Live Subdomain Scan (httpx - advanced)

Ran:
httpx -l subdomains.txt -o live.txt -H "User-Agent: Mozilla/5.0" -random-agent -follow-redirects -status-code -title -tech-detect

Results:
- 0 subdomains responded to automated `httpx` scanning
- This likely indicates the use of strict WAF/CDN protection (e.g., Akamai, CloudFront, Cloudflare)
- Manual inspection or browser-based recon may be required
- This is a valid recon outcome — the assets are public, but aggressively protected from headless scanners

