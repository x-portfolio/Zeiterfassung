# 📱 Arbeitszeiterfassung PWA - Installationsanleitung

## 🚀 So installierst du die App:

### Schritt 1: Dateien hochladen

Du musst alle Dateien auf einen kostenlosen Webhosting-Service hochladen. Hier sind die einfachsten Optionen:

#### **Option A: Netlify Drop (EMPFOHLEN - am einfachsten!)**

1. Gehe zu: https://app.netlify.com/drop
2. Ziehe ALLE 5 Dateien in das Upload-Feld:
   - index.html
   - manifest.json
   - service-worker.js
   - icon-192.png
   - icon-512.png
3. Warte 10 Sekunden
4. Du bekommst eine URL wie: `https://dein-name.netlify.app`
5. **FERTIG!** Öffne diese URL auf deinem Handy

#### **Option B: GitHub Pages**

1. Erstelle einen kostenlosen Account auf https://github.com
2. Erstelle ein neues Repository (z.B. "zeiterfassung")
3. Lade alle 5 Dateien hoch
4. Gehe zu Settings → Pages → Source: "main branch"
5. Deine App ist dann unter: `https://deinname.github.io/zeiterfassung`

#### **Option C: Vercel**

1. Gehe zu: https://vercel.com
2. Melde dich kostenlos an
3. Klicke "New Project"
4. Lade alle 5 Dateien hoch
5. Fertig!

---

### Schritt 2: App auf dem Handy installieren

#### **Android (Chrome):**

1. Öffne die URL deiner gehosteten App in Chrome
2. Chrome zeigt automatisch ein Banner: **"App installieren"**
3. Tippe auf **"Installieren"**
4. Die App erscheint als Icon auf deinem Homescreen
5. **Fertig!** Die App funktioniert jetzt wie eine native App

**Alternative für Chrome:**
- Drei Punkte (⋮) → "App installieren" oder "Zum Startbildschirm hinzufügen"

#### **Android (Brave/Firefox):**

1. Öffne die URL in Brave oder Firefox
2. Drei Punkte (⋮) → "Zum Startbildschirm hinzufügen"
3. Fertig!

#### **iPhone (Safari):**

1. Öffne die URL in Safari
2. Tippe auf **Teilen-Button** (□↑)
3. Wähle **"Zum Home-Bildschirm"**
4. Tippe **"Hinzufügen"**
5. Fertig!

---

## ✨ Vorteile der PWA:

- ✅ Funktioniert wie eine native App
- ✅ Komplett offline nutzbar
- ✅ Daten bleiben lokal gespeichert
- ✅ Automatische Updates beim nächsten Öffnen
- ✅ Kein App Store nötig
- ✅ Funktioniert auf Android UND iPhone

---

## 🆘 Probleme?

**Chrome zeigt keine Installationsoption:**
- Stelle sicher, dass die Seite über HTTPS läuft (alle oben genannten Services nutzen HTTPS)
- Warte 30 Sekunden nach dem ersten Laden
- Aktualisiere die Seite einmal

**App funktioniert nicht offline:**
- Öffne die App einmal online, damit der Service Worker installiert wird
- Danach funktioniert sie komplett offline

**Icons werden nicht angezeigt:**
- Stelle sicher, dass ALLE 5 Dateien hochgeladen wurden
- Manchmal dauert es 1-2 Minuten bis die Icons geladen sind

---

## 📦 Diese Dateien brauchst du:

1. **index.html** - Die Haupt-App
2. **manifest.json** - PWA Konfiguration
3. **service-worker.js** - Offline-Funktionalität
4. **icon-192.png** - App-Icon (klein)
5. **icon-512.png** - App-Icon (groß)

Alle Dateien müssen im gleichen Ordner sein!

---

## 🎯 Empfehlung:

Nutze **Netlify Drop** - das ist mit Abstand am einfachsten:
1. Alle Dateien auf einmal hochziehen
2. Link kopieren
3. Auf dem Handy öffnen und installieren
4. Fertig in unter 2 Minuten! 🚀
