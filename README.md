# AdGuard Home Whitelist

## Whitelist Syntax

- Each domain should be listed on a new line.
- Wildcards (\*) can be used to match multiple subdomains.
  - For example, `*.example.com` will match `subdomain.example.com`, `another.example.com`, etc.
- Use a leading dot (.) to match all subdomains of a domain.
  - For example, `.example.com` will match `www.example.com`, `mail.example.com`, etc.
