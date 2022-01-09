# CVE-2021-26294 Exploit
Directory Traversal in Afterlogic webmail aurora and pro .

Description: AfterLogic Aurora and WebMail Pro products with 7.7.9 and all lower versions are affected by this vulnerability, simply sending an HTTP GET request to WebDAV EndPoint with built-in “caldav_public_user@localhost” and it’s the predefined password “caldav_public_user” allows the attacker to read all files under the web root.

## Usage  
```bash
python3 CVE-2021-26294.py http(s)://target:port
```

## Author
[D0rkerDevil](https://twitter.com/D0rkerDevil)
