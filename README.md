# Cursor Landing Page (Pure HTML & CSS)

This project is a **static landing page** inspired by the Cursor website, built using **pure HTML and CSS only**. It focuses on modern layout techniques, reusable design tokens, and semantic HTML structure—without any JavaScript or frameworks.

---

## ✨ Features

* Pure **HTML5 + CSS3** (no JavaScript)
* Semantic HTML structure (`header`, `nav`, `main`, `section`, `article`, `footer`)
* CSS Grid & Flexbox for layouts
* CSS Variables for consistent theming
* Custom font loading using `@font-face`
* layout (desktop-first)
* Card-based UI components
* Accessible markup foundations (alt text, landmarks)

---

## 🗂️ Project Structure

```
project-root/
│
├── index.html        # Main HTML file
├── style.css         # Global styles and layout
├── Images/           # Image assets used in the UI
│   └── *.webp
├── fonts/            # Custom font files
│   └── CursorGothic-Bold.woff2
└── README.md
```

---

## 🚀 How to Run the Project

1. Download or clone the repository
2. Make sure the folder structure remains the same
3. Open `index.html` in any modern web browser

No build tools, servers, or dependencies are required.

---

## 🎨 Design System

The project uses CSS variables to maintain a consistent design language:

* **Colors**: Defined in `:root` for background, text, and hover states
* **Typography**: Custom font via `@font-face` with fallback system fonts
* **Spacing**: Reusable padding and margin variables
* **Buttons**: Shared border, radius, hover behavior

Example:

```css
:root {
  --text-color: #edecec;
  --bg-color: #14120b;
  --btn-radius: 50rem;
}
```

---

## 🧱 Layout Overview

* **Header**: Fixed navigation bar with logo, links, and CTA buttons
* **Hero Section**: Main headline, call-to-action, and layered images
* **Logo Grid**: Trusted company logos using CSS Grid
* **Feature Sections**: Alternating text-image layout
* **Testimonials**: Card-based quotes using `<figure>` and `<blockquote>`
* **Changelog**: Semantic `<article>` elements with `<time>`
* **Footer**: Multi-column navigation and utility controls

---

## Screenshots

<p align="center">
  <img src="\Images\hero.png" width="300" height="300" />
  <img src="\Images\main.png" width="300" height="300" />
  <img src="Images\article.png" width="300" height="300" />
</p>

---

## ♿ Accessibility Considerations

* Semantic HTML landmarks improve screen reader navigation
* Images include descriptive `alt` text where meaningful
* Interactive elements are keyboard-friendly by default
* Color palette chosen for dark-theme readability

> Note: This project can be further improved with ARIA labels, focus styles, and responsive media queries.

---

## 📌 Limitations

* Desktop-first (mobile optimizations not fully implemented)
* No JavaScript functionality
* Static content only

---

## 📚 Learning Goals

This project was created to practice:

* Writing clean, structured HTML
* Building layouts with Grid and Flexbox
* Creating reusable CSS systems
* Understanding real-world landing page structure
* Improving readability and maintainability of code

---

## 📄 License

This project is for **learning and practice purposes only**.
All brand names, logos, and references belong to their respective owners.

