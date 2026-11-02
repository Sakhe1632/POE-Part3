Part1
Artisan's Hearth Bakery Website

Project Overview
This is a static website project for Artisan's Hearth Bakery, a fictional small business bakery based in Pretoria, South Africa. The website is built using HTML5, CSS3, and JavaScript, designed to establish an online presence for the bakery by showcasing products, telling the brand story, and facilitating customer enquiries.

The project consists of five interconnected web pages with a consistent navigation system, responsive design, and user-friendly contact forms. All code is standards-compliant and well-documented.

Student Information

Student Name: Sakhe September
Student Number: ST10485499 
Subject: Web Development 
Subject Code: WEDE5020 
Date: 18 September 2026 

Project Title
Artisan's Hearth Bakery Website

Project Overview

Organization: Artisan's Hearth Bakery – a family-owned bakery specializing in artisan breads, pastries, and celebration cakes using traditional methods and locally sourced ingredients.

Project Goals:
1. Showcase the bakery's products and services
2. Provide an easy way for wholesale and custom order enquiries
3. Build brand identity and share the bakery's story
4. Increase foot traffic to the physical store
5. Establish a professional online presence

Website Pages:
- Homepage (index.html):Welcome message, features, product preview
- About Us (about.html):History, mission, vision, team, values
- Products (products.html): Catalogue with descriptions and pricing
- Enquiry (enquiry.html): Detailed contact form for various enquiry types
- Contact (contact.html): Location, map, hours, contact form

Website Goals and Objectives

Primary Objectives
1. Display Product Catalogue: Create an attractive online catalogue of baked goods
2. Generate Enquiries: Facilitate wholesale and custom order enquiries
3. Increase Foot Traffic: Drive customers to the physical store
4. Build Brand Identity: Tell the bakery's story and values
5. Establish Online Presence: Professional digital storefront

Key Performance Indicators (KPIs)
- Number of enquiry form submissions
- Website traffic and page views
- Time spent on product pages
- Engagement with contact information

Key Features and Functionality

Core Features
- Responsive Navigation: Consistent, intuitive menu across all pages
- Contact Forms: Multiple forms for enquiries and messages
- Visual Product Display: Image-rich catalogue with clear descriptions
- Google Maps Integration: Interactive map for location finding
- Social Media Links: Connections to Facebook, Instagram, Twitter, WhatsApp

Technical Features
- Semantic HTML5: Proper use of header, nav, main, section, footer
- Cross-browser Compatibility: Tested on Chrome, Firefox, Edge, Safari
- External CSS Styling: All styling is handled in a separate `css/style.css` file.
- Responsive Design: Media queries ensure the site works on desktop, tablet, and mobile devices.


Changelog (Part 2 Updates)

[18 September 2026] - Part 2 Implementation
- Created External Stylesheet: Added `css/style.css` and linked it to all HTML pages.
- Base Styles: Implemented a CSS reset and set global font families (Georgia, Segoe UI), colors (Browns/Whites), and line heights.
- Layout Structure: Used CSS Flexbox for the header navigation and CSS Grid for product cards, team members, and features.
- Visual Styling: Added `box-shadow`, `border-radius`, and `:hover` states to buttons, links, and product cards.
- Responsive Design: 
    - Added `@media` queries for tablet (max-width: 768px) and mobile (max-width: 480px).
    - Converted multi-column layouts to single-column on smaller screens.
    - Used relative units (`rem`, `%`) for font sizes and widths to ensure scalability.
- Typography: Applied a harmonious typographic scale to headings and paragraphs.

Feedback from Part 1
1. HTML Syntax Errors Resolved: 
   - Fixed the broken image tag in `about.html` (it previously contained invalid syntax `<src=...>`). This has been corrected to a proper `<img>` tag with a valid `alt` attribute.
   - Removed duplicate/conflicting files (e.g., `home.html` and `index.html`). The website now uses a single, consistent `index.html` as the main entry point.

2. Semantic HTML Improvements:
   - I ensured all pages correctly use semantic tags (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`) to improve accessibility and SEO.
   - I also added missing `alt` text to images on the Home page to improve screen reader compatibility.

3. Navigation Consistency:
   - I corrected the navigation links across all 5 pages to ensure they point to the correct filenames (e.g., `contact.html` instead of `Contact.html` to avoid case-sensitivity issues on GitHub Pages).
   - I also ensured the navigation menu is identical on every page for a seamless user experience.

4. Form Validation:
   - Added the `required` attribute to essential fields in the Enquiry and Contact forms to prevent empty submissions.
   - Verified that all form `action` and `method` attributes are correctly set up.

5. Code Cleanup:
   - Removed unused placeholder text and fixed the page title in `index.html` (which previously said `[Page Title]`).



Screenshots



Desktop View

<img width="1896" height="951" alt="Destop View" src="https://github.com/user-attachments/assets/bc5a04c7-af02-416c-ac26-1b65376ea849" />




Tablet View

<img width="590" height="777" alt="Tablet View" src="https://github.com/user-attachments/assets/08855f7c-107b-4b2f-bf6f-9eda65baf340" />



Mobile View

<img width="496" height="563" alt="Mobile View" src="https://github.com/user-attachments/assets/fb20a70c-8806-4264-9c33-58d1623295f8" />
Changelog
The Part 2 entries I written from problems found in the Part 2.
Artisan's Hearth Bakery
WEDE5020 Portfolio of Evidence, Part 3: Enhancing Functionality and SEO Student number: ST10485499 | Updated: 1 November 2026
A multi-page website for a fictional artisan bakery in Pretoria. Part 3 I added JavaScript interactivity, form validation, SEO, security and public deployment.

Part 2 feedback corrections

Problem found	Change made
1	Clashing blue page background (
#0a1fdd), pink navigation links and a muddy content panel	New palette: enamel blue, crust brown, flour white, with checked contrast
2	home.html and index.html both existed; index.html held placeholder text	One complete index.html; home.html removed
3	Links pointed to enquiry.html and contact.html but files were Enquiry.html and Contact.html	All file names and links lowercase
4	Duplicate stylesheets, one inside a nested CSS/Style.css/ folder, plus a minified <style> block on the products page	One css/style.css
5	Placeholder and hotlinked images (via.placeholder.com, picsum.photos, missing files, Unsplash)	Local, optimised images only
6	Invalid HTML: a malformed <src=...> tag, empty style= attributes, missing lang	Valid markup; lang="en-ZA" on every page
7	Founder named Elias in the story but Lethabo in the team; "Thabo" used in Sakhe's bio	Names made consistent
8	Placeholder titles, no meta descriptions or keywords	Unique title, description and keywords per page
9	Meaningless image names (images3.jpg) and an unrelated packaged-roll photo	Descriptive names and alt text; unrelated photo not used
10	Blank icon headings in the footer and contact page; missing copyright symbol	Clear text labels and consistent footer
11	Forms with action="#" and no validation or feedback	Full validation, error messages, AJAX and responses
12	Generic Google Maps embed	Interactive Leaflet map pinned to the bakery
13	One breakpoint; menu stacked into a tall column on phones	Three breakpoints and a collapsible menu



Readme short · MD
Artisan's Hearth Bakery
WEDE5020 Portfolio of Evidence, Part 3: Enhancing Functionality and SEO Student number: ST10485499 | Updated: 2 November 2026

A multi-page website for a fictional artisan bakery in Pretoria. Part 3 adds JavaScript interactivity, form validation, SEO, security and public deployment.

Live site: [REPLACE: your live link]
Repository: [REPLACE: your GitHub link]
Hosted on: [REPLACE: Netlify or GitHub Pages]
1. About the project
Business	Artisan's Hearth Bakery, 123 Main Street, Pretoria, Gauteng, 0001
Audience	Pretoria households, event planners, and cafes and restaurants buying wholesale
Goals	Show the range and prices, take enquiries, make the bakery easy to find and contact
Built with	HTML5, CSS3, plain JavaScript (no framework), Leaflet and OpenStreetMap for the map
Pages: Home (index.html), About, Products, Gallery, Enquiry, Contact and a 404 page.

2. Part 3 features
Brief requirement	What was built	Where
Accordions	Animated, keyboard-friendly FAQ panels	About, Products, product modal
Tabs	Mission / vision / values; hours / getting here / parking	About, Contact
Modal	Product details in a native <dialog>	Products
Interactive map	Leaflet map with pin, popup, "Show my distance" and directions link	Contact
Animations	CSS transitions and a hero reveal, switched off for users who prefer reduced motion	All pages
Advanced DOM manipulation	Data-driven rendering, event delegation, shareable search URLs, live regions	All scripts
Gallery lightbox	Arrow keys, swipe, Esc, focus trap, captions and counter	Gallery
Dynamic content	Products built from one data file; baker's notes with "load more"; live open/closed status; "on the oven today" board	Products, Home, every page
Search	Live search with highlighting, category filter, sorting, empty state	Products
3. Forms
Enquiry (enquiry.html) asks about products, wholesale or custom cakes. After validation it shows an itemised estimate, a wholesale discount where it applies (10% over R1 500, 15% over R4 000), the earliest collection date (24 h for bread and pastries, 48 h for cakes, skipping Sundays and public holidays) and how we will reply.

Contact (contact.html) takes a general message. After validation it builds an email addressed to info@artisanshearth.co.za (set in js/data.js) with a preview, an Open in my email app button and a Copy message button.

Both forms

Validated with JavaScript: name, email, South African phone number, quantity, date, message length, selections and consent.
Clear error messages beside each field and in a summary that links to the field.
Submitted with AJAX and a loading spinner (simulated by default; paste a Formspree address into formEndpoint in js/data.js to deliver real messages).
A hidden field traps spam bots.
4. SEO
Item	Approach
Keywords	Local phrases such as artisan bakery Pretoria, sourdough bread Pretoria and custom celebration cakes Pretoria, used in titles, headings and body text
Title tags	Unique per page, about 50 to 58 characters
Meta descriptions and keywords	Unique per page; descriptions about 140 to 165 characters
Headings	One h1 per page, then h2 and h3 in order
Images	Descriptive file names (e.g. dark-rye-seeded-loaves-with-wheat-800.webp), specific alt text, WebP in two sizes
URLs and links	Short lowercase pages, canonical links, breadcrumbs, internal links in the copy
Mobile	Responsive at three breakpoints, collapsible menu
Structured data	JSON-LD for Bakery, Products, FAQ, breadcrumbs and gallery
Off-page	Share buttons on every page, Open Graph and Twitter cards, social links, local SEO details (name, address and phone kept identical; coordinates in schema). Backlink plan: directory listings, suppliers, local food bloggers
Extras	robots.txt, sitemap.xml, 404.html
5. Security and performance
Security: Content Security Policy, security headers (_headers), all dynamic text escaped before display, safe external links, input limits and spam trap, HTTPS on the host.
Performance: responsive WebP images, lazy loading, no libraries, map loads only when scrolled into view, long cache times for CSS and images.
Accessibility: skip link, labelled fields, announced errors, keyboard-friendly modal and lightbox, contrast checked against WCAG AA.
6. Folder structure
index.html  about.html  products.html  gallery.html  enquiry.html  contact.html  404.html
css/style.css
js/  data.js  main.js  products.js  gallery.js  map.js  forms.js
images/  screenshots/  tools/build.py
robots.txt  sitemap.xml  _headers  netlify.toml  .nojekyll  README.md
js/data.js holds the products, gallery, notes, hours and settings. tools/build.py regenerates the pages, sitemap and robots file; run it after changing data.js or the live address:

bash
SITE_URL=https://your-live-address/ python3 tools/build.py
7. Run and deploy
Run locally: python3 -m http.server 8000, then open http://localhost:8000.

GitHub Pages: push to main, then Settings, Pages, Deploy from a branch, main, / (root). Netlify: import the repository, leave the build command empty, set the publish directory to ..

Tested in Chromium (desktop and 390 px mobile): all pages load with no console errors; search, filter, sort, modal, lightbox, tabs, accordions, menu, validation, estimates and email building all work. [REPLACE: add other browsers or devices you tried]

8. Changelog
The Part 2 entries were written from problems found in the Part 2 code. Compare them with your marker's actual feedback and edit them to match.

Part 2 feedback corrections
Problem found	Change made
1	Clashing blue page background (
#0a1fdd), pink navigation links and a muddy content panel	New palette: enamel blue, crust brown, flour white, with checked contrast
2	home.html and index.html both existed; index.html held placeholder text	One complete index.html; home.html removed
3	Links pointed to enquiry.html and contact.html but files were Enquiry.html and Contact.html	All file names and links lowercase
4	Duplicate stylesheets, one inside a nested CSS/Style.css/ folder, plus a minified <style> block on the products page	One css/style.css
5	Placeholder and hotlinked images (via.placeholder.com, picsum.photos, missing files, Unsplash)	Local, optimised images only
6	Invalid HTML: a malformed <src=...> tag, empty style= attributes, missing lang	Valid markup; lang="en-ZA" on every page
7	Founder named Elias in the story but Lethabo in the team; "Thabo" used in Sakhe's bio	Names made consistent
8	Placeholder titles, no meta descriptions or keywords	Unique title, description and keywords per page
9	Meaningless image names (images3.jpg) and an unrelated packaged-roll photo	Descriptive names and alt text; unrelated photo not used
10	Blank icon headings in the footer and contact page; missing copyright symbol	Clear text labels and consistent footer
11	Forms with action="#" and no validation or feedback	Full validation, error messages, AJAX and responses
12	Generic Google Maps embed	Interactive Leaflet map pinned to the bakery
13	One breakpoint; menu stacked into a tall column on phones	Three breakpoints and a collapsible menu
Part 3 additions (all 2 November 2026)
#	Change
14	Shared data file, plus shared script for menu, status, enquiry list, accordion, tabs, toasts and share buttons
15	Dynamic products page with search, filter, sort, modal and enquiry list
16	New gallery page with lightbox
17	Interactive map on the contact page
18	Enquiry form with estimate and availability; contact form that compiles an email; AJAX submission
19	Image pipeline: 10 images in two sizes as WebP, plus share image and favicon
20	SEO: canonical links, Open Graph, JSON-LD, robots.txt, sitemap.xml, 404 page
21	Security: Content Security Policy and headers. An inline script found during testing was moved into main.js rather than weakening the policy
22	Bugs found in testing and fixed: the "Load more" button never hid, and a product chosen in the enquiry form was ignored when the list already had items
23	Page generator, deployment files and fresh screenshots

REFERENCE

- W3Schools. (2026). CSS Tutorial. [Online]. Available at: https://www.w3schools.com/css/
- MDN Web Docs. (2026). CSS: Cascading Style Sheets. [Online]. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS
- Google Fonts. (2026). Browse Fonts. [Online]. Available at: https://fonts.google.com/
- Unsplash. (2026). Beautiful Free Images & Pictures. [Online]. Available at: https://unsplash.com/



