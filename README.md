# Black list

This is a project with lists of objects that are attacked.

- [ip](ip): this is a file with SSH knockers and some ports scanners.
    ```sh
    fetch https://raw.githubusercontent.com/cybermerlin/blacklist/main/ip
    pfctl -t black_list -T add -f ip
    ```
- 
