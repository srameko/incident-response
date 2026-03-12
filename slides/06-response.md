---
layout: section
subtitle: Jak reagovat na…
---
# Response
---
layout: default
---
# Jak reagovat na…

<div class="icon-grid">
  <div class="icon-card">
    <div class="icon">🎣</div>
    <div class="label">Uživatel klikl na phishing</div>
  </div>
  <div class="icon-card">
    <div class="icon">📄</div>
    <div class="label">Uživatel otevřel maldoc (Word / Excel / PDF)</div>
  </div>
  <div class="icon-card">
    <div class="icon">🛡️</div>
    <div class="label">AV detekoval malware (za běhu)</div>
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
    <div class="label">Ztracené zařízení / Úniklé přihlašovací údaje</div>
  </div>
</div>
---
layout: default
---
# Phishing – uživatel klikl na odkaz

1. Izolovat zařízení od sítě
2. Zkontrolovat, zda zadal přihlašovací údaje
3. Resetovat heslo – okamžitě / příští přihlášení dle rizika
4. Revokovat aktivní session / tokeny
5. Zkontrolovat mail server – blokovat phishingový sender/doménu
6. Threat Intelligence – je odkaz součástí širší kampaně?
---
layout: default
---
# Maldoc – uživatel otevřel škodlivý dokument

1. Izolovat zařízení
2. Zjistit, zda byl spuštěn macro / shell / payload
3. EDR – zkontrolovat process tree a child procesy
4. Artifact collection – vzorky pro analýzu
5. Eradikace – smazání artefaktů nebo reimaging
6. Ponaučení – jak dokument prošel přes mail gateway?
---
layout: default
---
# Ransomware

1. **Okamžitá izolace** – odpojit zařízení i síťové segmenty
2. Identifikovat „patient zero" a rozsah šíření
3. Business Continuity – co je kritické pro provoz?
4. Zálohy – jsou nepostižené? Jsou offline / immutable?
5. Komunikace – CISO, právníci, PR, případně regulátor
6. Rozhodnutí: obnova vs. reimaging vs. platba (poslední možnost)
7. Post-incident: jak ransomware vstoupil? Initial access vector?
---
layout: default
---
# (D)DoS

- **Identifikovat typ:** Volumetrický, Protocol, Application-layer
- Kontaktovat ISP / CDN / DDoS ochranu (Cloudflare, Akamai…)
- Rate limiting, IP blacklisting, geo-blocking
- Zkontrolovat, zda DDoS není smoke-screen pro jiný útok
- Sledovat dostupnost služeb a dopad na zákazníky
---
layout: default
---
# Ztracené zařízení

- Kontaktovat fyzickou bezpečnost – v případě krádeže i policii
- Někdy je nutné potvrzení od policie (pojistka, GDPR hlášení)
- **Brick the device** – rotace šifrovacího klíče disku
- Vzdálený wipe
---
layout: default
---
# Úniklé přihlašovací údaje

Notifikace od poskytovatele / CTI / OSINT / Letter Agency.

**Identifikace:**
- Postižení uživatelé
- Co bylo úniklé a z jakého zařízení

**Typy úniku:** Heslo · Session tokeny · Hash · Telefonní číslo · PII

**Akce:**
- Reset hesla / Revokace session / Revokace tokenu
- Notifikovat uživatele – vše úniklé musí být změněno / chráněno!
