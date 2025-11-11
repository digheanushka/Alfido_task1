# Alfido_task1
Reconnaissance & Scanning 

# Netdiscover / ARP scanners: help detect live hosts on a local subnet using ARP. Useful for inventory on LANs you control.

# Nmap (scanner): discovers live hosts, open ports, running services and can attempt OS/service fingerprinting — used to map attack surface.

# Passive OSINT/tools: DNS history, public cert transparency logs, search engines, and public code repos to learn about infrastructure without probing.

# Service-specific probes & banners: identify versions from service banners to research known issues (never exploit without permission).

# Vulnerability databases: use vendor CVE databases and advisories to interpret results.

## High-level, legal reconnaissance & scanning workflow (short, conceptual)

1. Get authorization — written permission that names the systems, dates, allowed tests, and contact person.


2. Define scope & rules of engagement — which IPs, domains, ports, test hours, and what is off-limits.


3. Passive reconnaissance (no direct probes) — collect public info: DNS records, WHOIS, public websites, open-source intelligence (OSINT). No scanning tools that touch the target.


4. Active reconnaissance (authorized only) — send probes to discover live hosts, open services, and basic service banners. Keep it minimally intrusive and within scope.


5. Port/service enumeration (authorized only) — identify which services are listening and their versions (to inform safe follow-up testing).


6. Vulnerability identification (authorized only) — map known vulnerabilities for discovered services (non-exploitative checks first).

