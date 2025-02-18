# sleepypig
Set up new site for https://sleepypigco.notion.site/Welcome-to-The-Sleepy-Pig-165d7c2515a48078aab2c6dda210fdb

## Components
* Astro (web framework): Best for fast web development using dynamic components
* Netlify (web hosting platform): Best for free scalable hosting
* Tailwind CSS (fast styling)

## To do
* Domain name?
* Content?
* 3rd party features

# NOTES
General Folder Naming Convention in Astro:
src/components/ → Reusable UI elements (buttons, cards, forms, etc.)
src/layouts/ → Page layouts (wrapping structure for pages)
src/pages/ → Page-specific content

📂 my-baking-shop/
├── 📂 public/                # Static assets (images, icons, etc.)
│   ├── 📂 images/
│   │   ├── cakes.jpg
│   │   ├── cookies.jpg
│   │   ├── varietygoods.jpg
│   │   ├── gallery1.jpg
│   │   ├── gallery2.jpg
│   │   ├── gallery3.jpg
├── 📂 src/
│   ├── 📂 pages/
│   │   ├── index.astro
│   │   ├── aboutme.astro
│   │   ├── gallery.astro  # ✅ Uses images from public/
│   │   ├── products.astro
│   │   ├── 📂 products/
│   │   │   ├── cakes.astro
│   │   │   ├── cookies.astro
│   │   │   ├── varietygoods.astro
│   ├── 📂 components/
│   │   ├── Header.astro
│   │   ├── Footer.astro
├── astro.config.mjs
├── package.json
├── tsconfig.json
├── README.md


