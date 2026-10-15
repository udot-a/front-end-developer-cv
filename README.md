# Andrii Udot — CV

Personal CV site: a single, dependency-free HTML page with light/dark themes and scroll-driven animations, hosted on GitHub Pages.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white)

**[Open the CV](https://udot-a.github.io/front-end-developer-cv/)** · [Download PDF](https://udot-a.github.io/front-end-developer-cv/CV_Andrii_Udot_Software_Engineer.pdf)

## Features

- **Light / dark theme** — follows the system setting, remembers a manual choice, and switches with a circular reveal (View Transitions API).
- **Animations** — staggered hero entrance, morphing gradient ring around the photo, floating tech badges, count-up stats, scroll reveal, a timeline line that fills as you scroll, and a pointer spotlight on cards.
- **Accessible by default** — semantic sections, labelled controls, and every animation disabled under `prefers-reduced-motion`.
- **Responsive** — tested down to 360 px wide with no horizontal scrolling.
- **Print-friendly** — a print stylesheet turns the page into a plain one-column CV.
- **Zero build step** — one `index.html` with inline CSS and JS; only Google Fonts load from outside.

## Structure

```text
index.html                              # the whole site: markup, styles, scripts
avatar.jpeg                             # portrait
CV_Andrii_Udot_Software_Engineer.pdf    # downloadable CV
favicon.svg · favicon.ico
.nojekyll                               # serve files as-is, skip Jekyll
```

## Run locally

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

---

Built by **Andrii Udot** — [LinkedIn](https://www.linkedin.com/in/andrii-udot-09181519a) · [udot.dron@gmail.com](mailto:udot.dron@gmail.com)
