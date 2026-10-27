# Security

## Reporting a problem

If you find a security problem in ShaferWare DNS Monitor (for example, a way its API token could be exposed
or misused), please report it privately instead of opening a public issue:

- Use **Security > Report a vulnerability** on this repository, or
- use the contact form at https://shaferware.com/contact/.

Include the DNS Monitor version, your Windows version, your Technitium version and the steps to reproduce it.

## Protect your API token

- Never post your API token in an issue, screenshot or log. DNS Monitor never writes the full token to its log;
  when a token is rejected it logs only its length and first and last 4 characters.
- If a token may have leaked, delete it in Technitium under **Administration > Sessions** and create a new one.
- Use a Technitium user with **Dashboard: View** permission only, as described in the README.

## Before you post anything

Bug reports and logs are public. Do not post personal information: names, email addresses, IP addresses,
computer or user names, or file paths that contain your Windows user name. `dnsmonitor.log` and `test.txt`
contain your server's address, so replace it with something like `SERVER-IP` before you paste them.

## Supported versions

Only the latest release receives fixes.
