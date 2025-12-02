# Arsh Aggarwal — Portfolio

A simple, responsive personal portfolio website built with HTML, CSS and minimal JavaScript. This repo contains a clean one-page layout to showcase education, skills, certifications and contact details.

Demo
- Open `index.html` in your browser to preview locally.
- (Optional) Host with GitHub Pages for a live site.

Features
- Lightweight, accessible single-page layout
- Responsive header with mobile menu toggle
- Smooth reveal animations (ScrollReveal)
- Sections: Home, About, Skills, Education, Certifications, Contact
- Simple contact form that uses mailto (client-side)

Tech
- HTML5
- CSS3 (custom, Google Fonts)
- Vanilla JavaScript
- Boxicons icon set
- ScrollReveal for subtle entrance animations

Repository structure
- index.html — main page
- styles.css — styling
- script.js — interactions (menu, scroll handling, ScrollReveal)
- README.md — this file

Quick start (local)
1. Clone the repository:
   git clone https://github.com/arshaggarwal295-stack/portfolio.git
2. Open the project folder and preview:
   - Double-click `index.html`, or
   - Run a lightweight local server:
     - Python 3: python3 -m http.server 8000
     - Node (http-server): npx http-server -c-1
   - Then visit http://localhost:8000 in your browser.

Deploy to GitHub Pages
1. Push changes to the `main` branch.
2. On GitHub, go to Settings → Pages, choose branch `main` and folder `/ (root)`.
3. Save — your site will be available at https://<your-username>.github.io/<repo-name>/ after a few minutes.

Customizing this portfolio
- Update your name, bio, education, skills, certifications, and contact info directly in `index.html`.
- Replace the hero badge (AA) or add a photo in the Home section.
- For a working contact form, integrate a backend or a service like Formspree / Netlify Forms.
- Update colors, fonts and layout in `styles.css`.

Accessibility & performance notes
- The layout uses semantic sections and clear focusable elements.
- Consider adding aria-labels and keyboard support for more interactive elements.
- Optimize images (if added) and defer third-party scripts when possible.

Planned improvements (suggestions)
- Add a Projects/Work section with cards and links to live demos or GitHub repos
- Improve contact form with serverless submission
- Add automated tests or CI to validate HTML/CSS

Contributing
- Contributions are welcome. Open an issue or submit a PR with proposed changes.
- Keep changes small and provide screenshots or a short description when updating layout or styles.

License
- MIT License — see LICENSE (or add an appropriate license file)

Contact
- Email: arshaggarwal295@gmail.com
- LinkedIn: https://linkedin.com/in/arsh-aggarwal-426a20334

