# IP Lists

## Purpose

Some simple IP lists to use in firewall tools like [pfBlockerNG](https://docs.netgate.com/pfsense/en/latest/packages/pfblocker.html).
These lists exist elsewhere but may not be in a format that is useable for me.

I primarily use these lists to block grey noise in my firewall logs.

## Methodology

Scanners seen frequenting my firewall logs are added to their respective list.  If a bit of research on the scanner identifies a website that provides the IPs/Subnets they use for scanning, those will be the basis for the listing. If IPs/Subnets are not provided or the scanner does not keep their website up to date or uses IPs outside those published those will also be added.  The source of the IPs is listed when available, otherwise they should be assumed to be from the firewall logs of me or another contributor.  Contributions are verified prior to merging pull requests.

Lists should be limited to IPv4 based addresses for the time being.

## Contribution

If you find inaccuracies in these lists, please submit a pull request to fix the issue or open an issue to document the discrepancy and I will get it fixed.
