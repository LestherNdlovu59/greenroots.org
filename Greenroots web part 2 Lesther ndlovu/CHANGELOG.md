# Changelog

---

## v1.1.0 — May 2026

Mostly a visual overhaul. The site was functional but the styling was pretty bare, so this update focused on making it actually feel like a proper community organisation's website.

### What changed

**New stylesheet (style.css)**
Rewrote the CSS from scratch. Switched to a proper design system using CSS variables for all colours, spacing, and fonts — so future tweaks don't mean hunting through the whole file. Brought in three Google Fonts (Playfair Display for headings, DM Sans for body text, Cormorant Garamond for pull quotes and accents).

**Colour palette**
Settled on deep forest greens, warm ivory backgrounds, and gold accents. Nothing too loud — it fits the nature/community vibe without looking like a generic template.

**Animations**
Added entrance animations on cards, blog posts, gallery items, and the hero sections. Also threw in a shimmer effect on the stats numbers, floating background orbs on the hero, and a subtle grain texture across the whole site. Nothing excessive — just enough to give it some life.

**Navbar**
Made it sticky with a frosted glass blur effect on scroll. Added an animated underline on nav links and a gradient stripe on the left edge.

**Responsive design (v1.1.0 focus)**
This was the main thing missing. The site was basically unusable on phones before. Fixed that with proper breakpoints across seven screen sizes — from tiny 360px phones all the way up to wide 1400px+ monitors. Also added a hamburger menu for mobile (pure CSS, no JavaScript needed). Hover effects are disabled on touch devices so cards don't get stuck highlighted after you tap them. Added a reduced-motion fallback for users who have that set in their OS accessibility settings.

**Gallery**
Grid adjusts from 1 column on phones up to 4 columns on wide screens. Images zoom and a dark overlay fades in on hover.

**Cards & sections**
Consistent hover lifts across donation cards, blog posts, feature blocks, and team member tiles. Each card has a gradient top-border that animates on hover.

**Footer**
Added a shimmer gradient bar along the top of the footer. Stacks vertically on mobile with the nav links wrapping into rows.

---

## v1.0.0 — April 2026

Initial build. All pages created: Landing, Home (Index), About, Blog, Contact, Gallery, and Donate. Basic HTML structure and navigation in place across all pages. No real styling beyond layout scaffolding.
