# Team Website – Responsiv Nettside med Media Query

## 📌 Beskrivelse
Dette prosjektet er en enkel, responsiv nettside som viser et team med seks medlemmer. Nettsiden er laget med HTML og CSS og oppfyller kravene:
- Bruk av **H1**, **H3**, **P**, **SPAN** elementer
- **Flexbox** for layout
- **Media Query** for responsivitet
- **writing-mode** i footer
- Footer inkludert

## 📂 Struktur
```
project/
│── index.html
│── mediaquerry.css
│── images/
│    ├── photo1.png
│    ├── photo2.png
│    ├── photo3.png
│    ├── photo4.png
│    ├── photo5.png
│    └── photo6.png
```

## ✅ Hvordan bruke
1. Legg bildene dine i mappen `images`.
2. Åpne `index.html` og endre `src` i `<img>`-taggene til dine bildefiler.
3. Åpne `index.html` i en nettleser for å se resultatet.

## 💻 Teknologier
- HTML5
- CSS3 (Flexbox, Media Query)

## 🔍 Funksjoner
- Seks bilder fordelt i **to rader med tre bilder hver**.
- Det midterste bildet i hver rad er **litt forskjøvet ned** for et dynamisk design.
- Responsiv layout: På små skjermer blir bildene stablet vertikalt.
- Minimalistisk design med enkel typografi.

## 🛠 Media Query
Media Query sikrer at layouten tilpasser seg skjermstørrelsen:
```css
@media (max-width: 768px) {
    .container {
        flex-direction: column;
        align-items: center;
    }
}
```

## ✍️ Egen vurdering
Prosjektet oppfyller alle krav:
- Responsivitet ✅
- Bruk av CSS Selectors ✅
- Bruk av writing-mode ✅
- Strukturert og klar for levering ✅

## ❓ Spørsmål
- Har du hjulpet noen? **Ja**
- Har du fått hjelp av noen? **Nei**
