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

Erstellen Sie eine Textdatei mit der Endung `.CSV` (z.B. `meine_daten.CSV`)

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

## ✏️ Daten bearbeiten & korrigieren

### Direkt in der App bearbeiten:
- **Stillzeiten anpassen:** Klicken Sie auf eine Session im Stillverlauf
- **Einzelne Sessions:** Ändern Sie Baby, Brust, Start- und Endzeit
- **Kombinierte Sessions:** Bearbeiten Sie jede Einzelphase separat
- **Löschen:** Entfernen Sie versehentlich erfasste Sessions
- **Baby-Management:** Babys umbenennen oder löschen

### CSV-Daten extern bearbeiten:
1. Daten mit `📤 CSV Export` exportieren
2. CSV-Datei mit Texteditor öffnen (z.B. Notepad, TextEdit)
3. Daten nach Bedarf ändern (Format beachten!)
4. Aktuelle App-Daten löschen
5. Bearbeitete Datei mit `📥 CSV Import` reimportieren

**Tipp:** Für größere Korrekturen ist die externe Bearbeitung oft schneller!

## 📊 Beispieldaten zum Testen

Um die App schnell auszuprobieren, können Sie **vorgefertigte Beispieldaten** direkt in der App herunterladen und importieren:

### Download und Import:

1. **Beispieldaten herunterladen:** In der App auf den Link "beispiel_stilldaten.csv" im Hilfe-Bereich klicken
2. **In die App importieren:** Klicken Sie auf `📥 CSV Import` und wählen Sie die heruntergeladene Datei
3. **Testen:** Erkunden Sie alle Funktionen mit realistischen Daten

**Perfekt zum Testen:** Die Beispieldaten zeigen alle App-Funktionen wie Tagesstatistiken, kombinierte Sessions und die verschiedenen Darstellungsformen!

## 🎯 Funktionen

- **Live-Timer:** Echtzeiterfassung der Stillzeiten
- **Beide Brüste:** Automatische Erkennung von Seitenwechseln
- **Multi-Baby Support:** Mehrere Babys verwalten
- **Detaillierte Tagesstatistiken:** Min/⌀/Max-Werte und Bruststatistiken
- **Intelligente Gruppierung:** Sessions < 10 Min werden kombiniert
- **Session-Bearbeitung:** Nachträgliche Bearbeitung möglich
- **CSV Export/Import:** Daten sichern und übertragen

## 🌐 Installation als App

Die App kann als **Progressive Web App (PWA)** auf dem Startbildschirm installiert werden:

### 📱 iPhone/iPad (iOS):
1. Safari öffnen und zur App navigieren
2. Teilen-Button (📤) antippen
3. "Zum Home-Bildschirm" auswählen
4. App erscheint mit Milchflaschen-Icon auf dem Startbildschirm

### 🤖 Android:
1. Chrome öffnen und zur App navigieren
2. Drei Punkte → "App installieren" oder "Zum Startbildschirm hinzufügen"
3. Installation bestätigen
4. App erscheint wie eine native App im App-Drawer

### 💻 Desktop (Chrome, Edge):
1. Browser öffnen und zur App navigieren
2. Adressleiste: Install-Symbol (⊕) oder "App installieren"
3. Installation bestätigen
4. App startet als eigenständiges Fenster

**Vorteil:** Nach der Installation läuft die App wie eine native App, auch ohne Browser-Adressleiste!

## 💡 Tipps

- Exportieren Sie wöchentlich ein Backup
- Nutzen Sie aussagekräftige Baby-Namen
- Die "Zuletzt angelegt" Info hilft beim Seitenwechsel
- Tages-Statistiken zeigen Entwicklung der Stillgewohnheiten

## 🆓 Open Source

Diese App ist kostenlos und werbefrei. Der Quellcode ist verfügbar und kann frei verwendet werden.
