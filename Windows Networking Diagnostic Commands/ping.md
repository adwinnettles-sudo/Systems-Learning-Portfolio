# ping

## Purpose

Tests basic network connectivity between your computer and another device by sending ICMP (Internet Control Message Protocol) Echo Requests and measuring whether a response is received.

## Common Uses

- Verify basic network connectivity
- Check whether a host is reachable
- Measure approximate network latency
- Identify packet loss during communication

## Common Commands

```cmd
ping google.com
```

```cmd
ping 8.8.8.8
```

```cmd
ping localhost
```

## What I Learned

Before using `ping`, I assumed that a successful internet connection meant every network service was functioning correctly. I learned that `ping` answers a much more specific question: *Can my computer communicate with another device at the network layer?*

A successful ping doesn't necessarily mean a website or application is working, but it provides a quick way to determine whether basic connectivity exists.

## Related Commands

- tracert
- nslookup
- ipconfig

## References

Microsfot Learn - ping