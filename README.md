# Screen — versiuni

Acest repo conține **doar** installerele aplicației Screen și fișierul `version.json`. Nu conține cod sursă.

- **Versiunea curentă:** 1.0.3
- **Versiunea minimă permisă:** 1.0.3 — versiunile mai vechi se blochează la pornire până la actualizare.

## Istoric

| Versiune | Data | Ce s-a schimbat | Descarcă |
|---|---|---|---|
| 1.0.3 **(ultima)** ⚠ minimă | 2026-10-06 | Mesaj „Tabletă găsită” pe carduri, versiunea mutată în Setări | [Mac](https://github.com/23botnari/screen-releases/releases/download/v1.0.3/Screen-1.0.3-mac-arm64.dmg) · [Windows](https://github.com/23botnari/screen-releases/releases/download/v1.0.3/Screen-1.0.3-win-x64.exe) |
| 1.0.2 | 2026-10-06 | Parolă la deschidere, protecție anti-modificare | [Mac](https://github.com/23botnari/screen-releases/releases/download/v1.0.2/Screen-1.0.2-mac-arm64.dmg) · [Windows](https://github.com/23botnari/screen-releases/releases/download/v1.0.2/Screen-1.0.2-win-x64.exe) |
| 1.0.1 | 2026-10-06 | Prima versiune Screen | [Mac](https://github.com/23botnari/screen-releases/releases/download/v1.0.1/Screen-1.0.1-mac-arm64.dmg) · [Windows](https://github.com/23botnari/screen-releases/releases/download/v1.0.1/Screen-1.0.1-win-x64.exe) |

## Instalare

- **Mac (Apple Silicon):** deschide DMG-ul și trage Screen în Applications. Prima dată: click dreapta pe Screen → Deschide (aplicația nu e semnată de Apple).
- **Windows:** rulează installerul. Dacă apare „Windows a protejat PC-ul”: Mai multe informații → Rulează oricum.

## Securitate

`version.json` este semnat digital (Ed25519). Aplicația acceptă doar fișiere cu semnătura validă, deci versiunea minimă,
linkurile de descărcare și parola de deschidere nu pot fi schimbate de altcineva. Parola nu apare nicăieri în clar — doar amprenta ei (scrypt).
