# Amanyire Joshua Muhinda — Portfolio Website

A sober, static personal portfolio website for Amanyire Joshua Muhinda, focused on Linux systems, enterprise networking, and resilient infrastructure.

Live site: [amanyirejoshua.github.io/portfolio-website](https://amanyirejoshua.github.io/portfolio-website/)

## Overview

This repository contains the source for a single-page portfolio site intended for general professional networking — recruiters, scholarship/research supervisors, collaborators, and other professional contacts. It is designed to be clear, credible, and lightweight rather than flashy.

## What's inside

- **Hero / About** — professional identity and technical focus
- **Experience & Recognition** — internship, Huawei ICT Competition Global Finals recognition, and technical leadership
- **Projects & Research** — ResilientUG (final-year research, in progress) and selected projects
- **Skills** — grouped by systems, networking, tooling, and security/scripting
- **Certifications** — selected credentials and training
- **Contact** — Formspree contact form and public profile links
- **Public CV** — a sanitized downloadable CV (`assets/Amanyire_Joshua_Muhinda_CV.pdf`) with personal contact details and referees removed

## Tech

- Plain **HTML**, **CSS**, and a small amount of vanilla **JavaScript**
- No build step required
- Google Fonts (Inter) loaded from CDN
- Formspree for contact form handling

## Project structure

```text
portfolio-website/
├── assets/
│   ├── Amanyire_Joshua_Muhinda_CV.pdf   # Sanitized public CV
│   ├── favicon.svg
│   ├── profile.jpg
│   ├── project-healthcare-chatbot.jpg
│   └── project-nkozi-online.jpg
├── index.html
├── styles.css
├── LICENSE
└── README.md
```

## Local preview

Because this is a static site, you can open `index.html` directly, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Privacy note

The public CV included in this repository is intentionally sanitized. It does not include phone numbers, personal/student email addresses, referee contact details, or other sensitive personal information.

## License

The source code in this repository is available under the [MIT License](LICENSE). Attribution is appreciated when reusing or adapting the design/content structure.
