# Front_Page-Example-Project

A front page development exercise based on the **Fyrre Magazine** Figma design.  
The goal: pixel-perfect implementation, accessible code, and product-thinking approach.
Live page: https://ygolan93.github.io/Front_Page-Example-Project/
---

## 🛠️ Tech Stack

- **HTML5** – Semantic and accessible structure
- **CSS3 (vanilla)** – Fully custom styling, without frameworks
- **Google Fonts** – Anton, Fraunces, and Work Sans
- **PerfectPixel** (extension) – Used to align design precisely with the Figma reference

---

## 🎯 Goals & Priorities

- ✅ **Pixel Perfect** match to the [Figma design](https://www.figma.com/design/O1PFIDsirrFUZUdCqNeSK4/Fyrre---Magazine-Website---Webflow-Template--Community)
- ✅ Fully **responsive** layout (Desktop, Tablet, Mobile)
- ✅ Strong **typography & spacing** matching the visual grid
- ✅ **Semantic HTML**: using `<main>`, `<section>`, `<article>`, `<aside>`, etc.
- ✅ Accessibility: `alt`, keyboard focus, screen reader support
- ✅ SEO-ready structure: correct heading hierarchy, meaningful metadata

---

## ♿ Accessibility (a11y)

- Semantic tags: `main`, `nav`, `section`, `article`, `footer`
- Descriptive `alt` attributes for all images
- Clear `aria-label`s where needed
- Keyboard-navigable buttons and links
- Visual focus indicators (via browser default)

---

## 📈 SEO + E-E-A-T

- Structured heading levels: `h1` > `h2` > `h3`
- Descriptive page `<title>`
- Meta viewport for responsive scaling
- Suggested future additions:
  - Meta description
  - Open Graph / Twitter Cards
  - Structured Data (JSON-LD) – `Magazine`, `Article`, or `Organization`

---

## 📦 Folder Structure

Front_Page-Example-Project/
│

├── Assets/ → All images used in the project

├── index.html → Main page markup

├── README.md → This file



> Note: Currently using inline `<style>`, but future iterations may migrate to SCSS or utility frameworks depending on scope.

---

## 🔮 Product Thinking: What’s Missing?

This is only the homepage. For a complete product experience, the following pages or features would be valuable:

- **Article page** – Full-length reading experience
- **About / Editorial team** – Credibility + trust (E-E-A-T)
- **Search** or **Categories** – Content discovery
- **Blog/Updates** – Fresh content for SEO
- **Newsletter management** – Real form with backend integration
- **Dark Mode / Theme toggle** – Accessibility + user preference
- **Real-time ticker / dynamic content** – Improve UX for updates

---

## ✅ To-do / Improvements

- [ ] Break CSS into modular SCSS files (`base`, `layout`, `components`)
- [ ] Use design tokens for spacing, colors, font-sizes
- [ ] Add Structured Data (JSON-LD)
- [ ] Improve README screenshots / visual comparisons (before/after)
- [ ] Publish via GitHub Pages or Netlify
