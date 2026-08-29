# Mukesh Kumar Kachhot — Jewellery CAD Designer Portfolio

A simple, professional, single-page portfolio website for **Mukesh Kumar Kachhot**, a Jewellery CAD Designer with 22 years of experience. Built with plain HTML, CSS, and JavaScript in a modern black-and-gold jewellery-inspired theme, and fully responsive across mobile and desktop.

## Sections

- **Home** — Hero introduction with name, title, and call-to-action buttons
- **About Me** — Background, 22 years of experience, and key stats
- **Skills** — Rhino, Matrix, JewelCAD, and Diamond Jewellery CAD
- **Portfolio** — Showcase grid of sample design work
- **Services** — Custom CAD design, stone setting, rendering, production files, and more
- **Contact** — Contact details and a client-side contact form

## Project Structure

```
my-first-project/
├── index.html          # Main page containing all sections
├── css/
│   └── style.css       # Black & gold theme, layout, and responsive styles
├── js/
│   └── script.js       # Mobile nav, scroll-spy, back-to-top, contact form
└── README.md
```

## Getting Started

No build tools or dependencies are required.

1. Clone or download this repository.
2. Open `index.html` directly in a web browser, **or** serve it locally:

   ```bash
   # Using Python
   python3 -m http.server 8000

   # Then visit
   http://localhost:8000
   ```

## Customization

- **Contact details**: update the email, phone, and social links in the `#contact` section of `index.html`.
- **Portfolio images**: replace the placeholder tiles in `.portfolio-thumb` with real project photos (`<img>` tags) inside the `#portfolio` section.
- **Profile photo**: replace the `.portrait-placeholder` div in the `#about` section with an `<img>` tag pointing to a real photo.
- **Colors**: all theme colors are defined as CSS variables at the top of `css/style.css` under `:root` (`--gold`, `--black`, etc.) for easy re-theming.
- **Contact form**: the form currently validates and confirms client-side only. To actually receive messages, connect it to a backend endpoint or a form service (e.g. Formspree, Netlify Forms) by updating the `fetch`/submit logic in `js/script.js`.

## Tech Stack

- HTML5 (semantic sections, accessible markup)
- CSS3 (custom properties, Flexbox, CSS Grid, media queries)
- Vanilla JavaScript (no frameworks or dependencies)
- Google Fonts: [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) & [Poppins](https://fonts.google.com/specimen/Poppins)

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge). Responsive layout tested for mobile, tablet, and desktop breakpoints.
