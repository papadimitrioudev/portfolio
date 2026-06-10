# papadimitriou.dev — Personal Portfolio

Personal portfolio website of **Panagiotis Papadimitriou** — Computer Science graduate
training toward backend development with Java & Spring Boot.

**Live:** [papadimitrioudev.netlify.app](https://papadimitrioudev.netlify.app)

## About

Hand-coded single-file site — no frameworks, no templates, no build step.

- Vanilla HTML / CSS / JavaScript in one `index.html`
- Dark developer theme: canvas starfield, mouse spotlight, 3D tilt cards,
  magnetic buttons, scroll-reveal animations
- Fully responsive, respects `prefers-reduced-motion`
- CV available as downloadable PDF

## Structure

```
portfolio-site/
├── index.html                          # the entire site
├── Panagiotis_Papadimitriou_CV.pdf     # CV (linked from the site)
└── README.md
```

## Run locally

No dependencies — just open `index.html` in a browser.

## Deploy

Deployed on Netlify. Any push to `main` triggers a redeploy
(when the repo is connected to Netlify).
