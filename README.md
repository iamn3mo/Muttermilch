# Muttermilch - Stillzeit Tracker

## 📱 Was ist Muttermilch?

Muttermilch ist eine **kostenlose, webbasierte App** zum Tracken von Stillzeiten. Die App hilft Eltern dabei, den Überblick über Stillgewohnheiten ihres Babys zu behalten und wichtige Muster zu erkennen.

## 🔒 Datenschutz & Privatsphäre

**Ihre Daten bleiben 100% privat!**

- **Lokale Speicherung:** Alle Daten werden nur auf Ihrem Gerät gespeichert
- **Keine Übertragung:** Es werden keine Daten an den Entwickler oder Dritte gesendet
- **Keine Registrierung:** Kein Account oder persönliche Daten erforderlich

## ⚠️ Wichtiger Hinweis zu Datensicherheit

**Ihre Daten können verloren gehen wenn:**

- Browser-Daten gelöscht werden
- Browser-Cache geleert wird
- Gerät zurückgesetzt wird

**Empfehlung:** Erstellen Sie regelmäßig ein Backup mit dem CSV-Export!

## 💾 Backup & Datenübertragung

### Backup erstellen:

- Klicken Sie auf `📤 CSV Export`
- Speichern Sie die Datei an einem sicheren Ort
- Bei Bedarf mit `📥 CSV Import` wiederherstellen

### Daten zwischen Geräten übertragen:

1. Auf dem alten Gerät: CSV exportieren
2. Datei auf das neue Gerät übertragen
3. Auf dem neuen Gerät: CSV importieren

## ✏️ Handschriftliche Daten importieren

Sie können auch handschriftlich erfasste Stillzeiten nachträglich importieren:

### Schritt 1: CSV-Datei erstellen

Erstellen Sie eine Textdatei mit der Endung `.csv` (z.B. `meine_daten.csv`)

### Schritt 2: Daten im CSV-Format eingeben

```csv
"Baby","Brust","Startdatum","Startzeit","Enddatum","Endzeit","Dauer (Minuten)"
"Emma","Links","04.06.2025","08:00","04.06.2025","08:15","15"
"Emma","Rechts","04.06.2025","08:17","04.06.2025","08:30","13"
"Emma","Links","04.06.2025","11:30","04.06.2025","11:45","15"
```

### Wichtige Format-Regeln:

- **Brust:** "Links" oder "Rechts"
- **Datum:** TT.MM.JJJJ (z.B. 04.06.2025)
- **Zeit:** HH:MM (z.B. 08:00)
- **Dauer:** Optional - wird automatisch berechnet wenn nicht angegeben
- **Anführungszeichen:** Jedes Feld in " " setzen
- **Trennung:** Felder mit Komma trennen

### Schritt 3: Datei importieren

Klicken Sie auf `📥 CSV Import` und wählen Sie Ihre Datei aus.

## 🎯 Funktionen

- **Live-Timer:** Echtzeiterfassung der Stillzeiten
- **Beide Brüste:** Automatische Erkennung von Seitenwechseln
- **Multi-Baby Support:** Mehrere Babys verwalten
- **Tages-Statistiken:** Durchschnitte, Min/Max-Werte
- **Intelligente Gruppierung:** Sessions < 10 Min werden kombiniert
- **CSV Export/Import:** Daten sichern und übertragen

## 🌐 Installation

Die App kann als **Progressive Web App (PWA)** installiert werden:

1. Chrome öffnen und zur App navigieren
2. Drei Punkte → "Zum Startbildschirm hinzufügen"
3. App erscheint wie eine native App auf dem Homescreen

## 💡 Tipps

- Exportieren Sie wöchentlich ein Backup
- Nutzen Sie aussagekräftige Baby-Namen
- Die "Zuletzt angelegt" Info hilft beim Seitenwechsel
- Tages-Statistiken zeigen Entwicklung der Stillgewohnheiten

## 🆓 Open Source

Diese App ist kostenlos und werbefrei. Der Quellcode ist verfügbar und kann frei verwendet werden.
