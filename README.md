# illustrated portfolio ✦

**Full-stack software engineer** building thoughtful digital experiences with clean code and intentional design.

> "good engineering and beautiful design aren't a trade-off. for me, they're the standard."

---

<img width="1361" height="673" alt="image" src="https://github.com/user-attachments/assets/8de9642c-b19c-4891-b32c-054b89fc25dc" />

---

## ✦ live site
 
🔗 [linmicarm.github.io/iyashicoded](https://linmicarm.github.io/iyashicoded)

## ✦ figma design

🎨 [view hi-fi wireframe](https://www.figma.com/design/tBXeDqaQgX65yOaKjybAnK/Portfolio-Hi-Fi-Wireframe?t=RfJQGBtUeBVIm6wq-0)

---

## ✦ about

A fully hand-coded personal portfolio built with vanilla HTML, CSS, and JavaScript — no frameworks, no build tools, no dependencies. Every section, layout, animation, and interaction written from scratch.

The project started in **Figma** with a complete hi-fi wireframe before a single line of code was written. The design system — color palette, typography, spacing, and component hierarchy — was defined upfront as CSS custom properties and used as the single source of truth throughout the build.

The result is a site built around a warm pastel palette, custom chibi doodles, editorial serif typography, and a layered grainy texture that gives it a soft, handcrafted feel distinct from typical developer portfolios.

---

## ✦ sections

| Section | Color | Description |
|---|---|---|
| Hero | `#faf3ea` cream | Introduction, tagline + navigation cards |
| About | `#ffaad3` pink | Background, personality + fun facts |
| How I Work | `#f7c79a` orange | Engineering philosophy + values |
| Projects | `#ffe8a2` yellow | Carousel with modal case studies |
| Services | `#bdd98f` green | What I offer + how I can help |
| Work With Me | `#86daec` blue | Who I work best with |
| Contact | `#c1a5f0` purple | Contact form + links |

---

## ✦ design process

1. **Hi-fi wireframe in Figma** — full layout, color system, typography, and component design across all 7 sections before any code was written
2. **Design system first** — CSS custom properties mirror the Figma variables, keeping color, spacing, and type consistent throughout
3. **Custom illustrations** — original chibi doodle artwork created for each section, each depicting Michelle in a different moment: coding, studying, reading, building, and more
4. **Section by section build** — coded to match the wireframe with refinements along the way
5. **Iterative polish** — copy, interactions, accessibility, and responsiveness layered in after the structural build

🎨 [view the figma wireframe →](https://www.figma.com/design/tBXeDqaQgX65yOaKjybAnK/Portfolio-Hi-Fi-Wireframe?t=RfJQGBtUeBVIm6wq-0)

---

## ✦ features

- 🎨 **7 colorful sections** — each with a unique pastel background, grain + glitter texture overlay
- 🖼️ **Custom doodle illustrations** — original chibi artwork in hero, about, how i work, services, and contact sections
- 🃏 **Project carousel** — swipeable 3-up card layout with click-to-expand modals, touch support
- 📋 **Project modals** — image, description, tech stack tags, live + GitHub links
- 🪟 **Floating glass header** — pill-shaped, blurs on scroll, active nav highlight via IntersectionObserver
- ✨ **Scroll-reveal animations** — cards fade and slide up as they enter the viewport
- 📬 **Working contact form** — connected to Formspree with async JS feedback
- ♿ **Accessible** — focus-visible styles, semantic HTML, ARIA labels, keyboard navigation
- 📱 **Fully responsive** — 4 breakpoints (1024px, 900px, 768px, 640px); doodles scale and hide gracefully
- 🔍 **SEO ready** — meta description, Open Graph tags, Twitter card, custom favicon

---

## ✦ tech stack

```
HTML5        — semantic, accessible markup
CSS3         — custom properties, grid, flexbox, animations, @keyframes
JavaScript   — vanilla ES6+, IntersectionObserver, fetch API, touch events
Formspree    — contact form backend
Google Fonts — Fraunces · Outfit · Inter
Vercel       — deployment + hosting
```

---

## ✦ typography

| Font | Role | Usage |
|---|---|---|
| `Fraunces` | Serif display | All `h1` headings, logo, nav, buttons |
| `Outfit` | Sans-serif | `h2`, `h3`, subheaders, tags |
| `Inter` | Sans-serif | Body text, paragraphs, form labels |

---

## ✦ color palette

```css
--cream:  #faf3ea   /* hero background */
--pink:   #ffaad3   /* about + primary accent */
--orange: #f7c79a   /* how i work */
--yellow: #ffe8a2   /* projects */
--green:  #bdd98f   /* services */
--blue:   #86daec   /* work with me */
--purple: #c1a5f0   /* contact + buttons */
```

---

## ✦ project structure

```
iyashicoded/
├── index.html           # full site — single page
├── style.css            # all styles
├── resume.pdf           # resume download
├── og-image.png         # social share image
└── images/
    ├── hero.png         # chibi doodle — hero section
    ├── about.png        # chibi doodle — about section
    ├── work.png         # chibi doodle — how i work section
    ├── services.png     # chibi doodle — services section
    ├── contact.png      # chibi doodle — contact section
    ├── hoshii.jpg       # project screenshot
    ├── mochiboard.jpg   # project screenshot
    ├── cafecompass.jpg  # project screenshot
    ├── softshelf.jpg    # project screenshot
    ├── petalfm.jpg      # project screenshot
    └── lantern.jpg      # project screenshot
```

---

## ✦ running locally

No build step needed:

```bash
# clone the repo
git clone https://github.com/linmicarm/iyashicoded.git
cd iyashicoded

# open in browser (mac)
open index.html

# open in browser (windows)
start index.html
```

Or use the VS Code **Live Server** extension for hot reload during development.

---

## ✦ deployment
 
Deployed on **GitHub Pages** — any push to `main` triggers an automatic redeploy.
 
```bash
git add .
git commit -m "your message"
git push
```
 
To deploy your own copy:
1. Fork this repo
2. Go to your repo → **Settings** → **Pages**
3. Set branch to `main` → `/ (root)` → Save
4. Live at `https://YOUR_USERNAME.github.io/iyashicoded` in ~2 minutes
---

## ✦ contact form setup

The contact form uses [Formspree](https://formspree.io). To swap in your own:
1. Create a free account at formspree.io
2. Create a new form and copy your form ID
3. In `index.html`, update the form action:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

---

## ✦ projects featured

| Project | Description |
|---|---|
| **hoshii** | cozy anime + manga tracking app with emotional journaling |
| **mochiboard** | soft productivity dashboard for creatives |
| **café compass** | café discovery app for finding cozy workspaces |
| **softshelf** | digital bookshelf + reading journal |
| **petalfm** | lo-fi + ambient music discovery app |
| **lantern** | multilingual community platform for niche hobby groups |

---

## ✦ license

This project is open source under the [MIT License](LICENSE).

Feel free to use it as inspiration — but please make it your own. ✦

---

<p align="center">built with care and intention by <a href="https://portfolio-ten-weld-87.vercel.app">michelle armstrong</a> ✦ iyashicoded</p>
