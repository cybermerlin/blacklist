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
- [ ] add a list of companies w dirty activities (w description about all registered action):
    - [ ] deception of employees
    - [ ] cruel treatment
    - [ ] ignoring environmental protection requirements
    - [ ] abuse of trust
