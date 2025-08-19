[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)

<img width="1024" height="250" alt="DienstOrbit Logo mit Schriftzug 1024x250" src="https://github.com/user-attachments/assets/56cda79c-a78e-4284-b28b-5f27dacadd27" />


## Dienstpläne im Orbit: smart planen, sauber exportieren.

DienstOrbit ist ein Dienstplan-Generator für THW-Ortsverbände und ähnliche Organisationen. Die Anwendung berücksichtigt Feiertage und Ferien nach Bundesland und ermöglicht den Export der Termine als CSV, PDF, ICS und Excel.

## Features

- **Dienstreihen anlegen:** Bis zu 5 Terminreihen mit individuellen Einstellungen (Bezeichnung, Wochentag, Turnus, Zeitraum, Uhrzeit).
- **Feiertage & Ferien:** Automatische Ermittlung und Kennzeichnung von Terminen an Feiertagen und in Ferien (OpenHolidaysAPI).
- **Export:** Ergebnisse können als CSV, PDF, ICS (Kalender) und Excel (.xlsx) heruntergeladen werden.
- **Auto-Badges:** Vorschlagswerte für Zeiten und Daten werden automatisch gesetzt und als "⚡ auto" markiert.
- **Validierung:** Eingabefelder werden live geprüft und Fehler angezeigt.
- **Floating Buttons:** Schneller Zugriff auf Tabelle, Export und Seitenanfang.
- **Lokale Speicherung:** Eingaben werden im Browser gespeichert.

## Nutzung

1. Öffne die Datei [`index.html`](index.html) in einem modernen Browser.
2. Fülle die allgemeinen Angaben aus (Ortsverband, Bundesland, Optionen).
3. Lege die gewünschten Terminreihen an und passe die Einstellungen an.
4. Klicke auf **Termine ermitteln**.
5. Die Ergebnistabelle erscheint. Exportiere die Termine über die gewünschten Buttons.

## Hinweise

- Die Anwendung benötigt eine Internetverbindung für die Abfrage von Feiertagen und Ferien.
- Die Datenquelle für Feiertage und Ferien ist [OpenHolidaysAPI](https://openholidaysapi.org/).
- Die Nutzung ist frei unter der MIT-Lizenz. Siehe [`LICENSE`](LICENSE).

## Lizenz

MIT License – siehe [`LICENSE`](LICENSE).

---

## Autor

© 2025 Wolfgang Saal, Böllenborn
