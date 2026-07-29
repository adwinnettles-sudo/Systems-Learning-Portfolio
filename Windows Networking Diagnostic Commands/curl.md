# curl

## Purpose

Sends HTTP requests directly from the command line, allowing you to inspect how a web server responds without using a web browser.

## Common Uses

- Verify website accessibility
- Inspect HTTP response headers
- Test APIs
- Compare server responses during troubleshooting

## Common Commands

```cmd
curl https://example.com
```

```cmd
curl -I https://example.com
```

## What I Learned

While troubleshooting connectivity issues, I learned that `curl` provides a perspective different from a web browser. Browsers include many additional features, whereas `curl` focuses on the raw HTTP request and response.

Using both tools together made it easier to determine whether an issue was related to the network, the web server, or the browser itself.

## Related Commands

- ping
- nslookup
- tracert

## References

Windows Learn - cURL