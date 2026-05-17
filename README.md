# TechGadget Price Matrix

## Project Overview

The **TechGadget Price Matrix** is a responsive product comparison webpage built using HTML5 and CSS3. The project demonstrates advanced CSS selectors, combinators, pseudo-classes, structural targeting, and responsive design techniques without relying heavily on utility classes.

This project focuses on efficient CSS styling using semantic HTML structure and relationship-based selectors.

---

## Features

- Responsive product comparison grid
- CSS combinators and pseudo-classes
- Mobile-first responsive layout
- Semantic HTML5 structure
- Hover interactions
- Structural list highlighting
- Accessibility-friendly layout
- Modern UI design

---

## Technologies Used

- HTML
- CSS

---

## CSS Concepts Demonstrated

### Selectors & Combinators

| Feature | Selector Used |
|---|---|
| First product highlight | `:first-of-type` |
| Footer links styling | Descendant combinator (`footer a`) |
| Direct price symbol styling | Child combinator (`.price-tag > span`) |
| Discount notice styling | Adjacent sibling combinator (`h2 + p`) |
| Button hover effect | `:hover` |
| Even feature rows | `:nth-child(even)` |
| Global box sizing | Universal selector (`*`) |

---

## CSS Units Used

| Unit | Purpose |
|---|---|
| `rem` | Main container sizing |
| `vh` | Hero section height |
| `%` | Grid column widths |
| `em` | Component spacing |

---

## Project Structure

```plaintext
techgadget-price-matrix/
│
├── index.html
└── README.md
```

---

## Responsive Design

The layout adapts for smaller screens using media queries.

### Desktop
- Two-column product layout

### Mobile
- Single-column stacked layout

---

## Accessibility Features

- Semantic HTML5 elements
- Proper heading hierarchy
- Keyboard-friendly buttons
- Readable typography
- Responsive scaling

---

## Browser Compatibility

Tested and compatible with:

- Google Chrome
- Mozilla Firefox
- Safari
- Microsoft Edge

---

## How to Run the Project

1. Download or clone the repository

```bash
git clone https://github.com/yourusername/techgadget-price-matrix.git
```

2. Open the project folder

```bash
cd techgadget-price-matrix
```

3. Open `index.html` in your browser

---

## Learning Objectives

This project helps practice:

- CSS combinators
- Structural pseudo-classes
- Responsive layouts
- CSS units
- Semantic HTML
- Modern UI styling

---

## Future Improvements

Possible enhancements:

- Dark mode toggle
- Product animations
- Interactive pricing cards
- JavaScript filtering
- CSS Grid alternative layout

---

## License

This project is for educational purposes only.