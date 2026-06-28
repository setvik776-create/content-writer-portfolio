# Content Writer Portfolio

Statinė portfolio svetainė content writeriui, sukurta talpinti per **GitHub Pages**.

## Svetainės struktūra

```
content-writer-portfolio/
├── index.html              # Pagrindinis puslapis
├── about.html              # Apie puslapis
├── works/
│   ├── index.html          # Darbų sąrašas
│   ├── seo-blog-post.html  # SEO straipsnio pavyzdys
│   ├── brand-story.html    # Prekės ženklo istorijos pavyzdys
│   ├── social-media-campaign.html  # Socialinės kampanijos pavyzdys
│   └── tech-article.html   # Techninio straipsnio pavyzdys
├── css/
│   └── style.css           # Stiliai
├── js/
│   └── main.js             # Interaktyvumas
├── .gitignore
└── README.md
```

## Kaip patikrinti lokaliai

Atidarykite terminalą projekto kataloge ir paleiskite:

```bash
python3 -m http.server 8000
```

Tada naršyklėje atidarykite: http://localhost:8000

## Kaip talpinti per GitHub Pages

### 1. Sukurkite repozitoriją GitHub

- Eikite į https://github.com/new
- Pavadinkite repozitoriją, pvz., `content-writer-portfolio`
- Pasirinkite **Public**
- Sukurkite repozitoriją

### 2. Įkelkite failus

Jei naudojate `git` iš komandinės eilutės:

```bash
cd content-writer-portfolio
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/JUSU_VARTOTOJO_VARDAS/content-writer-portfolio.git
git push -u origin main
```

### 3. Įjunkite GitHub Pages

- Eikite į repozitorijos **Settings** → **Pages**
- **Source** skyriuje pasirinkite **Deploy from a branch**
- Pasirinkite **main** šaką ir **/(root)** aplanką
- Paspauskite **Save**

Po kelių minučių svetainė bus pasiekiama adresu:

```
https://JUSU_VARTOTOJO_VARDAS.github.io/content-writer-portfolio/
```

## Kontaktinė forma

Kontaktinė forma naudoja **Formspree**. Jei norite gauti žinutes į savo el. paštą:

1. Užsiregistruokite https://formspree.io/
2. Sukurkite naują formą
3. Pakeiskite `action` reikšmę faile `index.html`:

```html
<form action="https://formspree.io/f/JUSU_FORMOS_ID" method="POST">
```

## Pritaikymas

- Pakeiskite vardą ir kontaktus `index.html`, `about.html` ir `works/index.html`.
- Pakeiskite darbus pagal savo poreikį kataloge `works/`.
- Atnaujinkite spalvas `css/style.css` kintamąjame `--accent`.

## Licencija

Laisvai naudokite ir modifikuokite pagal savo poreikius.
