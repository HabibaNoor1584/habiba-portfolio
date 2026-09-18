# Habiba Noor — Academic Portfolio

A simple, static academic portfolio website. No build tools, no frameworks — just HTML, CSS, and JavaScript.

## Files

- `index.html` — all the page content and structure
- `style.css` — all the visual design
- `script.js` — mobile menu + scroll animations
- `assets/` — put your profile photo and CV here
- `assets/certificates/` — put certificate images/PDFs here

## Where to edit things

| What you want to change | Where to go |
|---|---|
| Name, headline, intro text | `index.html`, the `<section class="hero">` block |
| About paragraph | `index.html`, `<section id="about">` |
| Add/edit a research focus area | `index.html`, `<div class="focus-grid">` — copy one `.focus-card` block |
| Thesis details | `index.html`, `<section id="experience">` |
| Lab experience cards | `index.html`, `<section id="lab-experience">` |
| Education entries | `index.html`, `<ul class="timeline">` |
| Skills | `index.html`, `<section id="skills">` |
| Biotech Squad / BioSkillz | `index.html`, `<section id="leadership">` and `<section id="bioskillz">` |
| Achievements | `index.html`, `<div class="achieve-grid">` |
| Certificates | `index.html`, `<div class="cert-grid">` — replace a `.cert-card` with your own, and add the file to `assets/certificates/` |
| Email / LinkedIn / GitHub | `index.html`, `<section id="contact">` — replace `YOUR_EMAIL_HERE`, `YOUR_LINKEDIN_URL_HERE`, `YOUR_GITHUB_URL_HERE` |
| Profile photo | Add a file named `profile.jpg` inside `assets/` |
| CV | Add a file named `Habiba-Noor-CV.pdf` inside `assets/` |
| Publications (future) | `index.html`, `<section id="publications">` — remove the `hidden` attribute once you have something to show |
| Colors / fonts | `style.css`, the `:root { ... }` block at the top |

## Adding a new project or certificate later

Copy an existing card block (e.g. a `.focus-card`, `.lab-card`, or `.cert-card`) in `index.html` and edit the text — you don't need to touch the CSS.
