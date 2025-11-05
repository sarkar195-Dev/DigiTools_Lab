DigiToolsLab - Multi-Page Landing Site

This project is a complete, single-file, multi-page website for "DigiToolsLab," a fictional digital tools marketplace. It is built using HTML, Tailwind CSS (via CDN), and vanilla JavaScript.

The site is fully responsive and simulates a multi-page experience using JavaScript to show and hide different page sections (<div id="page-name">).

Features

Single-Page Application (SPA) Simulation: Uses JavaScript to toggle visibility of different "pages" without a server, providing a fast user experience.

Dynamic Content: The Shop and Blog pages are dynamically populated from JavaScript arrays (allProducts, allBlogPosts).

Pagination: Both the Shop and Blog pages include a complete, functional pagination system built with JavaScript.

Responsive Design: Features a mobile-friendly layout with a collapsible hamburger menu for navigation on smaller screens.

Modal Pop-up: Includes a functional Login/Register modal with tabbed switching between the two forms.

Multiple Pages: Contains 8 distinct page layouts:

Home Page

About Page

Shop Page (with dynamic grid and pagination)

Blog Page (with dynamic grid and pagination)

Contact Page

Privacy Policy

Terms and Conditions

Affiliate Dashboard

Pages Overview

1. Home Page (#home-page)

The main landing page featuring a hero section, a benefits grid, featured "Group Tools" packages, promotional banners, and an FAQ section.

2. Shop Page (#shop-page)

A marketplace layout with a sidebar for filters (UI only) and a main grid for products. Products are loaded dynamically from the allProducts array, and users can navigate through pages using the pagination controls.

3. Blog Page (#blog-page)

Similar to the shop, this page features a sidebar and a main grid for blog post summaries. Posts are loaded from the allBlogPosts array, and pagination is included.

4. About Page (#about-page)

A static page describing the company's mission, vision, core values, and founder.

5. Contact Page (#contact-page)

A static page with a "Send us a Message" form and a sidebar with contact details (Email, Phone, Address).

6. Affiliate Dashboard (#affiliate-page)

A dedicated dashboard for affiliate partners, showing stat cards (Total Earnings, Clicks, Conversion Rate), the user's affiliate link, and a table of recent commissions.

7. Legal Pages (#privacy-page, #terms-page)

Static pages with formatted text for the site's Privacy Policy and Terms and Conditions.

Technologies Used

HTML5: For the core structure and content.

Tailwind CSS (via CDN): For all styling, layout, and responsiveness.

Vanilla JavaScript: For all interactivity, including:

Page routing (renderPage() function)

Modal logic (openAuthModal(), closeAuthModal())

Dynamic content rendering for Shop and Blog

Pagination logic (loadShopPage(), loadBlogPage())

How to Run

Since this is a self-contained static site, no build steps or servers are required.

Clone or download the repository.

Open the index.html file directly in any modern web browser (like Chrome, Firefox, or Safari).

All CSS, JavaScript, and data are included within this single file.

