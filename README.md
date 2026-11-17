# Ayan Nasim — Personal Portfolio Website
### College Assignment: Demonstration of HTML5 & CSS3 Design Principles

---

## 1. Project Overview
This website is a multi-page personal portfolio developed for **Ayan Nasim**, a commerce student pursuing a Bachelor of Business Administration (BBA) at IIMB and preparing for the CA Intermediate examination under the Institute of Chartered Accountants of India (ICAI).

The project is designed to demonstrate advanced **HTML5 and CSS3 design principles**, creating a human-crafted editorial identity suited for an aspiring finance and accounting professional.

---

## 2. Technology Stack & Constraints
- **HTML5:** Semantic, accessible markup (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`, `<blockquote>`, `<cite>`).
- **CSS3:** Custom design system using CSS Variables (`:root`), Flexbox, CSS Grid, and Media Queries.
- **Strictly Vanilla:** 
  - **Zero JavaScript**
  - **Zero Frontend Frameworks** (No React, No Vue, etc.)
  - **Zero CSS Libraries** (No Bootstrap, No Tailwind CSS)
  - **Zero UI Libraries**
- **Local Portability:** Can be launched by double-clicking `index.html` directly in any web browser without requiring a web server or build pipeline.

---

## 3. Project Directory Structure
```
ayan-portfolio/
│
├── index.html            # Home page (Hero, Stats, Milestones Overview)
├── about.html            # About Me (Background, Core Motivations, Values)
├── education.html        # Academic Journey (Vertical Timeline, Schooling & BBA)
├── qualifications.html   # Professional Qualifications (CA Foundation & CA Intermediate)
├── skills.html           # Skills & Areas of Interest (4 Core Domains)
├── contact.html          # Let's Connect (Direct Contact Directory & Clickable Links)
│
├── style.css             # Unified master stylesheet across all pages
│
└── assets/
    └── ayan-profile.jpg  # Original resume portrait photograph
```

---

## 4. Design System & Principles Demonstrated

### A. Colour Palette
- **Primary Navy (`#172A3A`):** Applied to primary titles, sticky navigation bar, and footer to convey corporate authority and stability.
- **Warm Ivory (`#F7F4EF`):** Main page background offering a comfortable reading canvas with low optical strain.
- **Muted Sage (`#718477`):** Accent color used for academic markers, status ribbons, and subtle borders.
- **Terracotta (`#C47A5A`):** Active accent used for primary category kickers, button highlights, and interactive hover states.
- **Muted Gold (`#C6A15B`):** Applied to achievement accents, quotes, and institutional highlights.
- **Charcoal Text (`#292929`):** High-contrast body typography for optimal readability.
- **Secondary Text (`#777777`):** Metadata, sub-labels, and explanatory annotations.

### B. Typography Pairings
- **Headings & Large Titles:** `Playfair Display` (Serif) — Provides an editorial, classic corporate feel.
- **Body & Paragraphs:** `Lato` (Sans-Serif) — Highly legible, open proportion for academic reading.
- **Navigation, Buttons & UI Badges:** `DM Sans` (Sans-Serif) — Clean, modern, precise geometry.

### C. Core Design Principles
1. **Visual Hierarchy:** Distinct contrast between page kickers, h1/h2 headings, lead paragraphs, and metadata badges.
2. **Contrast & Accessibility:** WCAG-compliant contrast ratios between typography and backgrounds, supplemented with a skip-to-content accessibility link (`.skip-link`).
3. **Alignment & Grid System:** CSS Grid and Flexbox alignment ensuring mathematical rhythm and consistent container gutters (`1180px` max-width).
4. **Proximity:** Related concepts (e.g., ICAI subject areas, timeline dates and institutions) grouped into dedicated semantic clusters.
5. **Repetition & Consistency:** Identical header, sticky navigation, breadcrumb patterns, button designs, and footer across all six pages.
6. **Balance & White Space:** Ample section padding (60px–96px) avoiding cramped layouts and letting content breathe.
7. **Pure CSS Mobile Responsiveness:** Fully responsive across desktop, tablet, and mobile devices, including a zero-JavaScript pure CSS hamburger navigation toggle (`#nav-toggle`).

---

## 5. How to View the Website
1. Navigate into the `ayan-portfolio` folder (or the root workspace).
2. Double-click `index.html` to open it in your preferred web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari).
3. Use the navigation bar links to browse between all six pages.
4. On mobile devices or smaller browser windows, test the pure CSS mobile menu toggle and responsive timeline.
