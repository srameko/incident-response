---
layout: section
subtitle: How to respond to…
---
# Response
---
layout: default
---
# How to respond to…

<div class="icon-grid">
  <div class="icon-card">
    <div class="icon">🎣</div>
    <div class="label">User clicked a phishing link</div>
  </div>
  <div class="icon-card">
    <div class="icon">📄</div>
    <div class="label">User opened a maldoc (Word / Excel / PDF)</div>
  </div>
  <div class="icon-card">
    <div class="icon">🛡️</div>
    <div class="label">AV detected malware (at runtime)</div>
  </div>
  <div class="icon-card">
    <div class="icon">🔒</div>
    <div class="label">Ransomware</div>
  </div>
  <div class="icon-card">
    <div class="icon">🌊</div>
    <div class="label">(D)DoS</div>
  </div>
  <div class="icon-card">
    <div class="icon">📱</div>
    <div class="label">Lost device / Leaked credentials</div>
  </div>
</div>
---
layout: default
---
# Phishing – user clicked a link

1. Isolate the device from the network
2. Check if credentials were entered
3. Reset password – immediately / on next login based on risk
4. Revoke active sessions / tokens
5. Check mail server – block the phishing sender/domain
6. Threat Intelligence – is the link part of a broader campaign?
---
layout: default
---
# Maldoc – user opened a malicious document

1. Isolate the device
2. Determine if a macro / shell / payload was executed
3. EDR – check process tree and child processes
4. Artifact collection – samples for analysis
5. Eradication – delete artifacts or reimage
6. Lessons learned – how did the document pass through the mail gateway?
---
layout: default
---
# Ransomware

1. **Immediate isolation** – disconnect devices and network segments
2. Identify "patient zero" and the scope of spread
3. Business Continuity – what is critical for operations?
4. Backups – are they unaffected? Are they offline / immutable?
5. Communication – CISO, legal, PR, and possibly regulators
6. Decision: restore vs. reimage vs. payment (last resort)
7. Post-incident: how did ransomware enter? Initial access vector?
---
layout: default
---
# (D)DoS

- **Identify type:** Volumetric, Protocol, Application-layer
- Contact ISP / CDN / DDoS protection (Cloudflare, Akamai…)
- Rate limiting, IP blacklisting, geo-blocking
- Check whether DDoS is a smoke screen for another attack
- Monitor service availability and customer impact
---
layout: default
---
# Lost Device

- Contact physical security – in case of theft, also contact police
- Police confirmation may be required (insurance, GDPR reporting)
- **Brick the device** – rotate the disk encryption key
- Remote wipe
---
layout: default
---
# Leaked Credentials

Notification from provider / CTI / OSINT / Law Enforcement.

**Identification:**
- Affected users
- What was leaked and from which device

**Leak types:** Password · Session tokens · Hash · Phone number · PII

**Actions:**
- Password reset / Session revocation / Token revocation
- Notify users – everything leaked must be changed / protected!
