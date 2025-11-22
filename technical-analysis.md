# Technical Analysis

## Environment
- Host OS isolated  
- Windows 10 Virtual Machine with Oracle VirtualBox  
- NAT network  
- Two temporary Steam accounts with Tempmail  
- VM deleted after analysis

## Attack Flow
1. Victim reaches "vote for skin" fake page  
2. Fake Steam login button appears  
3. OpenID MITM redirect steals credentials  
4. Attacker attempts family view lock  
5. Inventory hijack becomes possible

## Frontend Findings
- CSReserve-style template  
- Minified js bundles  
- Hardcoded endpoints  
- No legitimate steam assets  
- Suspicious openid parameters

## Backend Findings (Inferred)
- Lightweight credential forwarder  
- Disposable VPS from British Virgin Islands  
- No real API logic  
- Minimal session handling

## Mitigation
- Never log into Steam outside of steamcommunity.com  
- Use Steam Guard  
- Avoid unknown family sharing invites  
- Report phishing domains immediately
