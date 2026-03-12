---
layout: section
subtitle: According to NIST & SANS
---
# Incident Response Cycle
---
layout: image-right
image: /ir-cycle.png
---
# Incident Response Cycle

Four fundamental phases according to NIST and SANS:

1. **Preparation**
2. **Detection & Analysis**
3. **Containment, Eradication & Recovery**
4. **Post-Incident Analysis**
---
layout: default
---
# 1. Preparation

Creating an Incident Response Plan (IRP), defining roles and responsibilities, building the team, and implementing security controls.

**Team structure:** SOC / CIRT / CERT

**Team model:** Flat vs. Layered

**Skills:** Specialization vs. generalist knowledge

**Coverage:** 8/5 · 24/7 · Follow the Sun · On-call

**SOP:** General and threat-category specific

**Contacts:** CISO · Physical Security · IT · PR · HR…
---
layout: default
---
# 2. Detection & Analysis

Incidents are detected using monitoring and alerting mechanisms. Analysts investigate, collect evidence, and assess impact.

**Tools:** SIEM · EDR · SOAR · Forensics

**Detection:** Signatures · Behavioral detection · Threat Intelligence…

**Triage:** Impact · Severity

**IR > DF** – Incident Response takes precedence over digital forensic analysis
---
layout: default
---
# 3. Containment, Eradication & Recovery

Once an incident is confirmed, immediate action is taken – containing the spread, eradicating the threat, and recovering affected systems.

**Actions:** Isolation vs. Process Kill / Artifact Removal (Business Continuity)

- Depends on the asset owner – security may lead, but…
- Business Continuity & Disaster Recovery plans
- Involvement of other business units (which may take the lead)
---
layout: default
---
# 4. Post-Incident Analysis

After the incident is resolved, a comprehensive analysis is conducted – causes, weaknesses, and preventive measures.

- **Root Cause** – root cause analysis
- **Reporting & Sharing** – information sharing
- **Lessons Learned**
- **Weakness → Hardening / Patching**
- **Improve detections / log coverage**
- **Missing or insufficient processes**
