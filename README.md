# Theory MCG apex redirect

Serves the naked domain `theorymcg.com` on GitHub Pages and redirects it to
`https://www.theorymcg.com`, preserving path, query and hash.

Why GitHub: DNS stays on Wix, and Wix DNS cannot CNAME or flatten an apex to
Cloudflare Pages. GitHub Pages gives free apex A records and a certificate,
independent of any Wix hosting plan.

Wix DNS apex A records point here:
185.199.108.153 / 185.199.109.153 / 185.199.110.153 / 185.199.111.153

The real site is on Cloudflare Pages at `apestudios-theorymcg`.

Note: the registrar for this domain is GoDaddy (renews 2027-08-14), but the
nameservers are Wix (ns14/ns15.wixdns.net), so the records live in the Wix
DNS panel. Google Workspace MX for @theorymcg.com is on the same zone.
