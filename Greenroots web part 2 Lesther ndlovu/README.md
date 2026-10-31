Subject: Web Development & Design
Student Name: Lesther Ndlovu
Student Number: ST10476598 

1. Organisation Overview
GreenRoots Community Garden is a registered non-profit founded in 2015 in Cape Town's Woodstock suburb. The organisation has transformed two abandoned plots into community gardens serving over 300 members. Its mission is to cultivate community connection, promote sustainable living, and provide equitable access to fresh produce. The target audience includes local residents, schools, corporate CSR partners, and donors supporting urban agriculture.
2. Website Goals and Objectives
The website will serve as GreenRoots' digital hub — driving membership registrations, online donations, and event attendance. Key goals include:
•	Increase Membership: 150 new member sign-ups within 6 months of launch.
•	Boost Donations: Provide a transparent online donation portal to grow financial support.
•	Event Promotion: Publicise workshops and planting days via an events calendar with RSVP functionality.
KPIs: 1,500 unique monthly visitors within 3 months; 3% donation conversion rate; 500 newsletter subscribers within 6 months.
3. Current Website Analysis
GreenRoots' existing website has been inactive since 2021, showing only a basic holding page with a contact email. Key weaknesses: no mobile-responsive design, outdated content, no online donation functionality, and poor SEO — the site is not indexed on Google. Improvements will focus on a mobile-first redesign, payment gateway integration, and a structured SEO strategy.
4. Proposed Website Features and Functionality
•	Homepage: Hero banner with mission statement, membership CTA, and donation button.
•	Membership Portal: Online registration with tiered membership options and secure payment.
•	Events Calendar: Interactive calendar with RSVP and automated email confirmations.
•	Donation Page: PayFast-integrated donation portal with recurring donation options.
•	Blog / Resources: Gardening tips and news updated bi-monthly.
•	Contact Page: Contact form, Google Maps showing garden locations, and social media links.
5. Design and User Experience
The design will reflect growth and sustainability. Colour scheme: Forest Green (#2D6A4F) and Earthy Brown (#6B4226) with Warm Cream (#FFF8E7) accents. Typography: Playfair Display for headlines and Open Sans for body text. Wireframes include a full-width hero, 3-column features section, events strip, and footer. WCAG 2.1 AA accessibility compliance will be maintained throughout.
6. Technical Requirements
•	Platform: WordPress CMS for easy non-technical content updates.
•	Hosting: Afrihost South Africa — POPIA compliant with low local latency.
•	Payment: PayFast gateway for donations and membership fees.
•	Plugins: The Events Calendar, WPForms, Yoast SEO, Mailchimp integration.
7. Timeline
Weeks 1–2: Discovery and planning. Weeks 3–4: Design mockups. Weeks 5–8: Development and integrations. Weeks 9–10: Content population. Weeks 11–12: Testing, accessibility audit, and launch.
8. Budget
•	Hosting & Domain: R 1,950
•	Theme & Plugins: R 2,100
•	Development (80 hrs @ R 300/hr): R 24,000
•	Content & Photography: R 5,500
•	Contingency (10%): R 3,355
Total Estimated Budget: R 36,905


---

## Pages Overview

| Page | Description |
|------|-------------|
| Landing Page | Welcome screen with background video and quick stats |
| Home (Index) | Hero section, what we do, impact stats, and testimonials |
| About | Organisation history, mission, team, values, and future plans |
| Blog | Articles on urban agriculture, community stories, and sustainability |
| Contact | Contact form, office details, map placeholder, and social links |
| Donate | One-time, monthly giving, and volunteer/sponsor options |
| Gallery | Image grid showcasing the garden and community events |

---

## HTML Tags Used

Below is a reference of every HTML tag used across the site, with a brief description and example from the project.

### Document Structure

| Tag | Purpose | Example |
|-----|---------|---------|
| `<!DOCTYPE html>` | Declares the document as HTML5 | `<!DOCTYPE html>` |
| `<html lang="en">` | Root element, sets language to English | `<html lang="en">` |
| `<head>` | Contains meta information about the page | `<head>...</head>` |
| `<body>` | Contains all visible page content | `<body>...</body>` |
| `<meta>` | Provides metadata like charset and viewport | `<meta charset="UTF-8">` |
| `<title>` | Sets the browser tab title | `<title>About Greenroots</title>` |
| `<link>` | Links external files like stylesheets | `<link rel="stylesheet" href="style.css">` |

### Navigation

| Tag | Purpose | Example |
|-----|---------|---------|
| `<nav>` | Defines the navigation section | `<nav class="navbar">...</nav>` |
| `<ul>` | Unordered list used for nav links | `<ul class="nav-links">...</ul>` |
| `<li>` | Individual list item | `<li><a href="About.html">About</a></li>` |
| `<a>` | Anchor tag for hyperlinks | `<a href="Donate.html" class="donate-btn">` |

### Layout & Containers

| Tag | Purpose | Example |
|-----|---------|---------|
| `<div>` | Generic container for grouping elements | `<div class="gallery-container">` |
| `<main>` | Main content area of the page | `<main class="about-container">` |
| `<section>` | Thematic grouping of content | `<section class="hero">` |
| `<article>` | Self-contained piece of content | `<article class="blog-post">` |
| `<footer>` | Bottom section of the page | `<footer class="footer">` |
| `<header>` | Introductory content or heading group | `<header>` |
| `<span>` | Inline container for styling | `<span class="dot">.</span>` |

### Headings & Text

| Tag | Purpose | Example |
|-----|---------|---------|
| `<h1>` | Main page heading | `<h1>🌱 ABOUT US</h1>` |
| `<h2>` | Section heading | `<h2>Our Mission</h2>` |
| `<h3>` | Sub-section heading | `<h3>Jane Doe</h3>` |
| `<h4>` | Minor heading | `<h4>Urban Agriculture in Practice</h4>` |
| `<p>` | Paragraph of text | `<p>GreenRoots was founded in 2015...</p>` |
| `<strong>` | Bold text for emphasis | `<strong>Inclusivity:</strong>` |
| `<b>` | Bold text (non-semantic) | `<b>This structure ensures sustainability.</b>` |
| `<cite>` | Citation or attribution | `<cite>- Sarah, Woodstock Resident</cite>` |

### Lists

| Tag | Purpose | Example |
|-----|---------|---------|
| `<ul>` | Unordered (bulleted) list | `<ul><li>Soil preparation</li></ul>` |
| `<ol>` | Ordered (numbered) list | `<ol><li>Use containers on balconies</li></ol>` |
| `<li>` | List item for both ul and ol | `<li>Planting seasonal crops</li>` |

### Forms

| Tag | Purpose | Example |
|-----|---------|---------|
| `<form>` | Wraps all form elements | `<form class="contact-form">` |
| `<label>` | Label for a form input | `<label for="name">Name</label>` |
| `<input>` | Text or email input field | `<input type="text" id="name" placeholder="Your name">` |
| `<textarea>` | Multi-line text input | `<textarea id="message" placeholder="Tell us how we can help">` |
| `<button>` | Clickable button | `<button type="submit">Send Message</button>` |

### Media

| Tag | Purpose | Example |
|-----|---------|---------|
| `<img>` | Displays an image | `<img src="Assets/garden.jpg" alt="Community Garden">` |
| `<video>` | Embeds a video element | `<video autoplay muted loop playsinline>` |
| `<source>` | Specifies media source for video | `<source src="Assets/videoplayback.mp4" type="video/mp4">` |

### Deprecated Tags (Present in Code — To Be Replaced)

| Tag | Issue | Replacement |
|-----|---


9. References
Afrihost. (2024). Shared web hosting plans. Retrieved from https://www.afrihost.com/
PayFast. (2024). PayFast merchant documentation. Retrieved from https://developers.payfast.co.za/
Web Content Accessibility Guidelines (WCAG) 2.1. (2018). W3C. Retrieved from https://www.w3.org/TR/WCAG21/
WordPress. (2024). WordPress for nonprofits. Retrieved from https://wordpress.org/
Yoast. (2024). SEO for nonprofits: Getting started guide. Retrieved from https://yoast.com/

