# BrewCraft Café

A responsive multi-page static website for **BrewCraft Café**, an artisanal coffee house and bakery. Built with semantic HTML5, modern CSS3 (Grid, Flexbox, and 3D CSS flip animations), and lightweight vanilla JavaScript.

## Features

- **Home Page (`index.html`)** — Hero banner with call-to-action and interactive 3D flip cards showcasing signature favorites (front: dish photo, badge, summary, price; back: roast, ingredients, and nutrition details).
- **Full Menu (`menu.html`)** — 16 café dishes and beverages organized into four categories, each with photography stored locally in `images/`:
  - *Hot Coffees & Specialty Teas* (Classic Espresso, Velvet Cappuccino, Caramel Macchiato, Ceremonial Matcha Latte)
  - *Cold Brews & Iced Beverages* (Classic Cold Brew, Iced Vanilla Latte, Hazelnut Mocha Frappe, Classic Lemon Iced Tea)
  - *Savory Bites & Sandwiches* (Herb & Cheese Panini, Avocado Sourdough Toast, Herb Chicken Bagel, Spinach & Feta Quiche)
  - *Bakery & Desserts* (Almond Butter Croissant, Blueberry Oat Muffin, Classic Tiramisu, Chocolate Fudge Brownie)
- **About Us (`about.html`)** — Café story, key highlights, and a structured weekly opening hours table.
- **Contact & Reservations (`contact.html`)** — Location details and an interactive table reservation form with instant client-side confirmation.
- **Responsive Design (`style.css`)** — Warm espresso-and-caramel theme that adapts across desktop, tablet, and mobile viewports with zero external dependencies.

## Project Structure

```text
BrewCraft Café/
├── index.html          # Home page with hero & 3D flip cards
├── menu.html           # Categorized 16-item menu with dish photos
├── about.html          # Story, highlights & opening hours table
├── contact.html        # Address details & table reservation form
├── style.css           # Global styles, responsive grids & 3D card effects
├── images/             # Local dish photographs (.jpg)
└── README.md           # Project documentation
```

## Getting Started

No build step or server is required:

1. Clone or download this repository.
2. Open `index.html` directly in any modern web browser.

## Tech Stack

- **HTML5** — Semantic multi-page layout
- **CSS3** — Custom properties, Flexbox, CSS Grid, and 3D `preserve-3d` card flip transitions
- **JavaScript** — Client-side reservation form handling in `contact.html`

## Image Credits

Dish photographs in `images/` are sourced from [Wikimedia Commons](https://commons.wikimedia.org/) under open licenses.

