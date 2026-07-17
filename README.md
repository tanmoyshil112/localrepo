# Amazon Clone

A front-end clone of the Amazon India homepage, built from scratch using HTML and CSS as a practice project to strengthen layout, styling, and responsive design fundamentals.

## Overview

This project recreates the core visual structure of the Amazon.in homepage, including the navigation bar, category panel, hero banner, promotional deal boxes, horizontally scrollable product carousels, and footer. It was built section by section, with an emphasis on matching real-world spacing, alignment, and visual hierarchy.

## Features

- **Responsive navigation bar** with logo, delivery location, search bar with category dropdown, sign-in, returns & orders, and cart sections
- **Category panel** with a horizontally listed menu of shopping categories
- **Hero section** with a full-width banner image and a smooth fade-to-background gradient overlay
- **Promotional deal boxes** — a four-box layout showcasing shopping deals, headphone offers, home appliances, and a sign-in/sponsored product card
- **Horizontally scrollable product rows** ("More items to consider", "Related to items you've viewed", "Best sellers in Home & Kitchen") with custom scrollbars and equally spaced product cards
- **Product cards** with images, titles, discount badges, limited-time deal tags, current price, and struck-through MRP
- **Full footer** with informational link columns, social links, language/region selectors, and a copyright section

## Tech Stack

- **HTML5** — semantic page structure
- **CSS3** — Flexbox, CSS Grid, positioning, pseudo-elements, and gradients
- **Font Awesome** — icons (via CDN)

## Project Structure

```text
project-folder/
├── index.html
├── style.css
├── amazon_logo.png
├── hero_image1.jpg
├── card1/          (Laptop product images)
├── hedphones/       (Headphone product images)
├── row/             (Best seller product images)
└── rendom/          (Footer assets, flag icon, etc.)
```

## Key CSS Concepts Used

| Concept | Where it's used |
|---|---|
| Flexbox | Navbar, category panel, deal boxes, product rows |
| CSS Grid | Image grids inside deal boxes |
| `position: relative` / `absolute` | Layering deal boxes over the hero section, sponsored label placement |
| `z-index` | Controlling stack order between the hero fade and the boxes above it |
| `::after` pseudo-element | Gradient fade effect at the bottom of the hero image |
| `overflow-x: auto` + `flex-shrink: 0` | Horizontally scrollable product carousels |
| `object-fit: contain` | Preserving image aspect ratio inside fixed-size containers |
| `-webkit-line-clamp` | Truncating long product titles to two lines |

## What This Project Helped Practice

- Building multi-section responsive layouts from a visual reference
- Debugging real alignment and overflow issues (image centering, stacking context, flex-shrink behavior)
- Creating reusable CSS class patterns that scale across multiple similar sections
- Working with negative margins and z-index to create overlapping layout effects
- Structuring a large HTML file into clean, well-commented sections

## Disclaimer

This project is built purely for educational and portfolio purposes to practice front-end development skills. It is **not affiliated with, endorsed by, or connected to Amazon.com, Inc.** in any way. All product images and brand names used are for demonstration purposes only.

## Author

Built as a self-driven front-end practice project. <br> By Tanmoy shil (CSE).
