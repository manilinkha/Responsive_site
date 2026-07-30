Responsive Website with Photos Page (Flexbox + Grid + Bootstrap)
Overview
This project extends my existing multi-page website by adding a Bootstrap navbar to every page and a brand-new Photos page that demonstrates both Flexbox and CSS Grid layouts with full responsiveness across mobile, tablet, and desktop.
Pages
Page
Description
index.html
Home page — intro, hobbies, and favorite foods
about.html
About Me page
feedback.html
Feedback form (name, email, rating, interests, country)
photos.html
New page — Flexbox Gallery and CSS Grid Gallery

Files
├── index.html

├── about.html

├── feedback.html

├── photos.html

├── style.css       (shared styles, navbar theme, gallery layouts)

├── feedback.css    (styles specific to the feedback form)

└── README.md
Features Implemented
1. Bootstrap Navbar
Added via Bootstrap 5 CDN on all four pages.
Built with navbar, navbar-expand-lg, and navbar-dark classes.
Collapses into a hamburger menu (navbar-toggler) on mobile screens.
Same menu items and look on every page: Home | About | Feedback | Photos.
Custom .site-navbar styling in style.css matches the site's existing dark background and orange accent color.
2. Photos Page (photos.html)
Main heading <h1>Photos</h1>.
Flexbox Gallery (.photos-flex) — 6 images laid out with display: flex; flex-wrap: wrap;.
Grid Gallery (.photos-grid) — 6 images laid out with display: grid;.
12 total images (6 per gallery).
3. Responsive Behavior (both galleries, via media queries)
Screen size
Images per row
≤ 768px (mobile)
1
769px – 1024px (tablet)
2
> 1024px (desktop)
4

4. General Responsiveness
meta name="viewport" added to all pages for proper mobile scaling.
Images use width: 100% and object-fit: cover so they resize smoothly without distortion.
overflow-x: hidden on html, body prevents horizontal scrolling at any screen size.
Navbar collapses cleanly into a hamburger menu below the lg breakpoint.
5. Bootstrap Classes Used
container, navbar, navbar-expand-lg, navbar-dark, navbar-toggler, navbar-collapse, navbar-nav, nav-item, nav-link, text-center, p-3, m-2.
How to View
Keep all files in the same folder (the HTML files reference style.css, feedback.css, and each other by relative path).
Open index.html in any browser.
Resize the browser window (or open dev tools' device toolbar) to test the responsive breakpoints on the Photos page and the navbar collapse.
Notes
Only one new page was created: photos.html, per assignment rules.
Existing page content (Home, About, Feedback) was preserved — only the navbar and Bootstrap/viewport setup were added.
Gallery images are placeholder photos from picsum.photos and can be swapped for personal images by replacing the src attributes in photos.html.
Author
Mani

