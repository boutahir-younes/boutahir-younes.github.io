# Younes Boutahir, AI Engineer: Personal Portfolio Website

Portfolio website of Younes Boutahir, a Master's student in Decision-Making Information Systems and Imaging and an aspiring AI engineer working on deep learning, computer vision and LLM applications. The site presents projects, skills, education and certifications in a single fast page.

**Live site:** [boutahir-younes.github.io](https://boutahir-younes.github.io)

---

## Table of Contents

1. [Overview](#overview)
2. [Sections](#sections)
3. [Features](#features)
4. [Technology](#technology)
5. [Project Structure](#project-structure)
6. [Run Locally](#run-locally)
7. [Deployment](#deployment)
8. [Customization](#customization)
9. [Contact](#contact)
10. [License](#license)

---

## Overview

This is a static website written in plain HTML, CSS and JavaScript. It has no framework, no build step and no dependencies other than two web fonts, so it loads quickly and can be hosted for free on GitHub Pages.

The design is deliberately restrained: a clear hero section, a list of projects with measurable results, and a layout that works equally well for a recruiter reading on a phone and an engineer reading on a desktop.

## Sections

| Section | Content |
|---|---|
| Hero | Name, professional focus, short summary, CV download and an illustration of a latent space |
| Projects | IoT botnet detection (VAE and XGBoost), hospital management system with disease prediction, real-time tennis ball tracking |
| Skills | Deep learning, machine learning, computer vision, LLM applications, data and software tools |
| Education | Master SIDI, Bachelor's degree in Software Engineering, DEUST, Baccalauréat |
| Certifications | IBM AI Engineering Professional Certificate (Coursera) |
| Contact | Email, LinkedIn and GitHub |

## Features

- Light and dark themes. The site follows the system preference by default, and the visitor's choice is remembered.
- Responsive layout for phones, tablets and desktops.
- Keyboard navigation, visible focus states and a skip-to-content link.
- Respect for the reduced-motion setting of the operating system.
- Semantic HTML with page metadata and structured data for search engines.
- CV download with a clear file name for the recruiter.

## Technology

- HTML5
- CSS3 (custom properties for theming, grid and flexbox for layout)
- JavaScript (no libraries)
- Google Fonts: Bricolage Grotesque and IBM Plex Sans
- GitHub Pages for hosting

## Project Structure

```text
boutahir-younes.github.io/
├── index.html                # The whole website: markup, styles and scripts
├── photo.png                 # Profile picture
├── CV_BOUTAHIR_YOUNES.pdf    # CV offered for download
└── README.md
```

## Run Locally

Clone the repository and open `index.html` in a browser:

```bash
git clone https://github.com/boutahir-younes/boutahir-younes.github.io.git
cd boutahir-younes.github.io
```

Then open `index.html` directly, or serve the folder with any static server, for example:

```bash
python -m http.server 8000
```

and visit `http://localhost:8000`.

## Deployment

The site is deployed with GitHub Pages.

1. Name the repository `<username>.github.io`.
2. In the repository, open **Settings**, then **Pages**.
3. Choose the `main` branch and the root folder as the source.
4. The site is available at `https://<username>.github.io` after a short build.

## Customization

**Add a project.** In `index.html`, copy one `<article class="project">` block, then change the title, technology list, description, result and repository link.

**Update the CV.** Replace `CV_BOUTAHIR_YOUNES.pdf` with the new file under the same name. To rename it, change the `href` of the download button in `index.html` as well. The `download` attribute controls the name the visitor sees when saving the file.

**Add a certification.** In the Certifications section, copy the `<div class="cert">` block and edit it. Add the credential link so that recruiters can verify it.

## Contact

- Email: boutahir.younes1@gmail.com
- LinkedIn: [linkedin.com/in/younes-boutahir](https://linkedin.com/in/younes-boutahir)
- GitHub: [github.com/boutahir-younes](https://github.com/boutahir-younes)

## License

Released under the [MIT License](https://opensource.org/licenses/MIT).
