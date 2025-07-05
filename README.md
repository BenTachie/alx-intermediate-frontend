# 📐 Tailwind CSS Layouts & Semantic HTML Project

Welcome to the **Tailwind CSS Layouts & Semantic HTML Project** — a hands-on journey through building modern, responsive, and accessible web pages. This project combines utility-first Tailwind CSS layout design with industry-standard semantic HTML practices to help you master both form and function in frontend development.

---

## 🚀 What This Project Covers

This full-spectrum project is structured in two synergistic tracks:

### 🧱 Semantic HTML & Accessibility Track
Learn to structure your web pages using semantic HTML5 elements, optimize them for SEO, and apply ARIA roles to ensure your site is accessible to all users, including those relying on screen readers or assistive technology.

### 🎨 Tailwind CSS Layout Track
Explore responsive design using Tailwind CSS, Flexbox, and Grid — from basic columns to advanced layout patterns. Build mobile-first, scalable interfaces with clean, maintainable code.

---

## ✅ Project Tasks & Features

### 📂 `0x00-semantic_html/`

#### 📄 `0-index.html` – Basic Semantic Structure
- Built a valid HTML5 scaffold with `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>`.
- Introduced semantic tags: `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<footer>`.

#### 📄 `1-index.html` – SEO & Meta Tag Enhancements
- Added `meta` tags for `charset`, `viewport`, `description`, `keywords`, and `author`.
- Defined `<title>` for SEO visibility and browser tab naming.

#### 📄 `2-index.html` – Blog Post Layout Using Semantic HTML
- Structured a complete blog article using nested `<section>`, `<header>`, and `<figure>`.
- Applied heading hierarchy (`<h1>`, `<h2>`, `<h3>`) and `time` element for publication dates.
- Embedded accessibility-friendly image descriptions using `<figcaption>`.

#### 📄 `3-index.html` – Accessible Form with ARIA Roles
- Implemented a semantic `<form>` with `aria-labelledby`, `aria-required`, and `aria-live`.
- Ensured inputs are screen-reader-friendly and logically grouped.
- Included a live region for accessibility-aware form feedback.

---

### 📂 `0x02-tailwind-css/`

#### 🛠️ Tailwind CSS Setup
- Installed Tailwind via CLI & npm.
- Configured custom `input.css`, `output.css`, and `tailwind.config.js`.
- Enabled `--watch` mode for real-time development.

#### 📄 `1-index.html` – Basic 3-Column Grid Layout
- Created a responsive 3-column layout using `grid-cols-3`, `gap`, and padding utilities.

#### 📄 `2-index.html` – Nested Grid Layout
- Built a nested 2x2 grid with layout control and spacing using `grid-cols` and `gap`.

#### 📄 `4-flexbox_index.html` – Responsive Flexbox Layout
- Designed a horizontal sidebar-content layout using Flexbox.
- Applied responsive utility classes for width and stacking behavior.

#### 📄 `5-gridflex_index.html` – Grid + Flex Hybrid
- Combined CSS Grid and Flexbox for dynamic, content-spanning layouts.
- Demonstrated layout scalability using responsive `col-span` and breakpoints.

#### 📄 `6-imageGallery.html` – Responsive Image Gallery
- Built a mobile-first image gallery using `grid-cols-1` to `md:grid-cols-3`.
- Styled images with `rounded`, `shadow`, and responsive scaling.

---

## 🧠 Learning Outcomes

By completing this project, you'll gain hands-on experience in:

### ✅ Semantic HTML & Accessibility
- Structuring accessible, screen reader-friendly HTML5 documents.
- Using ARIA roles and live regions for dynamic content feedback.
- Optimizing pages for SEO using metadata and logical content hierarchy.

### ✅ Responsive UI Design with Tailwind
- Building mobile-first layouts with utility-first classes.
- Applying CSS Grid & Flexbox patterns within Tailwind.
- Creating reusable, visually polished UI components.

---

## 📚 Best Practices Checklist

A quick reference from this project’s roadmap:

- [x] Use semantic elements (`<header>`, `<main>`, `<article>`, etc.)
- [x] Define `lang`, `meta`, and `title` in the `<head>`
- [x] Maintain heading hierarchy (`<h1>` to `<h6>`)
- [x] Use ARIA roles where appropriate (`role="form"`, `aria-live="polite"`)
- [x] Use `<label for="">` and `aria-required` on inputs
- [x] Provide `alt` text and `<figcaption>` for images
- [x] Ensure keyboard navigation and accessibility validation
- [x] Optimize responsiveness using Tailwind’s `grid`, `flex`, and `breakpoints`
- [x] Validate HTML via [W3C Validator](https://validator.w3.org/)
- [x] Audit accessibility with [WAVE](https://wave.webaim.org/) and Axe DevTools

---

## 🛠 Technologies Used

- **HTML5** (Semantic structure)
- **Tailwind CSS** (Utility-first styling)
- **CSS Grid & Flexbox** (Layout systems)
- **ARIA Roles & Accessibility Standards**
- **SEO Best Practices**

---

## 🌐 Getting Started

### Requirements
- Node.js installed
- Any modern text editor (e.g., VS Code)
- A browser to view your HTML files


🤝 Contributions
Have suggestions or improvements? Fork the repo and submit a pull request. Let’s collaborate to build more accessible and beautiful UIs!

📄 License
This project is open for learning and portfolio use. Please credit the original author if adapted or reused for public or commercial projects.
