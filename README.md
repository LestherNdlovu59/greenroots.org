# GreenRoots Community Garden Website

A multi-page, static website for **GreenRoots**, a fictional Cape Town community garden non-profit. Built with plain HTML and CSS for the Web Development & Design module (Part 2 of the portfolio of evidence).

The site is designed around the organisation's goals from the Part 1 proposal: growing membership, encouraging donations and promoting community events.

## Pages

| Page | File | What it contains |
|---|---|---|
| Landing page | `Landingpage.html` | Full-screen background video, welcome message and quick stats (300+ members, 5 gardens, 10+ schools) |
| Home | `Index.html` | Hero section, what GreenRoots does, impact stats and testimonials |
| About | `About.html` | Organisation history, mission, team, values and future plans |
| Blog | `Blog.html` | Articles on urban agriculture, community stories and sustainability |
| Gallery | `Gallery.html` | Image grid of the garden and community events |
| Contact | `Contact.html` | Contact form, organisation details, map placeholder and social links |
| Donate | `Donate.html` | One-time donation, monthly giving, and volunteer or sponsor options |

## Features

- Seven linked pages with a shared navigation bar and footer
- Sticky navigation bar with a blurred "frosted glass" effect on scroll
- Design system built on CSS variables for colours, fonts, spacing and transitions
- Entrance animations on cards, blog posts, gallery items and hero sections
- Responsive layout with breakpoints from 360px phones to 1400px+ desktop monitors
- Gallery grid that adapts from 1 column on phones to 4 columns on wide screens
- Hover effects disabled on touch devices, and a reduced-motion fallback for users who prefer less animation
- Semantic HTML structure (`nav`, `main`, `section`, `article`, `footer`) and form labels

## Design

| | |
|---|---|
| **Colours** | Forest greens, warm ivory backgrounds and gold accents |
| **Headings** | Playfair Display |
| **Body text** | DM Sans |
| **Accent text** | Cormorant Garamond (pull quotes) |

Fonts are loaded from Google Fonts, so an internet connection is needed to see them as designed.

## Tech stack

- HTML5
- CSS3 (custom properties, Flexbox/Grid layout, media queries, keyframe animations)
- No JavaScript, frameworks or build tools

## Running the project

No installation is needed.

1. Clone or download the repository:
   ```
   git clone https://github.com/Justlester777/Greenroots-web.git
   ```
2. Open `Landingpage.html` in any modern browser. This is the entry point, and the navigation links to every other page.

## Project structure

```
.
├── Landingpage.html      Entry page with video background
├── Index.html            Home page
├── About.html
├── Blog.html
├── Gallery.html
├── Contact.html
├── Donate.html
├── style.css             Main stylesheet used by every page
├── Assets/               Images and background video
├── Web proposal/         Planning documents (Part 1)
├── CHANGELOG.md          Version history
└── README.md
```

## Version history

See [CHANGELOG.md](CHANGELOG.md).

- **v1.1.0 (May 2026):** new stylesheet and design system, animations, sticky navbar and responsive breakpoints
- **v1.0.0 (April 2026):** initial build of all seven pages with basic structure and navigation

## Known issues and planned improvements

- **Contact form does not submit.** The form has no `action` or backend, so "Send Message" does nothing yet.
- **Donate and "Join Us" buttons are placeholders.** Several buttons link to `#` instead of a real destination, and there is no payment integration.
- **Mobile menu.** The stylesheet contains hamburger-menu styles, but the HTML pages don't include the matching markup, so the mobile menu needs checking.
- **Deprecated HTML.** `Gallery.html`, `Landingpage.html` and `Index.html` still use `<center>` and `<marquee>`. These should be replaced with CSS (`text-align: center`).
- **Unused stylesheet.** `Css/styles.css` is a leftover from an earlier version, and every page uses `style.css`.
- **Large video file.** `Assets/videoplayback.mp4` is about 8 MB, which slows loading on mobile data. It should be compressed.
- **Accessibility.** The site needs an alt-text and colour-contrast review against WCAG 2.1 AA.

## Author

**Lesther Ndlovu**
Web Development & Design, The IIE
GitHub: [@Justlester777](https://github.com/Justlester777)

## Acknowledgements

Images are used for educational purposes only. If this site is ever published, replace them with licensed or original photography and credit the sources.
