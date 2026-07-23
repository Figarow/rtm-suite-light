# RTM Suite Light 1.0 — Defensive Security Workbench

**Kostenlos · lokal · defensiv.** Netzwerk-Inventar, Sicherheitsbaseline, Blue-Team-Audit und das passive Pwnagotchi Radar für Linux — ohne Kosten, ohne Zwang zur Registrierung.

➡️ **[Jetzt kostenlos herunterladen](https://figarow.github.io/rtm-suite-light/)**

---

## 🚀 Was ist RTM Suite Light?

RTM Suite Light ist die freie Edition der RTM Suite für autorisierte, defensive Sicherheitsprüfungen auf dem eigenen Linux-System:

- 🔍 Netzwerk-Inventar & Schwachstellenübersicht
- 🛡️ Sicherheitsbaseline & Blue-Team-Audit
- 📡 Pwnagotchi Radar (RTM Pwn Guard) — rein passive WLAN-Indikatoren, kein aktives Senden
- 📄 Lokale PDF-Berichte, alle Daten bleiben auf deinem Gerät

Alle Details, Download-Paket (mit SHA-256-Prüfsummen), Vorstellungsvideo und rechtliche Hinweise findest du auf der **[Downloadseite](https://figarow.github.io/rtm-suite-light/)**.

## 🛠️ Eingesetzte externe Werkzeuge

RTM Suite Light führt seine Prüfungen nicht isoliert aus, sondern steuert bewährte, separat zu installierende Systemwerkzeuge auf dem eigenen Linux-Rechner an. Diese Werkzeuge sind **nicht** Bestandteil des Downloads und müssen aus einer rechtmäßigen Quelle eigenständig installiert werden:

- **Nmap** – Netzwerk-Inventar und Schwachstellenübersicht
- **ss** (iproute2) – lokale Analyse offener Verbindungen und Ports
- **nft** (nftables) – Prüfung der Firewall-/Filterregeln
- **journalctl** – Auswertung lokaler System- und Sicherheitsprotokolle
- **xdg-open** – automatisches Öffnen erzeugter PDF-Berichte
- **Python 3, iw, ip, pkexec** – zusätzlich für den Live-Betrieb des Pwnagotchi Radars (RTM Pwn Guard)

Der Reiter "Systemcheck" zeigt beim Start, welche dieser Werkzeuge auf dem System bereits verfügbar sind.

## 🔥 Demnächst: RTM Suite — die absolute Megaversion

Die kostenlose Light-Edition bleibt dauerhaft frei nutzbar. Parallel dazu ist die **RTM Suite Vollversion** in Vorbereitung — die absolute Megaversion mit deutlich erweitertem Funktionsumfang:

- Erweiterte Auswertungen & tiefere Analysen
- Zusätzliche Prüfprofile
- Weiterführende Reporting-Funktionen

Die Ankündigung der Vollversion erfolgt über denselben Kanal wie dieser Download — schau also gerne ab und zu wieder vorbei oder beobachte ("Watch") dieses Repository.

## 💛 Freiwillig unterstützen

Download und Nutzung von RTM Suite Light sind und bleiben kostenlos. Eine Unterstützung ist rein freiwillig und beeinflusst weder Funktionsumfang noch Updates oder Support.

**Bitcoin (BTC, Mainnet, Native SegWit):**

```
bc1q7ej6cte24zrz8z8z5m2fcs7jcql6wuve6659hk
```

Den passenden QR-Code findest du unter [`assets/bitcoin-unterstuetzung.png`](assets/bitcoin-unterstuetzung.png). Bitte Adresse und Netzwerk vor dem Senden in der eigenen Wallet vollständig prüfen — Bitcoin-Transaktionen sind unumkehrbar.

## 📜 Rechtliches

- [EULA / Lizenzvertrag](rechtliches/EULA-LIZENZVERTRAG.txt)
- [Haftungsbegrenzung](rechtliches/HAFTUNGSBEGRENZUNG.txt)
- [Datenschutzhinweise](rechtliches/DATENSCHUTZHINWEISE.txt)
- [Drittanbieterhinweise](rechtliches/DRITTANBIETERHINWEISE.txt)
- [Support und Updates](rechtliches/SUPPORT-UND-UPDATES.txt)
- [Impressum](rechtliches/impressum.html)

Nutzung nur gegen Systeme und Netze mit ausdrücklicher Berechtigung des Verfügungsberechtigten.

---

**Anbieter:** SG, Wien, Österreich · [Kontakt](rechtliches/impressum.html)
