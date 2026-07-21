# Portfolio — Chinkhusel Batsuuri

Personal portfolio website showcasing my projects, skills, and background as a Software Engineering student. Built as a static, single-page site with vanilla HTML, CSS, and JavaScript — no frameworks or build tools required.

 **Live site:** https://khuslee0409.github.io/Portfolio/index.html

---

## Overview

The site is a one-page layout (`index.html`) with sections for Home, About, Projects, Skills, and Contact, plus dedicated detail pages for individual projects.

- **Home** — intro, name, title, and social links
- **About** — short bio (Software Engineering student at Macquarie University)
- **Projects** — card grid linking out to project detail pages and GitHub repos
- **Skills** — Java/JavaFX, Spring Boot, SQL, HTML/CSS
- **Contact** — social links (Discord, LinkedIn, GitHub)

---

## Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | Vanilla CSS (`styles.css`, `portfolio.css`) |
| Interactivity | Vanilla JavaScript (`script.js`) |
| Fonts | Google Fonts (Inter, Poppins) |
| Hosting | Static hosting (no backend/build step needed) |

No frameworks, bundlers, or package managers are used — the site runs directly from static files.

---

## Features

- **Responsive navigation** with a mobile hamburger menu toggle
- **Scroll-based active nav highlighting** via `IntersectionObserver`
- **Scroll-reveal animations** — elements fade/slide in as they enter the viewport
- **Sticky header** that gains a background/shadow on scroll
- **Dynamic copyright year** in the footer
- **Dedicated project pages** for deeper dives into individual projects

---

## Project Structure

```
Portfolio/
├── index.html            # Main landing page (Home, About, Projects, Skills, Contact)
├── mp3player.html         # Project detail page — Mp3Player (Java/JavaFX)
├── taskplanner.html       # Project detail page — Task Planner (Spring Boot)
├── styles.css              # Main site styling
├── portfolio.css           # Additional/project-page styling
├── script.js                # Nav toggle, scroll effects, reveal animations
└── pics/                    # Images, screenshots, icons
```

---

## Featured Projects

### Mp3Player
A Java-based desktop music player with playlist management, play/pause/restart, skip forward/back, speed control, and a live progress bar.
**Tech:** Java, JavaFX, OOP
**Repo:** [github.com/khuslee0409/MP3player](https://github.com/khuslee0409/MP3player)

### Task Planner
A full-stack productivity app for managing tasks, deadlines, and schedules, with secure login and personalized data storage.
**Tech:** Spring Boot, SQL, JWT Auth
**Backend repo:** [github.com/khuslee0409/TaskPlanner](https://github.com/khuslee0409/TaskPlanner)
**Frontend repo:** [github.com/khuslee0409/TaskPlannerFrontEnd](https://github.com/khuslee0409/TaskPlannerFrontEnd)

---

## Running Locally

No build step is required — just open the site in a browser.


## Deployment

As a static site, this is deployed on github pages.

---

## Contact

- **LinkedIn:** [linkedin.com/in/chinkhuselbatsuuri](https://www.linkedin.com/in/chinkhuselbatsuuri/)
- **GitHub:** [github.com/khuslee0409](https://github.com/khuslee0409)
- **Discord:** available via the contact section on the live site

---

## License

No license specified yet.
