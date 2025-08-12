# Shreya Vadeseri Suresh — Professional Portfolio

A modern, responsive portfolio built with Bootstrap 5. Designed for roles like Data Analyst, Business Analyst, Project Analyst, and Project Manager.

## 🚀 Highlights

- **Mobile‑first, responsive** layout (Bootstrap 5)
- **Light theme** based on hero SVG colors
- **Fixed navbar** with smooth scrolling and active state
- **Redesigned sections**: timeline Experience, logo‑cards Education, card‑grid Projects
- **Accessible** focus states and keyboard-friendly navigation

## 🎨 Design System

### Color Palette (from hero illustration)
- **Primary**: `#FF725E` (red/orange)
- **Secondary**: `#2563eb` (blue)
- **Dark**: `#263238` (charcoal)
- **Light**: `#f5f5f5`
- Grays: `#e0e0e0`, `#ebebeb`, `#64748b`, `#475569`

Defined in `styles.css` under `:root`.

### Typography
- Font: Inter (Google Fonts), weights 300–700

## 🧭 Section Order (as rendered)
1. Navigation Bar (fixed)
2. Hero
3. Education
4. Experience (vertical timeline)
5. Skills
6. Projects
7. Certifications
8. Achievements
9. Contact

Navbar links reflect this order. Brand shows “Shreya Vadeseri Suresh”.

## 📁 Project Structure

```
Portfolio/
├── index.html                     # Main site
├── styles.css                     # Theme + components
├── script.js                      # Smooth scrolling, UI behavior
├── Images/                        # Logos and assets
│   ├── CSU.jpg
│   └── MJCET.png
├── Data analysis-pana.svg         # Hero illustration
├── README.md
```

## 🧩 Section Details

### Education
- Two equal-height cards with left-aligned university logos (`Images/CSU.jpg`, `Images/MJCET.png`)
- Prominent university name, degree, dates, GPA
- Subtle hover lift and shadow

### Experience (Timeline)
- Vertical, alternating timeline with markers/icons
- Each entry: job title, company, dates, and detailed bullet points

### Skills
- Icon-based badges in a responsive grid

### Projects
- One row of three equal-height cards
- Subtitle under section title: “A look at my recent data-driven projects”
- Each card includes: icon, title, gray tech badges, concise description, and a GitHub link
  - Chatbot (Python, TensorFlow, Keras, Jupyter) → `https://github.com/shreyavs09/Chatbot_Tensorflow_Project`
  - Banking Churn Dashboard (Python, Power BI, Google Colab) → `https://github.com/shreyavs09/Banking-Churn-Analysis-Project`
  - Walmart Sales (Python, SQL, MS Excel) → `https://github.com/shreyavs09/Walmart-Sales-Analysis-Project`

## 🔧 Setup
1. Download/clone this folder
2. Open `index.html` in any modern browser

## ✏️ Customization

### Content
- Hero: title/tagline and social links in `index.html` (Hero section)
- Education: update text and images in `#education`
- Experience: edit items in the timeline (`#experience`)
- Skills: add/remove badges in `#skills`
- Projects: edit titles, tech badges, descriptions, and GitHub URLs in `#projects`
- Contact: update email, phone, and social URLs in `#contact`

### Styling
- Colors: update CSS variables in `styles.css` under `:root`
- Buttons/badges/cards: see component sections in `styles.css`
- Navbar: spacing and hover effects under “NAVIGATION” rules

### Assets
- Hero illustration path: `Data analysis-pana.svg`
- Education logos: put files in `Images/` and reference in `index.html`

## 🚀 Deploy

### GitHub Pages
1. Create a repo and push files
2. Settings → Pages → Deploy from branch → `main`/`root`

### Netlify / Vercel
- Drag-and-drop (Netlify) or connect repo (Vercel) for instant deploys

## 📱 Responsiveness
- Tweaked breakpoints for navbar, timeline, cards, and grids
- Mobile refinements for icons, tech badges, and typography

## 🐛 Troubleshooting
- Images not showing: verify paths (`Images/…`) and file names
- CSS not applied: confirm `<link rel="stylesheet" href="styles.css">`
- Icons missing: ensure Font Awesome CDN is reachable

## 🙏 Credits
- Bootstrap 5, Font Awesome, Google Fonts
- Illustration inspired by Undraw/Storyset-style assets

—

If you fork this, remember to update contact info, project links, and images.
