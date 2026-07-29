# nslookup

## Purpose

Queries Domain Name System (DNS) servers to determine how domain names resolve to IP addresses.

## Common Uses

- Verify DNS resolution
- Compare responses from different DNS servers
- Troubleshoot DNS-related connectivity issues
- Retrieve DNS records

## Common Commands

```cmd
nslookup google.com
```

```cmd
nslookup openai.com
```

```cmd
nslookup google.com 8.8.8.8
```

## What I Learned

Learning `nslookup` helped me separate DNS problems from general internet connectivity problems.

I also learned that a website can be unreachable for reasons unrelated to DNS, and that querying a DNS server directly provides insight into how domain names are being resolved.

## Related Commands

- ping
- ipconfig
- tracert

## References

Microsoft Learn - nslookup