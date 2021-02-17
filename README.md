# Wordpress 4.7
This repository is used to demonstrate the XSS vulnerability in Wodpress 4.7.0 allowing the attacker to gain complete control over the site.

- Known as [CVE-2017-1001000](https://www.cvedetails.com/cve/CVE-2017-1001000/)
- Metasploit: [auxiliary/scanner/http/wordpress_content_injection](https://www.rapid7.com/db/modules/auxiliary/scanner/http/wordpress_content_injection/)
- Fixed: in the 4.7.1 and 4.7.2 patches.

## Setup
Run docker compose to run Wordpress 4.7.0 on port 8080.
```
docker-compose up
```
