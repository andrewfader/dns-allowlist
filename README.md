# dns-allowlist

A short, hand-kept DNS allowlist for a home router running Diversion with the oisd blocklist.

Use `https://raw.githubusercontent.com/andrewfader/dns-allowlist/main/allowlist.txt` as the hosted allowlist URL.

Rules for adding an entry:

- An entry un-blocks itself and every subdomain, so add the most specific host that fixes the problem.
- No hosting-provider or CDN suffixes that anyone can publish under.
- No paste sites, URL shorteners, redirectors or file drops.
- The domain must resolve and belong to who you think it does.
