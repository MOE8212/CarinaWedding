# ✨ Carina Eckert – Freie Traurednerin

Professionelle Website für das Nebengewerbe als freie Traurednerin & Hochzeitsservice-Vermittlung.

![Status](https://img.shields.io/badge/Status-Live-brightgreen)
![License](https://img.shields.io/badge/Lizenz-Privat-blue)

## 🌸 Überblick

Eine elegante, mobile-first Onepage-Website mit folgenden Bereichen:

- **Hero** – Emotionaler Einstieg mit Fullscreen-Hochzeitsfoto
- **Über mich** – Persönliche Vorstellung von Carina
- **Leistungen** – Freie Trauung, Eheversprechen, Rituale & Symbole
- **Vermittlung** – Fotografen, Floristik, Musik, Papeterie
- **So läuft's** – 4-Schritte-Ablauf
- **Testimonial** – Kundenstimme mit Hintergrundbild
- **Kontaktformular** – Anfrage mit Dropdown-Auswahl

## 🎨 Design

Inspiriert vom [Bloombliss Wedding Planner Design](https://dribbble.com/shots/25477830) von Farzana Rahman.

- **Schriften:** Cormorant Garamond (Serif) + Jost (Sans-Serif)
- **Farbpalette:** Creme, Salbeigrün, Gold-Akzente, Soft-Black
- **Bilder:** [Unsplash](https://unsplash.com) (kostenlos & lizenzfrei)
- **Animationen:** Scroll-Reveal, Hover-Effekte, Hero-Zoom

## 📱 Features

- ✅ Vollständig responsive (Mobile-first)
- ✅ Hamburger-Menü auf Smartphones
- ✅ Smooth Scroll Navigation
- ✅ Scroll-Reveal Animationen
- ✅ Optimierte Bildladung (lazy loading)
- ✅ Transparente → fixierte Navigation
- ✅ Keine externen Abhängigkeiten (nur Google Fonts)

## 🚀 Deployment

### Option A: GitHub Pages
1. Repository auf GitHub erstellen
2. Unter **Settings → Pages** den Branch `main` auswählen
3. Website ist live unter `https://[username].github.io/carina-eckert-website/`

### Option B: Eigene Domain
Die `index.html` kann auf jedem Webserver oder Hosting-Dienst (Netlify, Vercel, IONOS, Strato etc.) deployed werden.

## 📂 Projektstruktur

```
carina-eckert-website/
├── index.html      ← Komplette Website (Single-File)
├── README.md       ← Diese Datei
└── LICENSE         ← Lizenzinformationen
```

## 🖼️ Bilder anpassen

Das Porträtfoto im "Über mich"-Bereich ist aktuell ein Platzhalter. Um Carinas echtes Foto einzufügen:

1. Foto in das Repository hochladen (z.B. als `carina.jpg`)
2. In `index.html` die Zeile suchen:
   ```html
   <img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330?w=800&q=80"
   ```
3. URL ersetzen durch:
   ```html
   <img src="carina.jpg"
   ```

## 📧 Kontaktformular

Das Formular zeigt aktuell eine Bestätigungsanimation, sendet aber noch keine E-Mails. Für den Live-Betrieb empfehlen wir:

- [Formspree](https://formspree.io) (kostenlos bis 50 Anfragen/Monat)
- [Netlify Forms](https://www.netlify.com/products/forms/) (bei Netlify-Hosting inklusive)
- Eigenes Backend

---

Erstellt mit 💛 für Carina Eckert
