# Juma Abedneco — Personal Portfolio

A modern, responsive personal portfolio website built to showcase my background, skills, and coursework projects as a Computer Science student — designed to be shared with employers, internship/attachment opportunities, and freelance clients.

**Live site:** _[Add your GitHub Pages URL here once deployed — see deployment steps below]_

---

## About the Project

This portfolio presents who I am as a Computer Science student at The Kitale National Polytechnic, the skills I've built across my diploma programme, and coursework/practice projects spanning desktop applications, databases, networking, and web development.

It's a single-page site with a fixed navigation bar linking to each section:

`Home → About → Skills → Projects → Education → Experience → Certificates → Contact`

The site is intentionally honest about what's real and what's a placeholder — for example, project "View" and "GitHub" links are clearly marked as inactive until real links exist, and the contact form does not pretend to send messages, since no backend/email service is connected yet.

## Features

- Responsive layout — works on mobile, tablet, and desktop
- Fixed navigation with active-section highlighting and a mobile hamburger menu
- Hero section with profile photo and quick facts
- About section with a "What I Do" breakdown
- Skills organized by category (Programming, Web Development, Databases, Networking & IT, Tools)
- Project cards with technology badges and clearly-marked placeholder links (no fake URLs)
- Education timeline and Industrial Attachment section
- Certificates section, ready to be filled in as certificates are earned
- Contact section with a frontend-only form (no messages are actually sent until a backend/email service is added)
- Basic SEO: page title, meta description, Open Graph tags, favicon
- Subtle entrance animations and hover states (motion is reduced automatically if the visitor's system requests it)
- Accessible: semantic HTML, skip-to-content link, visible focus states, labeled form fields, alt text on images

## Technologies Used

- **HTML5** — semantic page structure
- **CSS3** — custom properties (design tokens), Flexbox, Grid, responsive media queries
- **Vanilla JavaScript** — mobile navigation, scroll-based active link highlighting, form handling
- No frameworks or build tools — plain, dependency-free front-end code

## Project Structure

```
portfolio/
├── index.html              # All page content and structure
├── css/
│   └── style.css           # All styling (design tokens, layout, responsive rules)
├── js/
│   └── script.js           # Navigation, scroll behavior, contact form handling
├── assets/
│   ├── images/
│   │   ├── profile.jpg          # Profile photo
│   │   ├── favicon.svg          # Favicon (modern browsers)
│   │   ├── favicon.ico          # Favicon (legacy browsers)
│   │   ├── apple-touch-icon.png # iOS home-screen icon
│   │   └── icon-512.png         # Open Graph / share preview image
│   └── cv/
│       └── Juma-Abedneco-CV.pdf # CV file (add your own — see note below)
└── README.md
```

> **Note:** `assets/cv/Juma-Abedneco-CV.pdf` is not included in this repository yet. Add your own CV file with that exact filename and the "Download CV" button will work automatically.

## How to Run Locally

No build step or server is required — it's a static site.

1. Clone or download this repository.
2. Open `index.html` directly in a browser, **or** for the best experience (so relative paths and any future backend calls behave like a real site), serve it locally:

   ```bash
   # Python 3
   python3 -m http.server 8000
   ```

   Then visit `http://localhost:8000` in your browser.

## Screenshots

_[Add screenshots of your site here once deployed — e.g. a hero section screenshot and a mobile view]_

```
![Homepage](screenshots/home.png)
![Mobile view](screenshots/mobile.png)
```

## Live Website

_[Add your live GitHub Pages URL here after deployment, e.g.]_
`https://[your-github-username].github.io/juma-abedneco-portfolio/`

## Author

**Juma Abedneco**
Computer Science Student, The Kitale National Polytechnic
Email: abednecojuma39@gmail.com
