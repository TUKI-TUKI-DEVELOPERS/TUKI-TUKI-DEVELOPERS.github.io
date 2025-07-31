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

Publica:

```bash
npm run deploy              # compila y empuja dist/ a gh-pages
```
