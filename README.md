# My Engineering Portfolio

A clean, minimal personal e-portfolio for a mechanical engineering student. Built with plain HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies, no build step.

## 🚀 Live Site

Deploy instantly with **GitHub Pages**:
1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under *Source*, select `main` branch and `/ (root)`
4. Click **Save** — your site will be live at `https://yourusername.github.io/repo-name`

## 📁 Structure

```
portfolio/
├── index.html   # The entire site (HTML + CSS + JS in one file)
└── README.md
```

## ✏️ Customizing

Everything to change is in `index.html`. Search for the following placeholders:

| Placeholder | Where to find it |
|---|---|
| `Alex Chen` | `<title>`, nav logo, footer |
| `alex.chen@email.com` | Contact section |
| `linkedin.com/in/alexchen-me` | Contact section |
| `github.com/alexchen-eng` | Contact section |
| `3rd`, `3.7` GPA, year | About stats |
| Project titles & descriptions | Projects section |
| `Austin, TX` | About & contact |
| `Summer 2025` | Contact intro |

To add your **resume PDF**: drop `resume.pdf` into the repo root and update the résumé link in the contact section:
```html
<a href="resume.pdf" class="contact-link">
```

## 🛠 Tech

- Pure HTML5 / CSS3 / vanilla JS
- [DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts
- Scroll-triggered reveal animations via `IntersectionObserver`
- Fully responsive down to mobile
- No frameworks, no npm, no build step needed
