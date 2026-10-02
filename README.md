# Testimonial Cards

A set of responsive-style testimonial cards for a website, built with plain **HTML** and **CSS**. This is a solution to the [Testimonial Cards](https://roadmap.sh/projects/testimonial-cards) project from [roadmap.sh](https://roadmap.sh), created to practice positioning and layout in CSS.

## Project Preview
![Project Preview](./src/images/project-preview.png)

## Overview

Testimonials are quotes from satisfied users that help build credibility and trust on a website. This project recreates a collection of testimonial card layouts, each one using a different layout technique:

| Section | What it shows |
| --- | --- |
| **First section** | Two cards side by side: a dark card with a speech-bubble pointer (inline SVG triangle) and an outlined card, each with an avatar, name and role |
| **Second section** | A large image next to a dark card with a 5-star rating, name, role and quote |
| **Third section** | A wide, centered outlined card with a quote and a row of avatars flanked by `>` and `<` navigation hints (the middle avatar is full size, the outer ones are smaller and faded) |

## Features

- Pure HTML and CSS, no frameworks or JavaScript
- Layouts built with Flexbox
- Inline SVGs for the speech-bubble pointer and star ratings
- Circular avatars using `border-radius`
- Dark and light card variants for visual contrast

## Concepts Practiced

- Flexbox: `display`, `flex-direction`, `justify-content`, `align-items`, `gap`
- Box model and `box-sizing: border-box`
- Sizing with `px`, `vh` and `rem`
- Rounded corners, borders and opacity
- Structuring a page into semantic sections
- Selectors: ID, class, child (`>`), `:first-of-type`, `:last-of-type`

## Project Structure

```
.
├── index.html
├── style.css
├── images/
│   ├── images.jpeg
│   ├── image2.png
│   └── image3.png
└── README.md
```

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/KunalGuhagarkar/Testimonial-Cards.git
   ```
2. Open the project folder:
   ```bash
   cd Testimonial-Cards
   ```
3. Open `index.html` in your browser (or use a tool like the VS Code *Live Server* extension).

## Acknowledgements

Project idea from [roadmap.sh](https://roadmap.sh/projects/testimonial-cards).

## Author

**Kunal Guhagarkar**
- GitHub: [@KunalGuhagarkar](https://github.com/KunalGuhagarkar)
