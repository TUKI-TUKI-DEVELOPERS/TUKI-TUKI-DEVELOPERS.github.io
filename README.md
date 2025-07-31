# Tuki Tuki Portafolio

Sitio estático construido con **[Astro](https://astro.build)** + **Tailwind CSS**  
Publicado en GitHub Pages: <https://tuki-tuki-developers.github.io/>

---

## 📁 Estructura mínima

/
├── public/ # Imágenes, favicon, etc.
├── src/ # Código fuente Astro
│ ├── components/
│ ├── layouts/
│ ├── pages/
│ └── styles/
├── astro.config.mjs # Config Astro (base = '/')
├── tailwind.config.js
├── package.json
└── README.md


---

## ⚙️ Primer uso

```bash
# clona el repo
git clone https://github.com/TUKI-TUKI-DEVELOPERS/tuki-tuki-developers.github.io.git
cd tuki-tuki-developers.github.io

# instala dependencias
npm install
```

Servidor de desarrollo

```bash
npm run dev           # http://localhost:4321
```

🏗️ Compilar para producción

```bash
npm run build         # genera HTML/CSS/JS estático en ./dist
```

🚀 Publicar en GitHub Pages (rama gh-pages)

    El script ya crea .nojekyll y sube dot-files, de modo que GitHub Pages
    sirve la carpeta _astro/.

    Ajusta/añade este script en package.json (una sola vez):

"scripts": {
  "dev":    "astro dev",
  "build":  "astro build",
  "preview":"astro preview",
  "deploy": "npm run build && touch dist/.nojekyll && npx gh-pages -d dist --dotfiles"
}

```bash
npm install -D gh-pages     # si no lo tienes
```

Publica:

```bash
npm run deploy              # compila y empuja dist/ a gh-pages
```
