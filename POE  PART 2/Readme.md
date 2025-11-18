# SUNRISE ARTISAN BAKERY Website

Welcome to the Sunrise Artisan Bakery website repository! This project showcases a fully responsive, multi-page website for a fictional bakery, built with HTML and CSS

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Changelog](#changelog)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

This website presents Sunrise Artisan Bakery’s products, recipes, story, and contact information. It is designed to work flawlessly on desktops, tablets, and mobile devices using modern CSS and responsive design techniques.

---

## Features

- **Consistent External CSS:** All pages link to a single `style.css` for unified styling.
- **Responsive Design:** Adapts to desktop, tablet, and mobile using relative units and media queries.
- **Modern Layouts:** Uses CSS Grid and Flexbox for structured, visually appealing layouts.
- **Interactive Cart:** Product page features a JavaScript-powered cart modal.
- **Accessibility:** Semantic HTML and descriptive `alt` attributes for images.
- **Performance:** Responsive images and minimal, efficient code.
- **Easy Navigation:** Consistent navigation bar across all pages.
- **Changelog:** All feedback and corrections are tracked below.

---

## Usage

- Browse the various pages (`home.html`, `products.html`, `recipes.html`, `aboutus.html`, `contactus.html`).
- On the Products page, add items to your cart and view the cart modal.
- The website automatically adjusts for different screen sizes for optimal user experience.

---

## Project Structure

```
/
├── home.html
├── products.html
├── recipes.html
├── aboutus.html
├── contactus.html
├── style.css
├── cart.js
├── sunrise_bakery_logo_small.png
├── /images (product & recipe images)
├── /screenshots (responsive design evidence)
└── README.md
```

---

## Technologies Used

- **HTML**
- **CSS**
---

## Changelog

### Part 2: CSS Styling & Responsive Design

- Linked all HTML pages to a single external stylesheet (`style.css`).
- Removed page-specific CSS file links.
- Added a modern CSS reset and established a base theme (font family, colors, margins, paddings).
- Implemented typography and layout styles using Flexbox and Grid.
- Applied visual enhancements using colors, backgrounds, borders, box-shadows, and interactive pseudo-classes.
- Used relative units (`em`, `rem`, `%`) for responsive sizing.
- Added media queries for desktop, tablet, and mobile breakpoints.
- Ensured responsive images and layouts.
- Used browser developer tools for cross-device testing.
- Provided screenshot evidence of the site on different devices in the `/screenshots/` folder.
- Updated semantic HTML and improved accessibility (descriptive `alt` on images, ARIA labels where appropriate).
- Fixed navigation and header consistency across all pages.
- Recorded all feedback and corrections in this changelog section.

---

## Screenshots

Screenshots of the website on desktop, tablet, and mobile are provided in the `/screenshots/` directory.

---

## License

This project is for educational purposes.

## PART 3
# Sunrise Artisan Bakery Website

## About
A full-featured demonstration site for a Cape Town bakery, including dynamic content, advanced JavaScript interactions, full SEO, forms with validation, and social engagement.

## Changelog

### 2025-11-18
- Implemented SEO (descriptions, keywords, meta og, sitemap, robots.txt, internal semantic links, unique titles)
- Added interactive tabs (About Us page)
- Added gallery with custom image lightbox (Products)
- Dynamic JS content loading/filter (products, recipes)
- Forms for Contact (general message) and Enquiry (service/volunteer/sponsor), both with client-side validation and dynamic post-validation feedback; AJAX-style feedback via JS
- Interactive modal popup for newsletter signup (Home)
- Integrated map view for contact (OpenStreetMap iframe)
- CSS transitions and animations on hero, buttons, etc. Mobile-friendly
- All images use descriptive `alt` attributes and responsive styling
- All feedback from Part 2 implemented

### [Earlier Logs...]
- Site structure setup, CSS modernization
- Navigation and page content
- Product and recipe data scaffold

## References

- [MDN HTML, JS, CSS documentation](https://developer.mozilla.org/)
- [OpenStreetMap](https://www.openstreetmap.org/)
- [Lightbox logic](https://www.w3schools.com/howto/howto_js_lightbox.asp) (adapted, no third-party dependency)
- [ARIA Practices Authoring Guide](https://www.w3.org/WAI/ARIA/apg/)
- Responsive design learned from [CSS-Tricks](https://css-tricks.com/)
