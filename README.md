# Incident Response

Tento repozitář obsahuje slides pro workshop **Incident Response**, připravené jako studijní materiál pro **Czechitas Digitální akademii – Kybernetická bezpečnost**.

## Obsah

- Co je incident (Event → Alert → Incident)
- Attack Frameworks (Kill Chain, MITRE ATT&CK, Unified)
- Incident Response Cyklus (NIST & SANS)
- Triage (1-10-60)
- Response (phishing, maldoc, ransomware, DDoS, ztracené zařízení, úniklé credentials)
- Eskalace

## Obrázky (doplnit do `/public/`)

Slidy s layoutem `image-right` čekají na tyto obrázky:

| Soubor | Slide |
|--------|-------|
| `event-alert-incident.png` | Event, Alert, Incident |
| `kill-chain.png` | Attack Frameworks – Kill Chain |
| `mitre-attck.png` | MITRE ATT&CK |
| `cyber-unified.png` | Cyber / MITRE / Unified |
| `ir-cycle.png` | IR Cyklus (NIST/SANS diagram) |
| `1-10-60.png` | Triage 1-10-60 |

`ondrej.png` je již přítomen.

## Lokální vývoj

### Požadavky

- Node.js 22+
- npm

### Spuštění

```
npm install
npm run dev
```

### Build

```
npm run build
```
