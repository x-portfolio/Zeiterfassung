# 📱 Arbeitszeiterfassung - Benutzerhandbuch

## 🎯 Konzept

Diese App hilft dir dabei, **40% deiner monatlichen Regelarbeitszeit im Büro** zu verbringen.

**Wichtig:** Die 40% beziehen sich auf die **Regelarbeitszeit** (basierend auf Arbeitstagen), nicht auf die tatsächlich geleistete Zeit!

---

## 🧮 Wie wird berechnet?

### Regelarbeitszeit pro Monat:
```
Arbeitstage = Werktage (Mo-Fr) - Urlaubstage - Feiertage
Regelarbeitszeit = Arbeitstage × 8,2 Stunden
```

### Büro-Ziel:
```
Büro-Soll = Regelarbeitszeit × 40%
```

### Verbleibende Bürozeit (Brutto):
```
Noch zu arbeiten = Büro-Soll - bereits geleistete Bürozeit
```

Die Anzeige zeigt die **Brutto-Zeit** (also die Zeit, die du noch einchecken musst, inklusive Pausen).

---

## 📋 Hauptfunktionen

### 🎯 Haupt-Dashboard
- **Große Anzeige:** Zeigt, wie viele Stunden du noch im Büro arbeiten musst (Brutto)
- **Aktualisieren-Button:** Berechnet die Werte neu
- **Live-Berechnung:** Berücksichtigt auch deine aktuelle Session, wenn du eingecheckt bist

### 📅 Monatsübersicht
- **Regelarbeitszeit:** Basierend auf Arbeitstagen des Monats
- **Arbeitstage:** Anzahl der Werktage minus Urlaub/Feiertage
- **Büro-Ist:** Tatsächlich im Büro verbrachte Zeit
- **Homeoffice:** Im Homeoffice verbrachte Zeit
- **Büro-Soll (40%):** Zielwert für diesen Monat

### 🕐 Stempeluhr
- **Kommen-Button:** Zeichnet Startzeit auf (Datum & Uhrzeit vom Handy)
- **Gehen-Button:** Beendet Arbeitszeit und speichert automatisch
- **Automatische Pausenberechnung:**
  - 6-9 Stunden → 30 Min Pause
  - Über 9 Stunden → 45 Min Pause
- **Arbeitsort:** Vor dem Einchecken Homeoffice oder Büro wählen

---

## 🎯 Schnellaktionen

### 🏖️ Urlaub buchen
1. Button "Urlaub" klicken
2. Start- und End-Datum wählen
3. "Hinzufügen" klicken
4. Reduziert die Regelarbeitszeit um 8,2h pro Urlaubstag (nur Werktage)

### 🎉 Feiertag buchen
1. Button "Feiertag" klicken
2. Datum wählen
3. Optional: Name eingeben (z.B. "Weihnachten")
4. "Hinzufügen" klicken
5. Reduziert die Regelarbeitszeit um 8,2h (wenn Werktag)

### ✏️ Nachbuchung
1. Button "Nachbuchung" klicken
2. Datum, Startzeit, Endzeit und Arbeitsort eingeben
3. "Hinzufügen" klicken
4. Pausen werden automatisch berechnet

### 🗑️ Daten löschen
Löscht ALLE gespeicherten Daten (Arbeitszeiten, Urlaub, Feiertage)

---

## 📊 Verlauf

### Aktueller Monat
Zeigt alle Einträge des aktuellen Monats:
- 🏠 Homeoffice-Tage
- 🏢 Büro-Tage
- 🏖️ Urlaubstage
- 🎉 Feiertage

### Navigation
- Mit ◀ ▶ Buttons durch verschiedene Monate navigieren
- Historische Daten bleiben gespeichert
- So kannst du prüfen, ob du in vergangenen Monaten die 40% eingehalten hast

---

## 💡 Tipps zur Nutzung

### Täglicher Workflow:
1. **Morgens:** App öffnen → Arbeitsort wählen → "Kommen" drücken
2. **Abends:** App öffnen → "Gehen" drücken → Fertig!

### Monatsanfang:
1. Feiertage des Monats eintragen
2. Geplanten Urlaub eintragen
3. Regelarbeitszeit wird automatisch angepasst

### Monatsmitte:
1. "Aktualisieren" Button drücken
2. Prüfen, wie viele Stunden noch im Büro nötig sind
3. Arbeitsort entsprechend planen

### Monatsende:
1. Prüfen, ob 40%-Ziel erreicht wurde
2. Mit ◀ ▶ zu nächstem Monat wechseln

---

## 🔍 Häufige Fragen

**Q: Warum wird "Brutto-Zeit" angezeigt?**
A: Die Brutto-Zeit zeigt, wie lange du noch einchecken musst. Die Pausen werden automatisch abgezogen, wenn du auscheck.

**Q: Berücksichtigt die App meine aktuelle Session?**
A: Ja! Wenn du gerade eingecheckt bist im Büro, wird die laufende Zeit in der Berechnung berücksichtigt.

**Q: Was passiert, wenn ich 40% überschreite?**
A: Die Anzeige zeigt dann ein Plus (+) und wird grün. Du hast dein Ziel übertroffen!

**Q: Kann ich Einträge korrigieren?**
A: Ja! Mit dem 🗑️ Button kannst du Einträge löschen und dann mit "Nachbuchung" neu eintragen.

**Q: Werden Wochenenden als Arbeitstage gezählt?**
A: Nein! Nur Montag bis Freitag sind Arbeitstage.

**Q: Was passiert, wenn ich einen Feiertag am Wochenende eintrage?**
A: Feiertage am Wochenende reduzieren die Regelarbeitszeit nicht, da sie keine Arbeitstage sind.

---

## 📱 Installation auf dem Handy

### GitHub Pages aktualisieren:
1. Alte `index.html` auf GitHub löschen
2. Neue `index.html` hochladen
3. 1-2 Minuten warten
4. App im Browser neu laden

### Als App installieren:
1. URL öffnen in Chrome/Safari
2. Chrome: "App installieren" Banner
3. Safari: Teilen → "Zum Home-Bildschirm"
4. App funktioniert wie native App

---

## 💾 Datenspeicherung

- Alle Daten werden **lokal auf deinem Handy** gespeichert
- Keine Cloud, keine Server
- Daten bleiben auch bei App-Schließung erhalten
- Backup-Funktion gibt es nicht - bei App-Löschung sind Daten weg

---

## 🆘 Support

Bei Problemen oder Fragen:
1. App neu laden (Cache leeren)
2. Prüfen, ob alle Einträge korrekt sind
3. "Aktualisieren" Button drücken
4. Notfalls: Daten exportieren (Screenshot), dann App neu installieren

---

## 🎉 Viel Erfolg!

Die App hilft dir dabei, deine 40% Bürozeit perfekt zu planen und einzuhalten!
