# Parthey Productions

**A production company with an ecological and culturally literate perspective.**

Florianópolis · Choisey, Franche-Comté · New York

---

## Site Structure

```
/
├── index.html              ← Splash / home page
├── css/
│   └── main.css            ← All shared styles
├── images/
│   ├── chateau_exterior.jpg
│   ├── comte.jpg
│   ├── crest.jpg
│   ├── dinner_outside.jpg
│   ├── dining_stone.jpg
│   ├── bedroom_blue.jpg
│   ├── great_hall.jpg
│   ├── grounds.jpg
│   ├── horse.jpg
│   ├── postcard1.jpg
│   ├── postcard2.jpg
│   ├── red_salon.jpg
│   ├── staircase.jpg
│   ├── table_outside.jpg
│   └── tower_bedroom.jpg
└── pages/
    ├── france.html         ← Chateau de Parthey & France experiences
    ├── brazil.html         ← Florianópolis & Brazil experiences
    ├── journey.html        ← The Two-Continent Journey
    ├── about.html          ← About Louis & Sarah
    └── contact.html        ← Contact form
```

## Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g. `parthey-productions`)
2. Push this folder to the `main` branch
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch` → `main` → `/ (root)`
5. Your site will be live at `https://yourusername.github.io/parthey-productions`

### Custom Domain (optional)
To use a custom domain (e.g. `partheyprod.com`):
1. Add a file named `CNAME` in the root containing only your domain name
2. Point your domain's DNS to GitHub Pages (see GitHub docs)

## Before Launching

- [ ] Replace placeholder emails in `pages/contact.html` with real addresses
- [ ] Consider replacing the `mailto:` form action with a proper form service (Formspree, Netlify Forms, etc.)
- [ ] Add a `favicon.ico` to the root folder
- [ ] Review all pricing figures
- [ ] Add your real email and social links to the footer if desired

## Notes

- All images are served as regular files (not base64 embedded), so the site loads efficiently
- The site uses Google Fonts (Cormorant Garamond + Jost) loaded via CDN — requires internet connection to render correctly
- No JavaScript frameworks or build tools required — pure HTML/CSS/JS, works everywhere
- Mobile responsive throughout

---

*Parthey Productions · partheyprod.com*
