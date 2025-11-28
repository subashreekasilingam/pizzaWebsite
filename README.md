<!-- ...existing code... -->

# Pizza Pie —My Landing Page

Simple responsive landing page for a pizza shop with sections for Home, About, Menu, Services, and Contact.

## Demo / Preview

Open `index.html` in your browser to view the site.

## Features

- Responsive layout using CSS Grid
- Dark mode toggle and mobile menu (see `script.js` if present)
- Uses Boxicons for icons and ScrollReveal for reveal animations
- Sections: Home, About, Menu, Services, Contact

## Built with

- HTML (`index.html`)
- CSS (`styles.css`)
- Optional JavaScript (`script.js`)
- Boxicons (CDN), ScrollReveal (CDN)

## Getting Started

1. Clone the repo.
2. Open `index.html` in a browser to preview.

Optional local server:

- Python: `python -m http.server 8000`
- Node: `npx http-server`

## Project Structure

- `index.html` — markup and section anchors (#home, #about, #menu, #services, #contact)
- `styles.css` — styling and responsive rules
- `script.js` (optional) — mobile menu toggle and dark mode handling

## Tips

- Fix any broken image URLs and add descriptive `alt` attributes for accessibility.
- Add `script.js` to implement the mobile menu toggle and dark mode:
  - Toggle `.navbar.active` when `#menu-icon` is clicked
  - Toggle `body.active` for dark mode using `#darkmode`

## Contributing

- Open a PR with a clear summary and reference specific file edits.
- Keep consistent class names and avoid inline styles.

## License

Add a license (e.g., MIT) or keep as desired.

## Contact

For questions, contact: example@email.com

<!-- ...existing code... -->
