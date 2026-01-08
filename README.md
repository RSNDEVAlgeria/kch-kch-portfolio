# Nassim Kechtouli Portfolio

A modern, glassmorphism-style portfolio website designed for a graphic designer specializing in Adobe Illustrator.

## Features
- **Design**: Glassmorphism UI with light blue aesthetics.
- **Languages**: Full support for English, French, and Arabic (RTL).
- **Responsive**: Mobile-friendly with a hamburger menu.
- **Animations**: Smooth scroll reveal effects.

## How to Edit

### Changing Text
All text content is stored in `js/translations.js`. Open this file to edit the text for English (`en`), French (`fr`), and Arabic (`ar`).

### changing Images
- **Project Images**: Currently using placeholders. To change them, look for `.project-card` in `css/style.css` or add inline styles in `index.html`.
- **CV**: Place your CV PDF in the root folder and update the link in `index.html`:
  ```html
  <a href="your-cv-file.pdf" ... >Download CV</a>
  ```

### Contact Form
The contact form is currently frontend-only. To make it work, you can use a service like [Formspree](https://formspree.io/).
1. Register on Formspree.
2. Update the `<form>` tag in `index.html`:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="glass-card contact-form">
   ```

## Files
- `index.html`: Main page.
- `css/style.css`: Stylesheet.
- `js/main.js`: Logic for animations and menu.
- `js/translations.js`: Text content.
