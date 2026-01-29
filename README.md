# 🛡️ Security Awareness Quiz

Eine interaktive Website für Cybersecurity-Awareness-Training, die auf einem Poster als QR-Code präsentiert werden kann.

## 🎯 Zweck

Diese Website simuliert einen potentiellen Phishing-Angriff und klärt Nutzer über verschiedene Cybersecurity-Gefahren auf:
- Phishing
- Schwache Passwörter
- Deepfakes
- Social Engineering
- Ransomware
- Öffentliche WLAN-Risiken
- und mehr...

## ✨ Features

- **Eindrucksvolle Warnung**: Nutzer werden darauf hingewiesen, dass der QR-Code ein Phishing-Link hätte sein können
- **Interaktives Quiz**: 10 Fragen zu verschiedenen Cybersecurity-Themen
- **Sofort-Feedback**: Direkte Erklärungen nach jeder Antwort
- **Fortschrittsanzeige**: Visueller Fortschrittsbalken
- **Detaillierte Ergebnisse**: Vollständige Auswertung mit Statistiken
- **Responsive Design**: Funktioniert auf Desktop, Tablet und Smartphone
- **Moderne Animationen**: Ansprechende visuelle Effekte
- **Keine Abhängigkeiten**: Funktioniert komplett standalone

## 🎨 Design-Features

- Futuristisches Cybersecurity-Theme
- Gradient-Animationen
- Interaktive Hover-Effekte
- Pulsende Warnungen
- Smooth Transitions
- Dark Mode Design

## 📋 Quiz-Themen

1. Phishing-Angriffe
2. Passwortsicherheit
3. Verdächtige E-Mails erkennen
4. Deepfakes
5. Umgang mit verdächtigen Links
6. Passwort-Management
7. Zwei-Faktor-Authentifizierung
8. Social Engineering
9. Öffentliche WLAN-Sicherheit
10. Ransomware

## 🚀 Verwendung

### Als QR-Code auf Poster
1. Hoste die Website auf GitHub Pages (siehe DEPLOYMENT.md)
2. Generiere einen QR-Code mit der URL
3. Platziere den QR-Code auf deinem Security-Awareness-Poster
4. Nutzer scannen den Code und gelangen zur Website

### Lokale Nutzung
Einfach die `index.html` Datei in einem Browser öffnen - keine Installation oder Server nötig!

## 🛠️ Technologie

- **HTML5**: Semantisches Markup
- **CSS3**: Custom Properties, Animations, Grid/Flexbox
- **Vanilla JavaScript**: Keine Frameworks, pure Performance
- **Google Fonts**: JetBrains Mono & Outfit

## 📱 Browser-Kompatibilität

- Chrome/Edge (empfohlen)
- Firefox
- Safari
- Mobile Browser (iOS/Android)

## 🎨 Anpassungen

Du kannst die Website leicht anpassen:

### Farben ändern
Ändere die CSS-Variablen in `:root`:
```css
--accent-danger: #ff3366;
--accent-warning: #ffaa00;
--accent-success: #00ff88;
--accent-info: #00d4ff;
```

### Fragen hinzufügen/ändern
Bearbeite das `questions` Array im JavaScript-Bereich:
```javascript
{
    question: "Deine Frage?",
    options: ["Option 1", "Option 2", "Option 3", "Option 4"],
    correct: 0, // Index der richtigen Antwort
    explanation: "Deine Erklärung"
}
```

### Texte anpassen
Alle Texte können direkt im HTML bearbeitet werden.

## 📊 Analytics (Optional)

Um zu tracken, wie viele Nutzer das Quiz machen, kannst du Google Analytics oder ähnliche Tools hinzufügen.

## 📄 Lizenz

Frei verwendbar für Awareness-Training und Bildungszwecke.

## 🤝 Beitragen

Verbesserungsvorschläge sind willkommen! Einfach die `index.html` anpassen und nutzen.

## ⚠️ Wichtiger Hinweis

Diese Website ist ausschließlich für Bildungs- und Awareness-Zwecke gedacht. Sie simuliert Sicherheitsrisiken, um Nutzer zu schulen, und enthält keine echten Bedrohungen.

---

**Erstellt für Security Awareness Training** | Made with 🛡️ for better Cybersecurity
