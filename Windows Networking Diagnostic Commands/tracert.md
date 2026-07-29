# tracert

## Purpose

Displays the path that packets take from your computer to a destination by listing each router along the route.

## Common Uses

- Identify where a connection is slowing down
- Determine where packets stop reaching the destination
- Visualize the route traffic takes across the internet
- Troubleshoot routing issues

## Common Commands

```cmd
tracert google.com
```

```cmd
tracert 8.8.8.8
```

## What I Learned

`tracert` helped me realize that internet traffic doesn't travel directly from one computer to another. Instead, packets move through multiple routers before reaching their destination.

Seeing each hop made networking feel much less abstract and gave me a better understanding of how large networks communicate.

## Related Commands

- ping
- pathping
- ipconfig

## References

Microsoft Learn - tracert