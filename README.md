# Prabhat Kumar Singh — Personal Portfolio

A modern, responsive personal portfolio website for **Prabhat Kumar Singh**, Manager – Business Operations, with 12+ years of experience driving operational excellence, merchant & OEM onboarding, process automation, and data reconciliation across leading fintech platforms (Pine Labs, Paytm).

Built with plain **HTML, CSS, and JavaScript** — no frameworks, no build step.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## ✨ Features

- **Dark navy + gold** professional theme
- Fully **responsive** layout (desktop, tablet, mobile)
- Sticky navigation bar with scroll state and **scrollspy** active links
- **Scroll-reveal** animations on every section
- Animated **count-up** statistics (years, accuracy, awards)
- Smooth scrolling between sections
- Mobile **hamburger menu**
- Sections: Hero, About, Expertise, Experience (Professional Journey), Projects, Recognition & Impact, Insights, Contact

---

## 📁 Project Structure

```
portfolio/
├── index.html        # Page markup / all sections
├── style.css         # Styling, theme tokens, responsive rules
├── script.js         # Nav, scrollspy, reveal & count-up animations
├── assets/
│   └── profile.png   # Profile photo
└── README.md
```

---

## 🚀 Getting Started

No installation or dependencies required.

### Run locally

Simply open the file in a browser:

```bash
open index.html        # macOS
# or just double-click index.html
```

Or serve it with any static server (recommended, so fonts/assets load over HTTP):

```bash
# Python 3
python3 -m http.server 8000
# then visit http://localhost:8000
```

> An internet connection is needed for the Google Fonts (Inter & Cormorant Garamond); everything else works offline.

---

## 🌐 Deploy with GitHub Pages

1. Create a new repository on GitHub (e.g. `portfolio`).
2. Push this folder's contents to the repo:

   ```bash
   git init
   git add .
   git commit -m "Initial commit: portfolio website"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```

3. On GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`, choose the **`main`** branch and **`/ (root)`** folder, then **Save**.
5. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

> Make sure `index.html` is at the root of what you publish. If you push the whole project, set the Pages folder accordingly or move the `portfolio` files to the repo root.

---

## 🎨 Customization

- **Colors / theme** — edit the CSS variables in the `:root` block at the top of `style.css` (`--gold`, `--navy-900`, etc.).
- **Content** — update text directly in `index.html`.
- **Profile photo** — replace `assets/profile.png`.
- **Stats** — change the `data-count` / `data-suffix` attributes on the stat cards in `index.html`.
- **Contact info** — update the email, phone, and LinkedIn links in the Contact section and footer.

---

## 📬 Contact

- **Email:** singh.prabhat21@gmail.com
- **Phone:** +91-9717010478
- **Location:** Ghaziabad, Uttar Pradesh, India

---

© 2026 Prabhat Kumar Singh. All rights reserved.
