# Alan Siby — Portfolio Website

Personal portfolio site for Alan Siby, incoming Mechanical Engineering student at UT Austin. Showcases research, CAD/fabrication projects, resume, and contact info.

**Live site:** [alansiby07.github.io/portfolio](https://alansiby07.github.io/portfolio/)

## Pages

- `index.html` — Home page with a timeline of experience/milestones and selected projects
- `projects.html` — Full project index
- `resume.html` — Resume with education, research experience, projects, and skills
- `about.html` — About page
- `contact.html` — Contact page
- `printable.html` — Printable version of the portfolio

## Projects Featured

**Research**
- **Spacecraft Attitude Control** — Published research on engrXiv modeling a 1-axis PD control system with reaction wheel saturation

**High School**
- **Cam**
- **Cardboard Chair**
- **Castle Project**
- **Golf**
- **Hair Dryer**
- **Magic Snap** — Ergonomic, magnetic-charging redesign of the Apple Magic Mouse
- **Puzzle Cube**
- **Trammel Toy**

**Personal**
- **RC Car** (in progress)
- **Charging Stand** (in progress)

## Tech Stack

- HTML5 / CSS3
- Vanilla JavaScript (scroll-reveal animations via `IntersectionObserver`)
- Google Fonts (DM Serif Display, DM Sans)
- Hosted on GitHub Pages

## Project Structure

```
portfolio/
├── index.html
├── projects.html
├── resume.html
├── about.html
├── contact.html
├── printable.html
├── style.css
├── projects/
│   ├── research/
│   │   └── spacecraft-attitude-control/
│   │       └── media/
│   ├── hs/
│   │   ├── cam/
│   │   │   └── media/
│   │   ├── cardboard-chair/
│   │   │   └── media/
│   │   ├── castle-project/
│   │   │   └── media/
│   │   ├── golf/
│   │   │   └── media/
│   │   ├── hair-dryer/
│   │   │   └── media/
│   │   ├── magic-snap/
│   │   │   └── media/
│   │   ├── puzzle-cube/
│   │   │   └── media/
│   │   └── trammel-toy/
│   │       └── media/
│   └── personal/
│       ├── rc-car/
│       │   └── media/
│       └── charging-stand/
│           └── media/
└── Alan.Siby.Resume.pdf
```

Each project folder contains its own `media/` subfolder holding the images/screenshots used on that project's page.

## Deployment

This site is deployed via **GitHub Pages** directly from this repository — no build step is required. Any push to the main branch updates the live site automatically at [alansiby07.github.io/portfolio](https://alansiby07.github.io/portfolio/).

## Editing Locally

Since this is a static site, you can edit the HTML/CSS files directly and preview changes by opening them in a browser — no server or clone required to just view the live site. If you want to test local edits before pushing, clone the repo and open `index.html` directly in a browser (or use a simple local server if you run into asset-loading issues):

```bash
git clone https://github.com/alansiby07/portfolio.git
cd portfolio
python3 -m http.server 8000
```

## Contact

Reach out via the [Contact page](https://alansiby07.github.io/portfolio/contact.html).
