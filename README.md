# Ora's Bakery — WEDE5020 Portfolio of Evidence

## Student and module information
- **Student:** Khaya Molekoa Danzel
- **Student number:** ST10519050
- **Module:** Web Development 
- **Module code:** WEDE5020
- **Lecturer:** Mrs S Mahamo
- **Organisation:** Ora's Bakery 


## Project overview
Ora's Bakery is a small-business website concept designed to present the bakery, explain its story, display products, provide indicative menu prices, support customer enquiries and make contact information easy to find. The site contains six linked pages: Home, About, Menu, Gallery, Enquiries and Contact.

## Target audience
Local residents, families, students, office workers, coffee lovers, cake buyers and people planning birthdays or other events.

## Goals and measurable indicators
1. Present the bakery and its product range clearly.visitors can reach the menu and gallery from every page.
2. Encourage product and custom-order enquiries. enquiry form completion rate and number of valid enquiries (to be measured once a real form service is connected).
3. Make contact information easy to locate. contact page visits and click-to-call/email interactions.
4. Provide a usable experience on desktop, tablet and mobile. no horizontal overflow at the tested viewport widths; all navigation and forms remain usable.
5. Improve discoverability. page titles, descriptions, semantic headings, descriptive image alt text and crawl files are present; actual ranking requires publication and monitoring.

## Features
- Semantic HTML5 structure and consistent navigation across six pages.
- External CSS stylesheet with desktop, tablet and mobile breakpoints.
- Responsive image layout and descriptive alt text.
- Searchable and filterable menu.
- Gallery lightbox using the native HTML dialog element.
- Enquiry form with client-side validation and an indicative price calculation.
- Contact form with validation and a `mailto:` hand-off to the visitor's email application.
- Page-specific titles, descriptions and keywords.
- `sitemap.xml` starter files.

## Technical requirements
- HTML5, CSS3 and vanilla JavaScript.
- Visual Studio Code or another code editor.
- Current desktop/mobile browser.
- Local preview through VS Code Live Server or a static web server.
- Static hosting such as GitHub Pages or Netlify.
- No build tools or package installation required.

## File and folder structure
```text
website/
├── index.html
├── about.html
├── menu.html
├── gallery.html
├── enquiry.html
├── contact.html
├── sitemap.xml
├── Sitemap.txt
├── README.md
├── css/
│   └── style.css
├── js/
│   └── main.js
└── images/
    ├── bread.jpg
    ├── cake.jpg
    ├── cake copy.jpg
    ├── coffee.jpg
    ├── cookies.jpg
    ├── cupcakes.jpg
    └── Pastries.jpg
```

## Sitemap
Home → About | Menu | Gallery | Enquiries | Contact. See `Sitemap.txt` and `sitemap.xml`.

## Timeline and milestones
| Week | Milestone | Evidence |
|---|---|---|
| 1 | Select organisation, research audience and goals | Two proposals and selected scenario |
| 2 | Plan pages, content and wireframes | Sitemap and wireframes |
| 3 | Build semantic HTML pages and navigation | Six HTML pages |
| 4 | Apply desktop CSS and visual design | `css/style.css` |
| 5 | Add tablet/mobile breakpoints and test | Responsive CSS and test checklist |
| 6 | Add JavaScript interactions and form validation | `js/main.js` |
| 7 | Add SEO metadata, crawl files and documentation | Page metadata, `sitemap.xml`, README |
| 8 | Final testing, repository commits and deployment | Test evidence, Git history and live URL |

These are planning estimates, not supplier quotations. They exclude paid labour, business email, online ordering, payment processing and any paid form service.


## Form and deployment limitations
The enquiry form calculates an indicative estimate in the browser only; it does not store or send an order. The contact form uses `mailto:` to prepare an email in the visitor's configured email application. **It does not send email directly or guarantee delivery.** To meet a strict server-side email/AJAX requirement, connect a form backend (for example, a configured Netlify Forms endpoint or a server/API) and test it after deployment. Do not claim live email delivery until that service is configured and tested.

The address and contact details in the supplied files are inconsistent in places. This build uses the details recorded in the supplied README/homepage as the working project scenario. Verify all business details before public deployment. The second map link is a Pretoria-area search, not a verified second shop address.

## Part 1, Part 2 and Part 3 record
- **Part 1:** organisation proposals, audience/goals, sitemap, page structure, original project content and initial folder organisation.
- **Part 2:** shared external stylesheet, typography, grid/flex layouts, hover/focus states, responsive breakpoints and mobile navigation.
- **Part 3:** JavaScript menu search/filter, gallery lightbox, form validation, enquiry estimate, contact email hand-off and SEO/crawl files.

## Changelog
### Version 3.0 — 2 November 2026
- Expanded the supplied five-page project to six pages by adding a dedicated product enquiry page.
- Reorganised CSS and JavaScript into `css/` and `js/` folders.
- Updated the complete website colour palette to the purple Part 2 theme: purple `#7b2d8b`, deep purple `#4a1a54`, soft purple `#b77ac2`, lilac `#f3d9f7`, cream `#fffaf2` and orange accent `#e08a00`.
- Applied the Part 2 colours consistently to headings, navigation, buttons, cards, forms, gallery borders, tables, callouts and footer while retaining the improved responsive layout and accessible focus states.
- Added responsive layouts for tablet and mobile viewports.
- Added menu text search and category filters.
- Added an accessible gallery lightbox.
- Added client-side validation and indicative pricing for product enquiries.
- Added contact form validation and a `mailto:` message hand-off.
- Added page-specific SEO metadata, descriptive image alt text, `robots.txt` and `sitemap.xml`.
- Updated sitemap, testing notes, limitations and references.

### Version 2.0 — supplied Part 2 baseline
- Supplied project included five HTML pages, an external stylesheet, product images, a sitemap and a wireframe document.
- The supplied gallery referred to image files that were not included in the archive; the updated gallery now uses supplied image assets.
- The supplied contact details differed between pages; this build uses the README/homepage values as the working scenario and flags them for verification.

### Version 1.0 — supplied Part 1 baseline
- Initial project structure, five HTML pages, navigation, menu, gallery, contact page and README.

## References (Harvard-style starting list)
The following documentation informed implementation. Add any additional sources actually consulted, and check the institution's current IIE Harvard guide for exact punctuation and access-date requirements.

- Mozilla Developer Network (MDN) (n.d.) *HTML: HyperText Markup Language*. Available at: https://developer.mozilla.org/en-US/docs/Web/HTML (Accessed: 2 November 2026).
- Mozilla Developer Network (MDN) (n.d.) *CSS: Cascading Style Sheets*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS (Accessed: 2 November 2026).
- Mozilla Developer Network (MDN) (n.d.) *JavaScript*. Available at: https://developer.mozilla.org/en-US/docs/Web/JavaScript (Accessed: 2 November 2026).
- Google (n.d.) *Search Engine Optimisation (SEO) Starter Guide*. Available at: https://developers.google.com/search/docs/fundamentals/seo-starter-guide (Accessed: 2 November 2026)
- Unsplash (n.d.) *Unsplash*. Available at: https://unsplash.com/ (Accessed: 2 November 2026). 
W3Schools HTML Tutorial.
https://www.w3schools.com/html/

### Version 3.1 — 2 November 2026
- Rewrote the shared stylesheet with clear section headings and beginner-friendly CSS formatting.
- Changed the website to a purple bakery palette: cream, purple, lilac and orange accent.
- Kept the existing page layouts and JavaScript features while improving the styling for readability and easier student editing.
