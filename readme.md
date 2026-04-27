# 🎸 Shattered Riffs | Rock Band Landing Page

A responsive **Rock Band Landing Page** built with **HTML5** and **CSS3**, focused on semantic structure, modern UI layout, responsive design, and clean front-end practices.

---

# 📖 Project Overview

**Shattered Riffs** is a fictional band website designed as a landing page showcasing:

- Hero promotional section
- Upcoming tour events
- About the Band section
- Multimedia gallery
- Responsive navigation with hamburger menu
- Contact footer and social links

This project emphasizes:

- Semantic HTML
- Flexbox and CSS Grid
- Responsive Design
- UI/UX layout principles
- Component-based CSS organization

---

# 🚀 Features

## Header / Navigation
- Semantic `<header>` structure
- Logo branding
- Responsive navigation menu
- Mobile hamburger menu
- Flexbox layout

---

## Hero Section
- Full-width hero banner
- Bold typography
- Call-to-action button
- Background imagery
- Overlay content design

---

## Upcoming Events Section
- Semantic HTML table using:

```html
<thead>
<tbody>
```

Includes:

- Tour schedule
- Venue listings
- Ticket CTA buttons
- Styled concert-inspired layout

---

## About The Band
- Two-column responsive layout
- Band image and biography
- Unordered values list

Uses:

- CSS Grid
- Flexbox alignment

---

## Multimedia Section
- Image gallery
- Grid layout
- Embedded video section

Built with:

```css
display: grid;
grid-template-columns: repeat(...);
```

---

## Footer
Includes:

- Social media links
- Quick navigation
- Contact information
- Booking call-to-action

Semantic structure:

```html
<footer>
```

---

# 🛠 Technologies Used

- HTML5
- CSS3
- Flexbox
- CSS Grid
- Media Queries
- JavaScript
- Font Awesome

---

# 📂 Project Structure

```bash
shattered-riffs/
│
├── index.html
├── README.md
│
├── public/
│   ├── img/
│   └── video/
│
└── src/
    ├── css/
    │   ├── header.css
    │   ├── styles.css
    │   ├── table.css
    │   ├── img-about.css
    │   ├── img_principal.css
    │   ├── hamburguesa.css
    │   └── footer.css
    │
    └── js/
        └── script.js
```

---

# 📱 Responsive Design

Designed for:

- Desktop
- Tablet
- Mobile

Implemented using:

```css
@media screen and (...)
```

Responsive features include:

- Hamburger navigation
- Layout reflow
- Scalable typography
- Responsive images
- Mobile-friendly tables

---

# 🎨 Layout Techniques Used

## Flexbox
Used for:

- Header navigation
- Footer layout
- Content alignment

Example:

```css
display:flex;
justify-content:space-between;
align-items:center;
```

---

## CSS Grid
Used for:

- About section
- Multimedia gallery

Example:

```css
display:grid;
grid-template-columns:1fr 1fr;
gap:50px;
```

---

# ▶ How to Run

Clone repository:

```bash
git clone https://github.com/yourusername/shattered-riffs.git
```

Open:

```bash
index.html
```

or run with **Live Server** in VS Code.

---

# ✅ Requirements Covered

✔ Semantic HTML  
✔ Header + Navigation  
✔ Hero Section  
✔ HTML Table  
✔ Unordered List  
✔ CSS Grid Layout  
✔ Flexbox  
✔ Footer  
✔ Responsive Design  
✔ Hamburger Menu  
✔ README Documentation

---

# 💡 Future Improvements

Possible upgrades:

- Tour filtering with JavaScript
- Music player integration
- Animations and scroll effects
- Dark/light theme switch
- Backend contact form

---

# 👨‍💻 Author

**Juan José Maldonado**  
Frontend Developer in Training

GitHub Portfolio Project

---

## 📸 Preview

Desktop Version  
Responsive Mobile Version  
Rock-inspired UI Design

---

*"Code loud. Rock louder."* 🎸
