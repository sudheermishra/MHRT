# MHRT: Mental Health Real Talk (Home Page)

A responsive home page for **MHRT**, a social media platform built around real connection, mental health and everyday wellbeing. The page was built from a provided design (JPG) as part of an internship task.

**Live Demo:** https://mhrt-kohl.vercel.app/
**Repository:** https://github.com/sudheermishra/MHRT

---

## Features

- Pixel-focused recreation of the provided design
- Fully responsive: desktop, tablet and mobile
- Sticky navbar with dropdown-style links and a mobile hamburger menu
- Hero section with circular highlight and dotted rings
- "What Makes MHRT Different" feature cards
- "Core Elements of a Better Life" category cards with image badges
- App section (Coming Soon) with store badges
- Support banner with call to action
- Dark footer with link columns, social icons and copyright
- Smooth hover and transition effects

## Tech Stack

- HTML5
- CSS3 (custom properties, Flexbox, Grid, media queries)
- Vanilla JavaScript (mobile menu toggle)
- Fonts: Plus Jakarta Sans, Pinyon Script (Google Fonts)
- Deployed on Vercel

## Project Structure

```
MHRT/
├── index.html
├── style.css
├── script.js
├── assets/
│   └── images/
│       ├── logo.svg
│       ├── logo-white.svg
│       ├── hero_woman.png
│       ├── app_mockup.png
│       └── ...
└── README.md
```

> File names may differ slightly. Check the repository for the exact structure.

## Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/sudheermishra/MHRT.git
   cd MHRT
   ```
2. Open `index.html` in your browser, or use a local server such as the VS Code **Live Server** extension.

No build step or dependencies are required.

## Responsive Breakpoints

| Breakpoint | Target |
|---|---|
| `max-width: 1080px` | Small desktops and landscape tablets |
| `max-width: 960px` | Tablets (hamburger menu appears) |
| `max-width: 767px` | Mobile (single-column layout) |
| `max-width: 420px` | Small phones |

## Customization

- **Colors, fonts and spacing:** edit the CSS variables in the `:root` block at the top of `style.css`.
- **Images and logo:** replace the files inside `assets/images/` and keep the same file names, so no code changes are needed.
- **Text content:** edit directly in `index.html`.

## Notes

- The original image assets and logo were not provided, so **placeholder images and a recreated logo** are used. They can be swapped with the final brand assets at any time.
- The App Store and Google Play badges are placeholders until the MHRT app is released.

## Author

**[Your Name]**
- GitHub: https://github.com/sudheermishra
- LinkedIn: [Your LinkedIn URL]
- Email: [Your Email]

## License

This project was created for learning and internship evaluation purposes. All brand names, designs and content belong to their respective owners.
