# Flower Shop

This is a responsive web page for a flower shop, created as Assignment 2.

## Project Details

Below is a detailed breakdown of the technologies and components used in this project, based on a complete analysis of the repository code:

### 1. Core Technologies
* **HTML5:** Used to build the core structure of the website. Semantic tags such as `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>` are used to keep the code organized and accessible.
* **CSS3:** External CSS (`styles.css`) is used for all styling and design elements across the website.

### 2. Layout Systems
* **Flexbox:** Heavily used for the navigation bar, internal alignment of cards, and structuring the footer using `display: flex`. It helps in aligning and spacing elements cleanly.
* **CSS Grid:** Used to arrange the product cards and latest deals cards into a grid layout using `display: grid`. For example, the product section uses `grid-template-columns: repeat(4, 1fr);` to create a 4-column layout.

### 3. Typography and Fonts
Two fonts have been imported from **Google Fonts**:
* **Noto Serif:** Applied to headings and titles (e.g., `heading-primary`, `product-title`, `store-title`) to give a premium, elegant look.
* **Inter:** Used for paragraphs, descriptions, and buttons to ensure high readability.

### 4. Icons
* **FontAwesome:** A FontAwesome CDN is used to render the shopping cart icon (`<i class="fa-solid fa-cart-arrow-down"></i>`) in the navigation bar.
* Custom image icons are used for the social media links in the footer (e.g., Facebook, Twitter, LinkedIn, YouTube).

### 5. Responsive Design
* **Media Queries:** Used within CSS (`@media screen and (max-width: 576px)`) to adapt the layout for mobile and smaller devices.
* On smaller screens, navigation links are hidden, the layout direction is changed to a column-based approach, and the number of grid columns is reduced to ensure the site displays correctly across all device sizes.

### 6. Other Features
* **Images and Assets:** The project incorporates images from a local folder (`assets/`) in various sections. Some assets are also used as background images (e.g., in the form section).
* **Forms:** A simple HTML form (`<form>`) is included for users to subscribe to the newsletter.

## Links

* [GitHub Repository](https://github.com/Mahfiz720/Assignment-2)
* [GitHub Live Demo](https://mahfiz720.github.io/Assignment-2/)
* [Vercel Live Demo](https://assignment-2-rho-self.vercel.app/)

## File Tree

```
.
├── assets
│   ├── deal-ana.png
│   ├── deal-bloom.png
│   ├── deal-zabo.png
│   ├── flower-store.png
│   ├── hero-flower.png
│   ├── icon-facebook.png
│   ├── icon-linkedin.png
│   ├── icon-twitter.png
│   ├── icon-youtube.png
│   ├── logo.png
│   ├── news-letter-bg.png
│   ├── sample-flower-image.png
│   └── trusted-badge.png
├── flower-market.fig
├── index.html
├── readme.md
└── styles.css
```
