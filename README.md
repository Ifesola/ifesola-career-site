# Personal Career Website

A multi-page professional portfolio website featuring a résumé, cover letter, and career goals page with interactive elements and dark mode support.

---

##  Project Structure

```
ifesola-career-site/
│
├── resume.html         # Résumé page (home)
├── cover-letter.html   # Cover letter
├── career.goals.html   # Career goals page with media + contact form
├── style.css           # Global styling shared across all pages
├── images/             # Profile photo and other images
├── audio/              # Intro audio clip (career goals page)
├── video/              # Career goals video
└── docs/               # Downloadable résumé files (PDF/DOCX)
```

---

##  Features

###  Semantic HTML5
- Uses `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`
- Improves structure and accessibility

###  Consistent Navigation
- Links between Résumé, Cover Letter, Career Goals

###  Responsive Header Layout
- Profile image + name + job title
- Contact information section
- Auto-updating date

###  Dark Mode Toggle
- JavaScript toggles a `.dark-theme` class on `<body>`

###  Dynamic Dates
Auto-updates:
- "Last updated" on résumé
- Date in cover letter

###  Media-Rich Career Page
- Embedded audio intro
- Embedded video explaining career path
- Contact form posts to Zybooks viewer endpoint

###  Downloadable Résumé
- Button styled for PDF/DOCX downloads via the `docs/` folder

---

##  Tech Stack

- **HTML5** – semantic layout
- **CSS3** – styling, typography, animations
- **JavaScript** – theme toggle, date logic
- **Git & GitHub** – version control and hosting

---

##  How to Run Locally

### 1. Clone the repository:
```bash
git clone https://github.com/ifesola/ifesola-career-site.git
cd ifesola-career-site
```

### 2. Open the website:
- Double-click `resume.html`, or 
- Run with VS Code Live Server
- Live demo Link - https://ifesola.github.io/ifesola-career-site/index.html

### 3. Navigate the site:
- `resume.html`
- `cover-letter.html`
- `career.goals.html`

---

##  Learning Outcomes

This project demonstrates:

- Building a multi-page HTML/CSS portfolio
- Using semantic structure for clean layout
- Applying animations + transitions
- Managing responsive layouts
- Creating a dark mode system
- Embedding media on the web
- Using Git for version control and GitHub hosting

---

##  License

This project is for **educational and personal portfolio use**.

You're welcome to reference the structure or ideas, but please do not copy the content.

---

##  Author

**Ifesola Fadare**  
[GitHub](https://github.com/ifesola) | [Live Demo](https://ifesola.github.io/ifesola-career-site/)

---

** Star this repo if you found it helpful!**
