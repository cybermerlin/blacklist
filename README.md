# Black list

List of scammers and angry bots.
This is a project with lists of objects that are attacked.

- [ip](ip): this is a file with SSH knockers and some ports scanners + http DDoS attackers and vulnerabilities scanners.
    ```sh
    fetch https://raw.githubusercontent.com/cybermerlin/blacklist/main/ip
    pfctl -t black_list -T add -f ip
    ```
- [phone](phone): spammers or scammers
