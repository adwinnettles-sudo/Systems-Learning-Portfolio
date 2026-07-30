# Network Troubleshooting Workflow

Rather than immediately searching for a solution, I approach network problems by moving from the simplest possible explanation toward more complex causes.

Each step either confirms part of the network is functioning correctly or helps narrow down where the failure is occurring.

---

# Step 1 — Define the Problem

Determine exactly what is failing.

Questions to consider:

- Is there no internet connection?
- Is only one website unavailable?
- Is the issue affecting one device or multiple devices?
- Did the problem begin after a recent change?

Clearly defining the issue prevents unnecessary troubleshooting.

---

# Step 2 — Check Physical Connectivity

Before investigating software, verify the physical connection.

Examples include:

- Ethernet cable connected
- Wi-Fi enabled
- Router powered on
- Network adapter functioning

Simple physical issues can produce symptoms similar to software failures.

---

# Step 3 — Verify Local Network Configuration

Inspect the local network configuration.

Useful commands include:

- `ipconfig`
- `ipconfig /all`

Confirm:

- IP Address
- Default Gateway
- DNS Server

An incorrect configuration can prevent communication before traffic ever leaves the local network.

---

# Step 4 — Test Local Connectivity

Determine whether the computer can communicate within the local network.

Examples include:

- Ping localhost
- Ping the default gateway

Successful responses indicate that the local networking stack is functioning correctly.

---

# Step 5 — Test External Connectivity

Determine whether traffic can leave the local network.

Examples include:

- Ping a public IP address
- Compare results with a domain name

If a public IP responds but a domain name does not, DNS may be the source of the issue.

---

# Step 6 — Verify DNS Resolution

Use DNS tools to determine whether domain names are resolving correctly.

Useful command:

- `nslookup`

Compare expected and actual results before continuing.

---

# Step 7 — Trace the Route

If connectivity still fails, determine where communication stops.

Useful command:

- `tracert`

This can help identify where packets stop progressing toward the destination.

---

# Step 8 — Test the Application Layer

Even when network connectivity is functioning correctly, an application or web service may still be unavailable.

Useful command:

- `curl`

Testing HTTP responses helps distinguish server issues from network issues.

---

# Step 9 — Document the Investigation

Record:

- Symptoms
- Commands used
- Results
- Root cause
- Resolution
- Lessons learned

Documenting investigations builds a valuable reference for future troubleshooting.

---

# Key Takeaways

- Start with the simplest explanation.
- Verify each layer before moving to the next.
- Change one variable at a time.
- Use evidence to guide each decision.
- Document your findings.