# Atheeq R – Online Resume / Portfolio

This repository contains my interactive resume site, built as a lightweight, static portfolio hosted on GitHub Pages.

🔗 **Live site:**  
https://atheeqsyed.github.io/atheeq-portfolio/

## Overview

The site is a one-page resume with a couple of supporting pages:

- **Home (`index.html`)** – Summary, tech stack, skills, experience, projects, education and a brief contact panel.
- **Hobbies & Interests (`Hobbies.html`)** – A short personal page covering interests outside work.
- **Contact (`Contact.html`)** – Full contact details plus a live contact form powered by Formspree.

The design focuses on:

- A clean dark/light theme with a toggle.
- Tech-stack badges and logos for core tools I use.
- Clear, recruiter-friendly layout for my experience and skills.

## Tech Stack

- **HTML5 / CSS3**
- **Vanilla JavaScript** (no framework)
- Dark / light mode using a simple theme toggle and `localStorage`.
- Contact form submission via [Formspree](https://formspree.io/) (static-friendly backend).

## Features

- Responsive layout suitable for desktop and mobile.
- Sticky navigation with section highlighting.
- Dynamic “Tech Stack” section rendered from a JavaScript data structure.
- Live contact form:
  - Basic validation (name, email, message length).
  - Loading state with spinner.
  - Success / error messages.
- Quality-of-life helpers:
  - “Copy email to clipboard” button.
  - Direct WhatsApp link.
- SEO enhancements:
  - Custom `<title>` and `<meta description>` per page.
  - Open Graph + Twitter card tags.
  - Favicon and social preview image.

## Local Development

You can open the site directly in a browser:

```bash
# clone the repo
git clone https://github.com/atheeqsyed/atheeq-portfolio.git
cd atheeq-portfolio

# then open index.html in your browser
