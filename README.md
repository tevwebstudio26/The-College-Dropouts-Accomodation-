# Teseo Renting — Sito Web

Sito web per agente immobiliare freelance specializzato in affitti e intermediazione a **Rieti (RI), Lazio**.

Sviluppato da [T&V Web Studio](https://tevwebstudio.it)

---

## Struttura file

```
teseo-renting/
│
├── index.html              ← Homepage
├── appartamenti.html       ← Catalogo appartamenti (da sviluppare)
├── chi-siamo.html          ← About us (da sviluppare)
├── contatti.html           ← Form contatto Formfree (da sviluppare)
├── privacy.html            ← Privacy Policy (da sviluppare)
│
└── assets/
    ├── favicon.svg
    ├── og-cover.webp          ← Immagine Open Graph (1200×630)
    ├── about-agent.webp       ← Foto agente
    ├── apt-centro-storico.webp
    ├── apt-vazia.webp
    ├── apt-terminillo.webp
    └── ... (altre foto appartamenti)
```

---

## Stack tecnologico

- **HTML5** puro, zero framework
- **CSS3** custom con variabili, Grid, Flexbox, animazioni CSS
- **JavaScript** vanilla, zero dipendenze
- **Immagini** in formato `.webp` (ottimizzate)
- **Hosting** GitHub Pages

---

## SEO implementato

- Meta title, description, keywords specifici per Rieti
- Open Graph + Twitter Card
- Schema.org `RealEstateAgent` (JSON-LD)
- `canonical` URL
- `robots: index, follow`
- ALT text descrittivi su tutte le immagini
- Struttura heading gerarchica (H1 → H2 → H3)
- `loading="lazy"` sulle immagini non above-the-fold

---

## Da completare (prossimi step)

- [ ] Creare `appartamenti.html` con catalogo completo e filtri
- [ ] Creare `chi-siamo.html` con copy completo e sezione trust
- [ ] Creare `contatti.html` con form Formfree integrato
- [ ] Inserire immagini reali in formato `.webp`
- [ ] Creare `favicon.svg` con logo definitivo
- [ ] Mobile nav drawer (hamburger)
- [ ] Aggiornare URL canonici con dominio definitivo
- [ ] Google Search Console submission
- [ ] Sitemap XML

---

## Note immagini

Tutti i placeholder `<!-- <img src="assets/..."> -->` vanno sostituiti con foto reali in formato `.webp`.

Dimensioni consigliate:
- Foto appartamenti: **800×600px** (ratio 4:3), max 120KB
- Foto agente: **600×750px** (ratio 4:5), max 150KB
- OG cover: **1200×630px**, max 200KB
