📋 Table of Contents

Overview
Pages
Tech Stack
Project Structure
Getting Started
Author


🎯 Overview

Bienes Raíces is a fully responsive, multi-page static website for a real estate company. It showcases available properties, blog articles and contact information, with a clean modern design built using semantic HTML5, SCSS (SASS) and vanilla JavaScript. The project demonstrates solid frontend fundamentals including responsive layouts, CSS Grid, Flexbox and a professional build pipeline with Gulp.

🗂️ Pages

PageFileDescription🏠 Homeindex.htmlHero banner, featured properties and company highlights🏡 Listingsanuncios.htmlAll available properties listing📄 Property detailanuncio.htmlIndividual property details and photos📰 Blogblog.htmlReal estate articles and market insights📝 Blog postentrada.htmlIndividual blog post view👥 Aboutnosotros.htmlTeam and company information📞 Contactcontacto.htmlContact form and location map

🛠️ Tech Stack

TechnologyPurposeHTML5Semantic, accessible markupCSS3Responsive layouts (Grid + Flexbox)SCSS (SASS)Modular and maintainable styles with variables, mixins and partialsJavaScript (ES6+)UI interactivity (navigation, sliders, form behavior)Gulp 4Build automation: SASS compilation, minification, live reload

📁 Project Structure

Bienes-Raices-Final/
├── src/
│   └── scss/               # SASS source files
│       ├── base/           # Reset, variables, typography
│       ├── components/     # Buttons, cards, forms
│       └── layout/         # Header, footer, grid sections
├── build/
│   ├── css/                # Compiled CSS output
│   └── js/                 # Minified JS output
├── index.html              # Home page
├── anuncios.html           # Property listings
├── anuncio.html            # Single property detail
├── blog.html               # Blog index
├── entrada.html            # Blog post
├── nosotros.html           # About us
├── contacto.html           # Contact page
├── base.html               # Base template
├── gulpfile.js             # Gulp build configuration
└── package.json

🚀 Getting Started

Prerequisites

Node.js v16+
npm v8+

Installation

bash# 1. Clone the repository
git clone https://github.com/LuisAOL2003/Bienes-Raices-Final.git
cd Bienes-Raices-Final

# 2. Install dependencies
npm install

# 3. Start development (watch mode with live reload)
npx gulp watch

# 4. Build for production
npx gulp build
Open index.html in your browser or use the live reload server started by Gulp.

💡 Key Learning Highlights

CSS Grid & Flexbox — Complex, responsive layouts without CSS frameworks
SASS architecture — 7-1 pattern with partials, variables and mixins
Gulp automation — SASS compilation, autoprefixing, minification and browser sync
Semantic HTML — Accessible, SEO-friendly markup structure
Multi-page architecture — Consistent header/footer across all pages


👤 Author
Luis Ojeda — Full Stack Developer

🌐 portafolio-luis-ojeda.vercel.app
💼 LinkedIn
🐙 GitHub @LuisAOL2003
