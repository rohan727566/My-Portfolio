# Rohan Kumar — Portfolio

A single-page portfolio site built around a "systems dashboard" concept — a dark, data-driven layout with a fixed navigation rail, terminal-style panels, and a real skill-inventory chart, rather than a generic card grid.

**Live demo:** https://rohan727566.github.io/My-Portfolio/

## About this portfolio

The site is a single HTML file with no build step and no frameworks — open it and it runs. It's organized as a dashboard: a persistent left-hand nav rail, and a series of bordered "panels" for each section, styled like windows or log entries rather than uniform rounded cards.

### Sections

- **Overview** — headline, short bio, and a metrics strip (DSA problems solved, projects shipped, certifications, graduation year).
- **Experience** — AI Corporate Training role at Acmegrade.
- **Projects** — CIFAR-10 image classification, a spam/ham email classifier, and real-time object detection with YOLOv8, each shown as a spec-sheet panel (stack, type, period, notes).
- **Stack** — technical skills grouped by category, with an inline bar chart built from the actual count of skills per category (languages, core CS, libraries, tools).
- **Certifications** — a log-style list of certifications with issuer and year.
- **Contact** — direct email, phone, GitHub, and LinkedIn.

### Design

- **Typography:** Space Grotesk for headings, Inter for body copy, JetBrains Mono for data labels, stats, and panel chrome.
- **Palette:** near-black graphite background (`#0a0e14`), off-white text, a teal accent (`#4fd8c0`) for data and status, amber (`#e8a855`) as a secondary highlight.
- **Layout:** fixed nav rail on desktop, collapsing to a top bar on mobile; hairline borders instead of drop shadows; comment-style section labels (`// experience`) instead of tracked-out eyebrow text.

### Built with

- HTML5 + hand-written CSS (no Tailwind/CSS framework)
- Vanilla JavaScript (footer year, and rendering the skill-inventory chart from a small data array)
- Google Fonts: Space Grotesk, Inter, JetBrains Mono

## Running locally

No build step needed — clone the repo and open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Deployed via GitHub Pages from this repository at:
https://rohan727566.github.io/My-Portfolio/

## Contact

- Email: 2k22.csai.2212823@gmail.com
- LinkedIn: [linkedin.com/in/rohan-kumar-807980207](https://www.linkedin.com/in/rohan-kumar-807980207)
- GitHub: [github.com/rohan727566](https://github.com/rohan727566)
