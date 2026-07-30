# Universal IT Troubleshooting Methodology

Technical troubleshooting is less about immediately finding the correct answer and more about reducing uncertainty through observation and testing.

This methodology documents the framework I use when approaching unfamiliar technical problems.

---

# Step 1 — Observe the Problem

Before changing anything, identify what is actually happening.

Questions to ask:

- What is the user experiencing?
- What is expected to happen?
- What is happening instead?
- When did the issue begin?
- Can the problem be reproduced?

The goal is to clearly define the problem as much as you can before attempting a solution.

---

# Step 2 — Gather Information

Collect as much relevant information as possible without making assumptions.

Examples include:

- Error messages
- Network information
- System specifications
- Recent configuration changes

Reliable information reduces unnecessary guesswork.

---

# Step 3 — Consult Documentation

Before experimenting, check trusted sources.

Examples include:

- Vendor documentation
- Product manuals
- Official knowledge bases
- Technical documentation

Understanding how a system is intended to behave often explains why it is not behaving correctly.

---

# Step 4 — Form a Hypothesis

Based on the available information, identify the most likely explanation.

A hypothesis should be specific and testable.

Example:

> DNS resolution is failing because the configured DNS server is unreachable.

---

# Step 5 — Test Systematically

Perform one change or diagnostic at a time.

Examples include:

- Running diagnostic commands
- Testing connectivity
- Comparing expected and actual behavior
- Isolating variables

Changing multiple variables simultaneously makes it difficult to determine which action affected the outcome.

---

# Step 6 — Analyze the Results

Evaluate whether the evidence supports the hypothesis.

Possible outcomes include:

- The hypothesis is supported.
- The hypothesis is disproven.
- Additional information is needed.

Each result helps narrow the search for the underlying cause.

---

# Step 7 — Verify the Resolution

Once a solution appears successful, confirm that the original issue has been resolved.

Verification may include:

- Repeating the original task
- Confirming functionality with the user
- Monitoring for recurring issues

A successful test should consistently reproduce the expected behavior.

---

# Step 8 — Document the Findings

Record what happened, how the issue was investigated, and how it was resolved.

Useful documentation often includes:

- Symptoms
- Root cause
- Diagnostics performed
- Resolution
- Lessons learned

Well documented investigations become valuable references for future troubleshooting.

---

# Key Principles

- Avoid assumptions.
- Change one variable at a time.
- Prefer evidence over intuition.
- Consult authoritative documentation.
- Verify before declaring success.
- Document what you learn.

---

# Conclusion

Technical troubleshooting is a skill developed through repeated observation, experimentation, and reflection.

While individual technologies change, a structured problem-solving process remains broadly applicable across IT and software engineering.