---
layout: section
subtitle: Kill Chain, MITRE ATT&CK, Unified…
---
# Attack Frameworks
---
layout: image-right
image: /kill-chain.png
---
# Attack Frameworks

Detection often reveals the **attack phase** – how far the attacker has progressed.

- How serious is it?
- Does the attacker still have user privileges, or have they escalated?
- **Response depends on the phase:**
  - Host Isolation vs. Process Kill
  - Password reset – on next login, or immediately?
  - Session / token revocation
---
layout: image-right
image: /mitre-attck.png
---
# MITRE ATT&CK

A globally shared knowledge base of attacker tactics and techniques.

- Structured description of behavior (TTPs)
- Mapping detections to specific techniques
- Foundation for Threat Intelligence and Threat Hunting
---
layout: image-right
image: /cyber-unified.png
---
# Cyber / MITRE / Unified

**Different framework coverage:**

- Depends on the tooling used
- Kill Chain – linear, simple
- MITRE ATT&CK – detailed, non-linear
- Unified Kill Chain – combines both
