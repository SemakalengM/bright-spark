# Bright Spark Electrical Services – Website

A five-page responsive website for Bright Spark Electrical Services, a small electrical contractor based in Polokwane. Built with HTML5, CSS3 and JavaScript as set out in the project proposal (Part 1).

## How to view the website

1. Unzip the project folder.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge or Safari).
3. No server or installation is needed.

An internet connection is only needed for the Google Fonts and the map on the Contact page. Without it, the site uses system fonts and everything else still works.

## Pages

| Page | File | Content |
|---|---|---|
| Home | `index.html` | Introduction, interactive distribution board linking to each service, services overview, reasons to choose the business, how a job works, calls to action |
| About Us | `about.html` | Story, mission, vision, values, history timeline |
| Services | `services.html` | Installations, repairs, house wiring, lighting and maintenance, with jump links, quote buttons and FAQs |
| Enquiry | `enquiry.html` | Service request / quotation form with full validation |
| Contact | `contact.html` | Contact details, business hours with live open/closed status, service areas, map, contact form |

## Features

**HTML5:** semantic elements (`header`, `nav`, `main`, `section`, `article`, `aside`, `footer`, `figure`), accessible forms with labels and fieldsets, `details`/`summary` FAQs, skip link.

**CSS3:** custom properties (variables) for colours and fonts, Flexbox and Grid layouts, three responsive breakpoints, sticky header, CSS counters for the numbered steps, hover and focus states, reduced-motion support.

**JavaScript (`js/script.js`):**
- Mobile navigation toggle (also closes with Escape)
- Enquiry and contact form validation: required fields, name, email and South African phone number patterns, date checks (no past dates, no Sundays), minimum description length, consent checkbox, error summary and focus on the first error
- Live character counters on message boxes
- Service pre-selected on the enquiry form from the link clicked on the Services page
- Open/closed status and today's hours highlighted on the Contact page
- Back-to-top button and automatic footer year

**JavaScript (`js/sparks.js`, home page only):** animated 3D electrical sparks behind the hero, drawn on a `<canvas>` with plain JavaScript (no libraries, works offline). Glowing particles float in 3D space and are projected with perspective, lightning arcs jump between them and throw off falling sparks. Moving the mouse tilts the scene, and clicking the hero sets off a spark burst. The animation pauses when scrolled out of view or the tab is hidden, and shows a still frame when the visitor has reduced motion turned on.

Forms are not connected to a server, so submissions are simulated with a success message.

## Folder structure

```
bright-spark/
├── index.html, about.html, services.html, enquiry.html, contact.html
├── css/style.css
├── js/script.js, js/sparks.js
├── images/        logo, favicon, service icons, about illustration (SVG)
├── docs/
│   ├── planning.md   sitemap, wireframes, folder structure, design decisions
│   └── testing.md    test plan, results and debugging log
└── README.md
```

## Placeholder content

Bright Spark Electrical Services is the case-study business for this project. The phone number (082 789 1600) and email address (semakalengmokgwatjana@gmail.co.za) are the business's real contact details. The street address and owner's name are still placeholders and should be replaced with real details before the site goes live.

## Project timeline completed

| Week | Activity | Where to find it |
|---|---|---|
| 1–2 | Proposals and organisation selected | Part 1 proposal |
| 3 | Research and content | Page content |
| 4 | Sitemap, wireframes, folder structure | `docs/planning.md` |
| 5 | HTML pages | `*.html` |
| 6 | CSS styling and responsive design | `css/style.css` |
| 7 | JavaScript functionality | `js/script.js` |
| 8–9 | Testing and debugging | `docs/testing.md` |
| 10 | Documentation and README | This file |

## References

MDN Web Docs, 2025. *Learn web development*. Mozilla. Available at: https://developer.mozilla.org/en-US/docs/Learn_web_development [Accessed 21 August 2026].

Nielsen, J., 2012. *Usability 101: Introduction to usability*. Nielsen Norman Group. Available at: https://www.nngroup.com/articles/usability-101-introduction-to-usability/ [Accessed 21 August 2026].

Pressman, R.S. and Maxim, B.R., 2020. *Software Engineering: A Practitioner's Approach*. 9th ed. New York: McGraw-Hill Education.

W3C, 2024. *Responsive Web Design*. World Wide Web Consortium. Available at: https://www.w3.org/standards/webdesign/htmlcss [Accessed 21 August 2026].
