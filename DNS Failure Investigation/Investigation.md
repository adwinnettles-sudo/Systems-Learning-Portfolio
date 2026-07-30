# DNS Resolution Failure Investigation

## Summary

This investigation examines how DNS failures can prevent access to websites even when general network connectivity is still functioning.

The objective is not simply to restore connectivity but to determine where communication is breaking down and why.

---

# Objectives

- Differentiate DNS failures from general connectivity issues.
- Verify network connectivity.
- Test DNS resolution.
- Interpret the results.
- Document the investigation.

---

# Investigation

## Step 1 — Define the Problem

Assume the following symptom:

A web browser cannot open websites using domain names.

---

## Step 2 — Verify Basic Connectivity

First, determine whether the computer can communicate with external networks.

Possible checks include:

- Local network connectivity
- Default gateway
- Public IP connectivity

If these tests succeed, the network itself may still be functioning correctly.

---

## Step 3 — Compare IP Addresses and Domain Names

Attempt to communicate using:

- A public IP address
- A domain name

If communication succeeds using an IP address but fails using a domain name, DNS becomes a likely point of investigation.

---

## Step 4 — Query DNS

Use:

```cmd
nslookup google.com
```

Observe:

- DNS server used
- Returned IP addresses
- Error messages

These results help determine whether DNS resolution is functioning correctly.

---

## Step 5 — Form a Hypothesis

Possible hypothesis:

The configured DNS server is unavailable or unable to resolve domain names.

---

## Step 6 — Analyze the Evidence

Evidence may include:

- Successful communication by IP
- Failed communication by domain
- DNS query failures

Collectively, these observations increase confidence that DNS is responsible for the issue.

---

## Step 7 — Verify the Resolution

After correcting the DNS configuration or restoring DNS service:

- Repeat the DNS query.
- Test website access.
- Confirm consistent operation.

---

# Lessons Learned

This investigation reinforced several important ideas:

- Internet connectivity does not guarantee DNS is functioning.
- Domain names and IP addresses solve different problems.
- DNS failures can resemble complete network outages.
- Structured troubleshooting reduces unnecessary guesswork.

---

# References

- Microsoft Learn — nslookup
- Microsoft Learn — DNS