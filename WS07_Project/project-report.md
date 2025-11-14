# Project Report — Nature Journal

## Project idea and purpose
Nature Journal is a small, educational website created as a student project to practice responsive web design, semantic HTML, and accessible navigation. The site demonstrates a home page with a hero, feature cards, and supporting pages (About, Contact).

## Tools and technologies used
- HTML5 and semantic elements (<header>, <main>, <section>, <footer>, <article>)
- CSS3 (Flexbox, Grid, media queries, custom properties)
- A tiny bit of vanilla JavaScript for the responsive menu toggle
- Images sourced from Pexels (free-to-use stock photos)

## Structure of the project
- `index.html` — homepage (hero, features, image)
- `about.html` — project description and purpose
- `contact.html` — demo contact form (static)
- `styles.css` — external stylesheet with responsive rules

## Validation
Validate HTML and CSS using the W3C validators:
- HTML: https://validator.w3.org/ — upload or paste the `index.html` contents or run the local file through the validator.
- CSS: https://jigsaw.w3.org/css-validator/ — paste or upload `styles.css`.

Notes: I kept the markup simple and semantic. If the validators report warnings/errors, open the specific file and fix them (common fixes: missing alt attributes, mismatched tags, or vendor-specific CSS issues). I recommend running the validators now and following the messages — they are usually straightforward to resolve.

## Challenges and how they were handled
- Responsive navigation: making a small, accessible menu without frameworks required a lightweight JS toggle. Kept the toggle minimal and used `aria-expanded` for accessibility.
- Images: ensuring images are responsive and have descriptive alt text; used `max-width:100%` and `height:auto` to preserve aspect ratios.

## Additional features implemented
- Semantic HTML across all pages
- Consistent navigation present on every page
- Responsive hero image and feature grid using CSS Grid and Flexbox

## Possible improvements (next steps)
- Add server-side form handling or a form service for `contact.html`.
- Add animations and transitions for improved polish.
- Improve accessibility further (skip link, keyboard trap tests, focus styles).
- Add unit or visual tests and automate HTML/CSS validation in a CI workflow.

---

Project completed. Files are located in `WS07_Project/` in the workspace. Please run the W3C validators and tell me if you'd like me to fix any validator-reported issues automatically.