# RTM Suite Light 1.0 — Defensive Security Workbench

**Kostenlos · lokal · defensiv.** Netzwerk-Inventar, Sicherheitsbaseline, Blue-Team-Audit und das passive Pwnagotchi Radar für Linux — ohne Kosten, ohne Zwang zur Registrierung.

➡️ **[Jetzt kostenlos herunterladen](https://figarow.github.io/rtm-suite-light/)**

---

## 🚀 Was ist RTM Suite Light?

RTM Suite Light ist die kostenlose, proprietäre Edition (keine Open-Source-Lizenz) der RTM Suite für autorisierte, defensive Sicherheitsprüfungen auf dem eigenen Linux-System:

- 🔍 Netzwerk-Inventar & Schwachstellenübersicht
- 🛡️ Sicherheitsbaseline & Blue-Team-Audit
- 📡 Pwnagotchi Radar (RTM Pwn Guard) — rein passive WLAN-Indikatoren, kein aktives Senden
- 📄 Lokale PDF-Berichte, alle Daten bleiben auf deinem Gerät

Alle Details, Download-Paket (mit SHA-256-Prüfsummen), Vorstellungsvideo und rechtliche Hinweise findest du auf der **[Downloadseite](https://figarow.github.io/rtm-suite-light/)**.

## 💾 Downloads

| Plattform | Status | Paket |
|---|---|---|
| Linux | ✅ getestet | [RTM-Suite-Light-1.0-linux.zip](https://figarow.github.io/rtm-suite-light/downloads/RTM-Suite-Light-1.0-linux.zip) |
| Windows | ⚠️ **Experimental** | [RTM-Suite-Light-1.0-windows-EXPERIMENTAL.zip](https://figarow.github.io/rtm-suite-light/downloads/RTM-Suite-Light-1.0-windows-EXPERIMENTAL.zip) |

Die Windows-Version enthält einen Installer sowie eine portable Variante inklusive mitgelieferter Java-Laufzeit. Sie ist als **Experimental** gekennzeichnet, da sie bislang nicht auf echter Windows-Hardware verifiziert wurde. Der Pwnagotchi Radar benötigt unter Windows zusätzlich eine WSL2-Brücke mit externem, monitor-mode-fähigem USB-WLAN-Adapter (Anleitung im Paket enthalten). Rückmeldungen und Fehlerberichte sind ausdrücklich willkommen (siehe Sicherheitslücken-Kontakt unten).

## 🛠️ Eingesetzte externe Werkzeuge

RTM Suite Light führt seine Prüfungen nicht isoliert aus, sondern steuert bewährte, separat zu installierende Systemwerkzeuge auf dem eigenen Linux-Rechner an. Diese Werkzeuge sind **nicht** Bestandteil des Downloads und müssen aus einer rechtmäßigen Quelle eigenständig installiert werden:

- **Nmap** – Netzwerk-Inventar und Schwachstellenübersicht
- **ss** (iproute2) – lokale Analyse offener Verbindungen und Ports
- **nft** (nftables) – Prüfung der Firewall-/Filterregeln
- **journalctl** – Auswertung lokaler System- und Sicherheitsprotokolle
- **xdg-open** – automatisches Öffnen erzeugter PDF-Berichte
- **Python 3, iw, ip, pkexec** – zusätzlich für den Live-Betrieb des Pwnagotchi Radars (RTM Pwn Guard)

Der Reiter "Systemcheck" zeigt beim Start, welche dieser Werkzeuge auf dem System bereits verfügbar sind.

## Erweiterte Edition in Vorbereitung

RTM Suite Light bleibt dauerhaft kostenlos nutzbar. Eine erweiterte Edition mit zusätzlichen Analyse- und Berichtsfunktionen ist geplant. Informationen zu Lizenzmodell, Preis und Verfügbarkeit werden vor Veröffentlichung gesondert über denselben Kanal wie dieser Download bereitgestellt.

## 💛 Freiwillig unterstützen

Download und Nutzung von RTM Suite Light sind und bleiben kostenlos. Eine finanzielle Unterstützung ist freiwillig, erfolgt ohne Gegenleistung und beeinflusst weder Funktionsumfang noch Updates oder Support. Es handelt sich nicht um eine steuerlich absetzbare Spende im Sinne des österreichischen Spendenrechts; es wird keine Spendenbescheinigung ausgestellt.

**Bitcoin (BTC, Mainnet, Native SegWit):**

```
bc1q7ej6cte24zrz8z8z5m2fcs7jcql6wuve6659hk
```

Den passenden QR-Code findest du unter [`assets/bitcoin-unterstuetzung.png`](assets/bitcoin-unterstuetzung.png). Bitte Adresse und Netzwerk vor dem Senden in der eigenen Wallet vollständig prüfen — Bitcoin-Transaktionen sind unumkehrbar.

## 🔒 Sicherheitslücken melden

Für Hinweise zu Sicherheitslücken in RTM Suite Light oder RTM Pwn Guard: [birdwithbeard@gmx.at](mailto:birdwithbeard@gmx.at?subject=Sicherheitsmeldung%20RTM%20Suite%20Light). Bitte betroffene Version, Reproduktionsschritte und Auswirkungen beschreiben, keine ungeschwärzten echten Scan-/Evidence-Daten mitsenden und vor Veröffentlichung von Details eine angemessene Behebungsfrist einräumen. Unterstützt wird die aktuell veröffentlichte Version 1.0.

## 📜 Rechtliches

- [EULA / Lizenzvertrag](rechtliches/EULA-LIZENZVERTRAG.txt)
- [Haftungsbegrenzung](rechtliches/HAFTUNGSBEGRENZUNG.txt)
- [Datenschutzhinweise](rechtliches/DATENSCHUTZHINWEISE.txt)
- [Drittanbieterhinweise](rechtliches/DRITTANBIETERHINWEISE.txt)
- [Support und Updates](rechtliches/SUPPORT-UND-UPDATES.txt)
- [Rechtlicher Hinweis zum Prüfstatus](rechtliches/RECHTLICHER-PRUEFSTATUS.txt)
- [Impressum](rechtliches/impressum.html)

Nutzung nur gegen Systeme und Netze mit ausdrücklicher Berechtigung des Verfügungsberechtigten.

---

**Anbieter:** SG, Wien, Österreich · [Kontakt](rechtliches/impressum.html)
