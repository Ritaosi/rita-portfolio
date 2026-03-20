# Rita C. Osi — Product Manager Portfolio

> Personal portfolio for Rita C. Osi — Product Manager, Builder, and Researcher.

**🌐 Live Site:** [rita-portfolio-mauve.vercel.app](https://rita-portfolio-mauve.vercel.app)  
**📁 GitHub Repo:** [github.com/Ritaosi/rita-portfolio](https://github.com/Ritaosi/rita-portfolio)

---

## About

A single-file HTML/CSS/JS portfolio showcasing Rita's internship experience at IBM and HashiCorp, research at Indiana University, founding product work at PopUp, academic honors, and published work. Designed to be fast, self-contained, and easy to update — no frameworks, no build tools, no dependencies beyond Google Fonts.

---

## ✨ Features

- **Single file** — the entire site lives in `index.html`, making hosting and updates trivial
- **Custom animated cursor** — coral dot with a trailing ring that reacts to hover states
- **Scroll reveal animations** — sections fade and slide in as you scroll, with a safe fallback so content is always visible even if JS is slow
- **Fully responsive** — mobile-friendly layout with adaptive typography and grids
- **Live project links** — cards in the Projects section link directly to real work:
  - [PopUp Campus](https://apps.apple.com/us/app/popup-campus/id6752616780) on the App Store
  - [Cross Project Service Principals](https://www.hashicorp.com/blog/hcp-expands-service-principals-access-options-and-role-assignments) — HashiCorp blog post
  - [LLMCarbon — arXiv paper](https://arxiv.org/abs/2309.14393)
  - [LLMCarbon — Montreal AI Ethics](https://montrealethics.ai/llmcarbon-modeling-the-end-to-end-carbon-footprint-of-large-language-models/)

---

## 🛠 Tech Stack

| Layer | Choice |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, grid, flexbox, keyframe animations) |
| Scripting | Vanilla JavaScript (IntersectionObserver, requestAnimationFrame) |
| Fonts | Google Fonts — Playfair Display, DM Sans, DM Mono |
| Hosting | Vercel (auto-deploys on every push to `main`) |

No npm. No build step. No frameworks.

---

## 📁 Project Structure

```
rita-portfolio/
├── index.html      # The entire site — styles, markup, and scripts in one file
└── README.md       # This file
```

---

## 🚀 Deployment

This site is deployed on **Vercel** and connected to this GitHub repository. Every push to the `main` branch automatically triggers a redeployment.

**Live URL:** [https://rita-portfolio-mauve.vercel.app](https://rita-portfolio-mauve.vercel.app)

To make an update:
1. Edit `index.html` locally or directly on GitHub
2. Commit and push to `main`
3. Vercel redeploys automatically — usually live within 30 seconds

---

## 📐 Sections

| # | Section | Content |
|---|---|---|
| 01 | Hero | Name, tagline, key stats (2000+ users, 35+ interviews, 4.0 GPA), CTAs |
| 02 | Experience | PopUp, IBM, HashiCorp, Indiana University |
| 03 | Skills | Product, Engineering, Tools & Platforms |
| 04 | Honors | Ginkgo Fellowship, Provost Scholar, Entergy Award, Du Bois Honors College, BVCC, Bloomberg TechLab |
| 05 | Projects | Shipped work with live links |
| 06 | Education | Jackson State University · Columbia University |
| 07 | Contact | Email, LinkedIn, GitHub, phone |

---

## ✏️ How to Update

Everything lives in `index.html`. Here's where to find each section:

**Add a new role**
```html
<!-- Inside <div class="exp-grid"> in #experience -->
<div class="exp-card reveal">
  <div class="exp-meta">
    <div class="exp-company">Company Name</div>
    <div class="exp-period">Month Year – Month Year</div>
    <div class="exp-location">City, State</div>
  </div>
  <div class="exp-content">
    <div class="exp-role">Your Role Title</div>
    <ul class="exp-bullets">
      <li>Bullet point with <span class="exp-highlight">highlighted metric</span></li>
    </ul>
  </div>
</div>
```

**Add a new project with a link**
```html
<!-- Inside <div class="projects-grid"> in #projects -->
<div class="project-card reveal">
  <div class="project-tech">Tech · Stack · Here</div>
  <div class="project-title">Project Name</div>
  <div class="project-desc">Brief description of what you built and the impact.</div>
  <div class="project-links">
    <a class="project-link-btn" href="https://your-link.com" target="_blank" rel="noopener">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" width="10" height="10"><path d="M18 13v6a2 2 0 01-2 2H5a2 2 0 01-2-2V8a2 2 0 012-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
      Link Label
    </a>
  </div>
</div>
```

**Update hero stats**
```html
<!-- In the .hero-stats div -->
<div class="stat-num">2000<span>+</span></div>
<div class="stat-label">Active Users</div>
```

---

## 🎨 Design System

**Colors**

| Token | Value | Usage |
|---|---|---|
| `--coral` | `#ff5c3a` | Primary accent, CTAs, section labels |
| `--amber` | `#f5a623` | Role titles, project tech tags |
| `--lavender` | `#a78bfa` | Education section accents |
| `--bg` | `#0b0b0f` | Page background |
| `--surface` | `#111118` | Alternate section backgrounds |
| `--surface2` | `#17171f` | Card backgrounds |
| `--text` | `#e8e6f0` | Primary text |
| `--muted` | `#6b6880` | Secondary / supporting text |

**Typography**

| Role | Font |
|---|---|
| Display & headings | Playfair Display (serif) |
| Body & UI | DM Sans (sans-serif) |
| Labels & monospace | DM Mono |

---

## 📬 Contact

**Rita C. Osi**  
[chukwunyereosi@gmail.com](mailto:chukwunyereosi@gmail.com)  
[linkedin.com/in/rita-osi](https://www.linkedin.com/in/rita-osi/)  
[github.com/Ritaosi](https://github.com/Ritaosi)
