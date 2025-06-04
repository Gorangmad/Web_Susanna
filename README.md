# Einführung: Was ist Programmieren?

## 🎯 Lernziele
- Die Teilnehmenden verstehen, was Programmieren ist und warum es wichtig ist.
- Sie lernen zentrale Begriffe kennen.
- Sie visualisieren den Ablauf eines Programmierprozesses.
- Sie führen erste eigene „Anweisungen“ aus.
- Sie unterscheiden Frontend und Backend.
- Sie verstehen, wie Programme logisch ablaufen.
- Sie lernen Projektstrukturen, Fehlerarten und das Denken wie ein Entwickler kennen.

---

## ❓ W-Fragen: Programmieren verstehen

| Frage | Antwort |
|-------|---------|
| **Was** ist Programmieren? | Das Erstellen von Anweisungen, die ein Computer Schritt für Schritt ausführt. |
| **Warum** programmieren wir? | Um Aufgaben zu automatisieren, Websites und Apps zu entwickeln oder Probleme zu lösen. |
| **Wie** funktioniert Programmieren? | Durch das Schreiben von Code in einer Sprache, die vom Computer ausgeführt wird. |
| **Wer** programmiert? | Entwickler:innen, Wissenschaftler:innen, Künstler:innen, jeder kann es lernen. |
| **Wo** wird programmiert? | In Code-Editoren wie VS Code, im Browser oder auf Servern. |
| **Wann** ist es sinnvoll? | Immer, wenn man etwas automatisieren oder digital gestalten möchte. |

---

## 🧠 Zentrale Begriffe

| Begriff | Erklärung |
|--------|-----------|
| **Code** | Geschriebene Anweisungen |
| **Programm** | Ausgeführte Code-Sammlung |
| **Syntax** | Sprachregeln einer Programmiersprache |
| **Editor** | Werkzeug zum Schreiben von Code |
| **Compiler/Interpreter** | Übersetzer für den Computer |
| **Fehler (Bugs)** | Probleme im Code |
| **Debugging** | Fehler suchen und beheben |

---

## 🖼️ Visualisierung

```
[Du]
 ↓ Code schreiben (HTML / CSS / JS)
 ↓ 
[Editor: VS Code]
 ↓ 
[Browser / Node.js führt aus]
 ↓ 
[Ergebnis: Website, App, Funktion]
```

Oder als Analogie:

```
Rezept (Code) → Koch (Computer) → Gericht (Ergebnis)
```

---

## 💾 Wie sprechen Computer?

```
Maschinensprache (01010101)
↓
Assembler (mov ax, 01)
↓
Hochsprachen wie Python, JS, Java
↓
Du (entwickelst Webseiten, Spiele, Apps)
```

---

## 🌐 Was sind Programmiersprachen?

Programmiersprachen übersetzen deine Anweisungen in etwas, das der Computer versteht.

Beispiele:
- **HTML** – Struktur
- **CSS** – Design
- **JavaScript** – Interaktivität
- **Python** – Datenanalyse, Automatisierung
- **C++/C#** – Systemnah oder Spieleentwicklung
- **SQL** – Datenbanken

---

## 🔍 HTML vs CSS vs JavaScript

| Sprache | Aufgabe | Beispiel |
|--------|---------|----------|
| HTML | Struktur | `<h1>Hallo Welt</h1>` |
| CSS | Styling | `h1 { color: red; }` |
| JS | Interaktivität | `alert("Hallo!");` |

---

## 📁 Visualisierung Projektstruktur

```
[ index.html ]
  ↓ verwendet
[ style.css ]
  ↓ beeinflusst durch
[ main.js ]
  ↓ manipuliert
[ Webseite im Browser ]
```

---

## ⚙️ Frontend & Backend

### Was ist was?

| Teil | Beschreibung | Sichtbar |
|------|--------------|----------|
| Frontend | Alles, was im Browser läuft | ✅ |
| Backend | Alles, was im Hintergrund auf dem Server läuft | ❌ |

### Vergleich:

| Merkmal | Frontend | Backend |
|---------|----------|---------|
| Wo? | Browser | Server |
| Sprache | HTML, CSS, JS | Node.js, Python |
| Datenbankzugriff | Nein | Ja |
| Sichtbar? | Ja | Nein |

---

## 🔗 Kommunikation: API

Beispiel: Kontaktformular

```
User klickt „Senden“
 ↓
JS sendet Daten über API an Express-Backend
 ↓
Backend verarbeitet & antwortet
 ↓
Browser zeigt „Erfolg“-Meldung
```

---

## 🚦 Wie läuft ein Programm ab?

Ein Programm läuft Zeile für Zeile:

```text
1. Begrüße Nutzer
2. Frage Name
3. Zeige personalisierte Nachricht
```

→ Das nennt man **Control Flow** – gesteuert durch `if`, `for`, `function`.

---

## 🧠 Statisch vs Dynamisch

| Art | Beschreibung | Beispiel |
|-----|--------------|----------|
| Statisch | Inhalte fest im Code | Portfolio-Seite |
| Dynamisch | Inhalte entstehen beim Laden | Wetter, Login, API |

---

## 🐞 Fehlerarten

| Fehler | Bedeutung | Beispiel |
|--------|-----------|----------|
| Syntaxfehler | Falsche Schreibweise | `funtion()` |
| Logikfehler | Code funktioniert, aber tut das Falsche | falsche Berechnung |

---

## 📦 Projektstruktur

```
portfolio-website/
├── index.html
├── styles/
│   └── style.css
├── scripts/
│   └── main.js
└── img/
    └── me.jpg
```

→ Struktur hilft bei Übersicht und Teamarbeit.

---

## 🕹️ Was ist Git?

- Versionierung von Code
- Änderungen speichern und rückgängig machen
- Zusammenarbeit mit anderen

> GitHub = Plattform, um Git-Projekte online zu speichern

---

## 🧠 Denkweise: Wie denkt ein Programmierer?

1. **Zerlegen** – in kleine Teile
2. **Abstrahieren** – Muster erkennen
3. **Algorithmen bauen** – Reihenfolgen definieren
4. **Testen** – Fehler suchen und verbessern

---

## ✅ Checkliste

- [x] Ich weiß, was Programmieren ist
- [x] Ich kenne Frontend vs. Backend
- [x] Ich kenne HTML, CSS und JS
- [x] Ich habe gelernt, wie Programme ablaufen
- [x] Ich weiß, was APIs und Projektstruktur sind
- [x] Ich habe das Grundprinzip von Git verstanden


# 🧠 Wiederholungsfragen: Einführung in die Programmierung

Beantworte die folgenden Fragen schriftlich oder bespreche sie in der Gruppe:

---

### 1. Was versteht man unter „Programmieren“?

---

### 2. Warum ist Programmieren in der heutigen Welt so wichtig?

---

### 3. Was ist der Unterschied zwischen HTML, CSS und JavaScript?

---

### 4. Was ist der Unterschied zwischen einem Editor und einem Compiler?

---

### 5. Was macht ein Browser mit HTML- und CSS-Dateien?

---

### 6. Erkläre mit deinen Worten den Begriff „Frontend“. Nenne zwei typische Sprachen.

---

### 7. Was passiert im „Backend“ einer Website? Nenne ein Beispiel.

---

### 8. Wie kommunizieren Frontend und Backend miteinander?

---

### 9. Was ist eine API, und wofür wird sie gebraucht?

---

### 10. Welche zwei Arten von Fehlern kann ein Programm enthalten? Gib je ein Beispiel.

---

### 11. Wie sieht eine typische Projektstruktur für eine einfache Website aus?

---

### 12. Wie funktioniert die Denkweise eines Programmierers? Nenne die vier Schritte.

---

### 13. Was ist der Unterschied zwischen einem statischen und einem dynamischen Inhalt?

---

### 14. Was bedeutet „Control Flow“? Welche Schlüsselwörter (z. B. in JS) steuern ihn?

---

### 15. Was ist Git, und warum wird es beim Programmieren verwendet?

---


