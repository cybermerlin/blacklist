# Black list

List of scammers and angry bots.
This is a project with lists of attacking objects.

- [ip](ip): this is a file with SSH knockers and some ports scanners + http DDoS attackers and vulnerabilities scanners.
    ```sh
    fetch https://raw.githubusercontent.com/cybermerlin/blacklist/main/ip
    pfctl -t black_list -T add -f ip
    ```
- [phone](phone): spammers or scammers
- [email](email): spammers or scammers
- [ip.2way](ip.2way): IP for blocking anyway (in and out), w no conditions, just block it always. This file will filled by Snort when some virus or external activities will send our data from our system or will catch some data through unprivileged processes. (e.g. Ad-net, statistic catcher (ad.ya.ru, ad.google.com, msftncsi.com, ad.mail.ru, trk.mail.ru, mc.yandex.ru...)

**Banner-blacklist**
- [banners | Ad](ip.ad) IP of ad-servers


## TODO

- [ ] add commands \ instructions to apply blacklist
- [ ] add using [DNSBL](https://www.dnsbl.info/) to get and check adresses in blacklist
    - [ ] <details>  <summary>Click to expand to see all servers w BL</summary>
            ```
all.s5h.net	 b.barracudacentral.org	 bl.0spam.org
 bl.spamcop.net	 blacklist.woody.ch	 bogons.cymru.com
 combined.abuse.ch	 db.wpbl.info	 dnsbl-1.uceprotect.net
 dnsbl-2.uceprotect.net	 dnsbl-3.uceprotect.net	 dnsbl.dronebl.org
 drone.abuse.ch	 duinv.aupads.org	 dyna.spamrats.com
 ips.backscatterer.org	 korea.services.net	 noptr.spamrats.com
 orvedb.aupads.org	 proxy.bl.gweep.ca	 psbl.surriel.com
 rbl.0spam.org	 relays.bl.gweep.ca	 relays.nether.net
 singular.ttk.pte.hu	 spam.abuse.ch	 spam.dnsbl.anonmails.de
 spam.spamrats.com	 spambot.bls.digibase.ca	 spamrbl.imp.ch
 spamsources.fabel.dk	 ubl.lashback.com	 ubl.unsubscore.com
 virus.rbl.jp	 wormrbl.imp.ch	 z.mailspike.net
            ```
    </details>
- [ ] add a list of companies w dirty activities (w description about all registered action):
    - [ ] deception of employees
    - [ ] cruel treatment
    - [ ] ignoring environmental protection requirements
    - [ ] abuse of trust
