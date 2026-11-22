# DDoS Protected Hosting: Is Free Protection Enough, What Do Paid Tiers Add, and Which AVA Hosting VPS Plan Fits Your Site? (Full Plan and Price Table)

Hosting providers sell DDoS protection in three tiers, and the free tier bundled with most plans catches only the small attacks. Liquid Web's public pricing page puts numbers on the gap: included protection covers volumetric Layer 4 attacks up to 2 Gbps, a $99/month-per-server add-on raises that to 10 Gbps, and only the $499/month-per-account tier claims "complete protection" against complex or sustained attacks (prices as published on that page in February 2025).

AVA Hosting takes the simpler route. Every VPS in its store lists free DDoS protection, and the cheapest broadly usable one, VPS One, costs €5.00/month for 1 vCPU, 2 GB RAM and 25 GB NVMe. What the store page does not publish is how much mitigation capacity sits behind the word "free", and that number is the first thing to chase down before you buy from anyone.

Below: the full AVA Hosting VPS lineup with prices, what actually separates a free tier from a paid one, the security work DDoS protection does not do, and which plan suits which kind of site.

> **Quick pick:** One site or one app: VPS One at €5.00/month. A WooCommerce store or several client sites: VPS Basic at €10.00/month or VPS Lucky at €15.00/month. Both tiers include free DDoS protection, weekly backups, full root access, a control panel and a 99.9% SLA. The €11/year VPS Nano only makes sense if 512 MB RAM and a 100 Mbps port genuinely match your workload.
> 👉 [Check current AVA Hosting VPS plans and prices](https://my.ava.hosting/aff.php?aff=15562)

## AVA Hosting VPS plans compared

| Plan | vCPU / RAM | Storage / Port | Price | Order |
| --- | --- | --- | --- | --- |
| VPS Nano | 1 vCPU / 512 MB ECC | 20 GB NVMe / 100 Mbps | €11.00 / year | [Order VPS Nano](https://my.ava.hosting/aff.php?aff=15562) |
| VPS One | 1 vCPU / 2 GB ECC | 25 GB NVMe / 1 Gbps | €5.00 / month | [Order VPS One](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Basic | 2 vCPU / 4 GB ECC | 50 GB NVMe / 1 Gbps | €10.00 / month | [Order VPS Basic](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Lucky | 2 vCPU / 6 GB ECC | 70 GB NVMe / 1 Gbps | €15.00 / month | [Order VPS Lucky](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Power | 4 vCPU / 8 GB ECC | 90 GB NVMe / 1 Gbps | €20.00 / month | [Order VPS Power](https://my.ava.hosting/aff.php?aff=15562) |
| VPS Extra | 6 vCPU / 12 GB ECC | 120 GB NVMe / 1 Gbps | €30.00 / month | [Order VPS Extra](https://my.ava.hosting/aff.php?aff=15562) |

Every plan carries unlimited bandwidth, Intel Xeon E5 hardware, NVMe storage, free DDoS protection, weekly backups, full root access, a control panel, 99.9% SLA uptime and 24/7 support. Port 25 is closed on the Nano.

Two details worth noticing before you pick a row. The Nano bills annually at €11.00, which works out under €1 a month, but it ships a quarter of the RAM and one tenth the port speed of VPS One, and the store listed it as 0 available. The jump from Basic (€10) to Lucky (€15) buys 2 GB more RAM and 20 GB more NVMe, which is the cheapest meaningful upgrade in the lineup if you are running a database alongside a web server.

AVA also sells shared hosting from €1.99/month with cPanel and daily automated backups, on the same network with DDoS protection on all plans. If you do not want to administer a server at all, that is the simpler starting point.

## Free protection versus paid protection

The Liquid Web tier table is the clearest public example of how this market is priced, and it is worth reading line by line:

- **Free**: small targeted attacks, Layer 4 volumetric traffic up to 2 Gbps
- **$99/month per server**: adds large targeted attacks, up to 10 Gbps
- **$499/month per account**: adds complex or sustained attacks, described as complete protection

Two things follow from that. First, "DDoS protected" on a feature list tells you almost nothing on its own, because the same provider sells three very different ceilings under one label. Second, the billing unit matters as much as the price. At $99 per server, ten servers cost $990 a month; the $499 per-account tier covers all of them, so multi-server operators get a better deal from the top tier while a single-server user pays five times more than they need to.

Independent guidance points the same direction on capacity. Liquid Web's own buyer's guide suggests looking for at least 10 to 100 Gbps of mitigation for most businesses, and notes that the more bandwidth a network can absorb, the more resilient the site is under pressure. By that yardstick the $99 tier sits at the bottom of the recommended range, not the middle.

OVHcloud shows the other pricing model: DDoS protection included in every VPS at no extra cost, unmetered mitigation, always-on, with no separate tier to buy. For a small site that wants protection without a line item, that is a genuinely easier arrangement, and it costs nothing to say so.

AVA Hosting sits in the same camp as OVHcloud on pricing structure: protection is bundled into every plan rather than sold as an upgrade. A third-party review of the provider reports a hardened data centre in Chișinău, Moldova, a network channel around 50 Gbit/s and DDoS mitigation capacity in the hundreds of Gbps. Treat those figures as third-party reporting, because the official store page says only "Free DDoS Protection" and does not state a capacity ceiling or publish tiers. That gap is exactly what to close with a pre-sales question.

👉 [See what each AVA Hosting VPS plan includes](https://my.ava.hosting/aff.php?aff=15562)

## What DDoS protection does not cover

This is where most buyers overspend or under-protect. Liquid Web's own breakdown of what a DDoS-protected plan bundles is a useful checklist, because it shows how narrow the core feature is:

| Security feature | Included in DDoS-protected hosting? |
| --- | --- |
| DDoS mitigation | Yes |
| Web application firewall | Often, but not always |
| Malware scanning | Sometimes |
| SSL certificate | Often |
| Regular backups | Usually optional or add-on |

Traffic floods and protocol attacks are covered. SQL injection, cross-site scripting and HTTP floods need a WAF. Infected plugins and backdoors need malware scanning. Ransomware and accidental deletion need backups. Those are three different purchases, and a plan that advertises DDoS protection may include none of them.

A basic VPS and a DDoS-protected VPS differ on more than one row. The protected setup typically adds traffic filtering that goes beyond basic rules, access to scrubbing centres, built-in redundancy and failover, and 24/7 proactive monitoring rather than occasional checks. Cloudflare-style CDN integration is often optional on a plain VPS and included on a protected one.

Against that checklist, AVA Hosting is partially transparent. Weekly backups are listed as included on every VPS plan, which is better than the "usually optional" industry norm. WAF and malware scanning do not appear in the plan feature list, so ask directly whether a WAF sits in front of the VPS or whether you are expected to run ModSecurity or a CDN yourself. The provider's own SLA wording is also narrow about what is covered: power and network at the Chișinău data centre plus DDoS protection on all plans, but not downtime caused by your own applications, software or misconfiguration. No host covers the last part, and it is worth knowing before you buy.

## Can any host stop 100% of attacks?

No, and the honest providers say so. OVHcloud's own product page states that while a DDoS-protected VPS offers robust defence against most attacks, "no solution can guarantee 100% mitigation in all cases."

Whether an attack gets through depends on four variables: the size of the flood relative to the provider's mitigation capacity, how complex and how long the attack runs, whether it targets Layer 4 or your application layer, and whether your own stack has a weakness the attacker can reach. A 2 Gbps ceiling is fine against a bored attacker with a booter script. It is not fine against a sustained 50 Gbps campaign, and no amount of scrubbing fixes a vulnerable WordPress plugin.

That is the practical argument for buying capacity in proportion to what you actually stand to lose, rather than buying the biggest number on the page.

## Which tier fits which site

**Personal blogs, landing pages, staging environments.** The bundled protection is enough, and paying for a mitigation upgrade is wasted money. VPS One at €5.00/month covers this comfortably. If the attack risk you actually face is comment spam and login brute-forcing, a WAF or a CDN in front of the site does more for you than extra Gbps.

**E-commerce and online retail.** Peak sales periods are exactly when attacks land, and downtime during a promotion costs revenue immediately and customer trust afterwards. VPS Basic at €10.00/month or Lucky at €15.00/month, plus a WAF and tested backups, is the sensible floor.

**Game servers.** Attacks are often aimed at disrupting a match or gaining a competitive edge, and game traffic needs protocol-aware filtering at Layer 7, not just volumetric scrubbing. Ask specifically whether the protection handles the protocols you run.

**Agencies hosting multiple client sites.** One attacked site can drag down everything on the box and damage your reputation with every client on it. The 6 vCPU / 12 GB VPS Extra at €30.00/month exists for this, and per-account protection pricing (the model Liquid Web uses at $499/month) is worth asking about if you expect to spread across several servers.

**Financial, government and public service portals.** Downtime here involves sensitive data and public credibility. Look for compliance support and enhanced security options on top of mitigation, and expect to document your SLA.

**High-traffic media and social platforms.** These are the primary targets for large volumetric attacks, and this is the one category where paying for high-capacity mitigation and a CDN with global distribution is straightforwardly justified.

👉 [Compare the AVA Hosting VPS tiers side by side](https://my.ava.hosting/aff.php?aff=15562)

## FAQ

**Is free DDoS protection enough for a small site?**
For the attacks small sites usually receive, yes. It stops being enough when someone targets you specifically with a sustained campaign or with application-layer traffic that looks like normal requests. The question to ask any provider is the mitigation capacity in Gbps, not whether protection is "included".

**Is the €11/year VPS Nano worth it?**
Only if 512 MB RAM and a 100 Mbps port are all you need. VPS One gives you four times the RAM and a 1 Gbps port for €5.00/month, which is €60 a year against €11. The Nano is genuinely cheaper, but it is a different class of machine, and the store showed 0 available.

**Will a DDoS attack hurt my search rankings?**
Indirectly. Search engines do not penalise you for being attacked, but extended downtime and slow responses damage rankings and click-through over time. Uptime protection is the ranking argument, not the size of the mitigation tier.

**Do I need a WAF if I already have DDoS protection?**
If your site has logins, forms, search boxes or a CMS, yes. DDoS mitigation filters floods; a WAF filters the requests that look legitimate and are not.

## Before you order

Match the plan to the workload, not to the fear: one app or one site goes on VPS One at €5.00/month, a store or a handful of client sites on Basic or Lucky, and anything CPU-hungry on Power or Extra. Then confirm three things in writing before you pay, whichever provider you choose.

1. Is DDoS protection included on the plan you are buying, and what is the mitigation capacity ceiling?
2. Is there a WAF, or application-layer filtering, and is it extra?
3. What does the SLA actually cover, and what counts as excluded downtime?

AVA Hosting answers the first question clearly (included on every plan) and the third honestly (network and power, not your own application errors). The second is the one to ask.

👉 [Open the AVA Hosting VPS store and pick a plan](https://my.ava.hosting/aff.php?aff=15562)
