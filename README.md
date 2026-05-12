# cohort3-task3

ASTRO Winter Armor — a responsive product detail page built with **HTML**, **Tailwind CSS** (CDN), and **Lucide icons**. Yeh ek e-commerce style single product page hai jisme hero showcase, color variants, size selector, aur feature highlights diye gaye hain.

## Preview

A pixel-clean product page for the *ASTRO Winter Armor* jacket featuring:

- Sticky-feel nav with logo, menu, and cart/search/user icons
- Hero section with product image, price, description, and material/return accordions
- Size picker (S / M / L / XL) with active state
- 4 color variants (Beige, Red, Black, White) with hover highlight
- Detailed feature grid: 3X Water-Repellent, 3D Padded Zones, Insulation, Utility Pockets
- Brand value strip: Premium Fabrics, Thermal Protection, Function, Limited Edition

## Tech Stack

| Layer        | Tool / Library                          |
| ------------ | --------------------------------------- |
| Markup       | HTML5                                   |
| Styling      | Tailwind CSS (via CDN) + custom `style.css` |
| Typography   | Google Fonts — Poppins                  |
| Icons        | [Lucide](https://lucide.dev/) (CDN)     |

## Project Structure

```
task3/
├── assets/                # Product images (jacket variants & detail shots)
├── index.html             # Main page markup
├── style.css              # Custom styles + Poppins utility classes
└── README.md
```

## Getting Started

Koi build step nahi hai — pure static files. Bas kisi bhi static server se serve karein.

### Option 1 — VS Code Live Server

1. Project open karein VS Code mein.
2. `index.html` pe right-click → **Open with Live Server**.

### Option 2 — Python (built-in)

```bash
cd task3
python -m http.server 5500
```

Phir browser mein kholo: `http://localhost:5500`

### Option 3 — Node (npx)

```bash
cd task3
npx serve .
```

## Notes

- Image paths relative (`./assets/...`) hain, isliye page directly `file://` se bhi load hota hai.
- Tailwind CDN script use kiya gaya hai for quick prototyping; production ke liye Tailwind CLI/build setup recommend hai.

## Author

**Akhlaque Ur Rahman** — [@Akhlaque-Ur-Rahman](https://github.com/Akhlaque-Ur-Rahman)
