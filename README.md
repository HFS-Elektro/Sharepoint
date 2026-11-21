# HFS-Simulatoren – zum Teilen

Browser-Simulatoren für den Unterricht in den **Elektronikerberufen**, entwickelt an der Hans-Freudenberg-Schule Weinheim.
Diese Seite ist für **Kolleginnen und Kollegen**: Simulatoren öffnen, Link kopieren oder als QR-Code an die eigene Klasse weitergeben.

Die Simulatoren laufen komplett im Browser: am PC, auf dem iPad und auf dem Handy. Kein Konto, keine Installation,
nach dem ersten Aufruf auch **offline**.

## Inhalt

| Angebot | Datei | Wofür |
|---|---|---|
| **HFS-Schaltungssimulator** | `schaltungssimulator.html` | Gleichstromkreise (LF1), Installationsschaltungen (LF2), Schützsteuerungen (LF3), Elektronik (ab LF5), Brettaufbau mit Verteiler, Messgeräte und Fehlersuche |
| **HFS LOGO Lab** | `logo-lab.html` | Kleinsteuerung im Stil einer LOGO! programmieren und an einer Anlage testen |
| **Anleitung iPad** | `anleitung-ipad.pdf` | Anleitung für Schülerinnen und Schüler |

Die Startseite `index.html` zeigt alle Angebote, jeweils mit **Link kopieren**, **QR-Code** und **Teilen**.
Der QR-Code-Generator unten auf der Seite erzeugt auch Codes für eigene Adressen (z. B. den eigenen Moodle-Kurs)
und kann sie drucken oder als Bild speichern.

## Datenschutz und Sicherheit

- Kein Konto, keine Anmeldung, kein Tracking.
- Projekte und Einstellungen bleiben auf dem Gerät (Browserspeicher). Die Seiten schicken keine Daten an einen Server.
- Jede Seite enthält eine Sicherheitsregel (Content-Security-Policy): nur Dateien von dieser Adresse, kein Senden an fremde Server.
- Der QR-Code wird auf dem Gerät erzeugt ([qrcodejs](https://github.com/davidshimjs/qrcodejs) 1.0.0, MIT-Lizenz, liegt in diesem Repository).
- Wie jeder Webserver protokolliert GitHub beim Aufruf technisch die IP-Adresse des Geräts.

## Dateien

| Datei | Inhalt |
|---|---|
| `index.html` | Startseite mit Teilen-Funktionen |
| `schaltungssimulator.html`, `logo-lab.html` | die Simulatoren (je eine Datei, ohne Abhängigkeiten) |
| `version.json` | aktuelle Versionsnummern (der Simulator meldet damit Updates) |
| `HFS-Simulator-sw.js` | Service Worker für den Offline-Betrieb |
| `*.webmanifest`, `*.png`, `titel.jpg` | App-Name und Symbole |
| `qrcode.min.js` | QR-Code-Erzeugung |

Die Dateien werden automatisch erzeugt. Bitte nicht direkt auf GitHub bearbeiten,
weil die Startseite sonst ihre Sicherheitsprüfsumme verliert.

## Urheber und Lizenz

**Idee und Design: P. Disson** · umgesetzt mit Claude (KI von Anthropic)

Lizenz: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.de) –
Namensnennung, nicht kommerziell, Weitergabe unter gleichen Bedingungen.

Ausgenommen sind die Schaltzeichen-Normen und Markennamen, die nur zur Beschreibung genannt werden
(z. B. LOGO! ist eine Marke der Siemens AG; dieses Projekt ist kein Produkt von Siemens).
