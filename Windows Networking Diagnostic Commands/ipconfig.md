# ipconfig

## Purpose

Displays the current IP configuration of the computer.

## Common Uses

- Verify the assigned IP address
- View the default gateway
- Confirm the active network adapter
- Refresh DHCP information
- Clear the local DNS cache

## Common Commands

```cmd
ipconfig
```

```cmd
ipconfig /all
```

```cmd
ipconfig /flushdns
```

```cmd
ipconfig /renew
```

## What I Learned

Before learning this command, I thought networking problems generally occurred somewhere "on the Internet." Using `ipconfig` helped me understand that many issues can begin with the local machine itself, such as an incorrect IP configuration or a stale DNS cache.

## References

Microsoft Learn - ipconfig