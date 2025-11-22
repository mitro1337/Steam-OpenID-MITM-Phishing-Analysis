# Steam Ticket

Hello, I would like to report a phishing website that is impersonating Steam in order to steal user accounts through an OpenID MITM attack and Family View abuse.

I reproduced the attack in a controlled sandbox environment (isolated VM, temporary accounts) and confirmed the following:

The website uses a cloned Steam login page.

The form submits credentials through a fake OpenID endpoint.

The attacker attempts to force Family View / Family Sharing takeover to bypass restrictions.

The entire site is based on a stolen template from csreserve.shop.

The domain is hosted on OVH / VPS infrastructure with no real backend logic besides credential forwarding.

Data collected:

Domain: cs2-final.net

Hosting IP: 172.67.175.191

OpenID phishing endpoint: [newxyu, b4bcd]

Method: MITM OpenID, credential harvesting, attempted family takeover

Proof of concept: fully reproduced in an isolated virtual machine. https://www.youtube.com/watch?v=qsYza5weW3E

No real server-side logic apart from credential forwarding

This website is actively attempting to steal Steam accounts.
Please take appropriate action.

Thank you.
## Report Content
<[Open it here](https://help.steampowered.com/en/wizard/HelpRequest/?ticket=4AijpJxDugKEAQOBQoBuRgukfNSOAj21OrqwnZH%2Bj9mtO1nx98DD%2BBErZMj3oibG)>
