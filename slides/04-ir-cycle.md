---
layout: section
subtitle: Podle NIST & SANS
---
# Incident Response Cyklus
---
layout: image-right
image: /ir-cycle.png
---
# Incident Response Cyklus

Čtyři základní fáze podle NIST a SANS:

1. **Preparation** – příprava
2. **Detection & Analysis** – detekce a analýza
3. **Containment, Eradication & Recovery** – omezení, odstranění, obnova
4. **Post-Incident Analysis** – analýza po incidentu
---
layout: default
---
# 1. Příprava (Preparation)

Vytvoření Incident Response Plan (IRP), definice rolí a odpovědností, sestavení týmu a implementace bezpečnostních kontrol.

**Struktura týmu:** SOC / CIRT / CERT

**Model týmu:** Flat vs. Layered

**Dovednosti:** Specializace vs. univerzální znalosti

**Pokrytí:** 8/5 · 24/7 · Follow the Sun · On-call

**SOP:** Obecné i specifické pro kategorii hrozby

**Kontakty:** CISO · Fyzická bezpečnost · IT · PR · HR…
---
layout: default
---
# 2. Detekce a analýza (Detection & Analysis)

Incidenty jsou detekovány pomocí monitorovacích a alertovacích mechanismů. Analytici vyšetřují, sbírají důkazy a hodnotí dopad.

**Nástroje:** SIEM · EDR · SOAR · Forensics

**Detekce:** Signatury · Behaviorální detekce · Threat Intelligence…

**Triage:** Dopad · Závažnost

**IR > DF** – Incident Response má přednost před digitální forenzní analýzou
---
layout: default
---
# 3. Omezení, odstranění a obnova

Po potvrzení incidentu se okamžitě jedná – omezení šíření, eradikace hrozby a obnova postižených systémů.

**Akce:** Izolace vs. Process Kill / Odstranění artefaktů (Business Continuity)

- Závisí na vlastníkovi aktiva – security může vést, ale…
- Plány pro Business Continuity & Disaster Recovery
- Zapojení dalších business jednotek (které mohou vést)
---
layout: default
---
# 4. Analýza po incidentu (Post-Incident Analysis)

Po vyřešení incidentu se provede komplexní analýza – příčiny, slabiny a opatření pro prevenci.

- **Root Cause** – kořenová příčina
- **Reporting & Sharing** – sdílení informací
- **Lessons Learned** – ponaučení
- **Weakness → Hardening / Patching**
- **Vylepšení detekcí / log coverage**
- **Chybějící nebo nedostatečné procesy**
