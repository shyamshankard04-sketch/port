# Personal Portfolio Website: Shyam Shankar D

Week 1 project (Web Foundations: HTML, CSS, Git & GitHub). A responsive, static portfolio site deployed on GitHub Pages.

- **Live site:** _add your GitHub Pages link here_
- **Repository:** _add your repo link here_

## Project requirements and how they were met

| Requirement | Implementation |
|---|---|
| Header (name + navigation) | Sticky `<header>` with logo and `<nav>` linking to every section |
| About Me | `<section id="about">` with summary, education, interests, languages |
| Skills (icons) | CSS Grid of 10 skill cards using Devicon SVG icons |
| Projects (at least 2) | Cascade Guard and Railway Reservation System as `<article>` cards |
| Contact | Email (`mailto:`), GitHub and LinkedIn links |
| Responsive | Fluid layouts, media queries, mobile hamburger menu |
| Deployed on GitHub Pages | Static files served from the `main` branch root |

## Tech and concepts used

- **Semantic HTML5:** `header`, `nav`, `main`, `section`, `article`, `footer`, with headings in order and `alt` text / `aria-label` for accessibility.
- **CSS3:**
  - Custom properties (variables) for the colour theme.
  - **Flexbox** for the header, hero buttons and About layout.
  - **CSS Grid** (`repeat(auto-fit, minmax())`) for skills, projects and certifications, so columns adapt without extra breakpoints.
  - **Media queries** at 860px and 768px for the mobile menu and stacked layouts.
  - `prefers-color-scheme` for automatic dark mode.
  - Pure-CSS hamburger menu (hidden checkbox + `:checked` selector), so no JavaScript is needed.
- **Git & GitHub:** version-controlled with commits, pushed to GitHub, published via GitHub Pages.

## File structure

```
index.html   # all page content
style.css    # all styling and responsiveness
README.md    # this file
```

## Run locally

Open `index.html` in a browser (or use the VS Code Live Server extension).
