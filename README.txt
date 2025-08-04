Project: The Modern Frame - Fictional Art Gallery Website

Developer Name: Devanand K [RA2211003011171]

=======================================================

List of Implemented Features:

HTML:
- Full site structure with 4 pages: Home, Gallery, About, Contact.
- Proper use of DOCTYPE, html, head, and body tags.
- Semantic HTML5 tags used extensively: <header>, <nav>, <main>, <section>, <article>, <footer>.
- All pages are linked via a common navigation menu in the header using relative paths.
- Headings (<h1>-<h3>) and text formatting (<p>, <strong>, <em>, <blockquote>) used appropriately.
- An ordered list for the exhibition timeline on the About page.
- An unordered list for the staff list on the About page.
- A table for studio hours on the Contact page.
- At least 4 placeholder images from picsum.photos with `alt` attributes.
- One external link on the homepage with `target="_blank"` and `rel="noopener"`.
- An embedded YouTube video using an `iframe` on the Contact page.

CSS:
- A single external stylesheet (style.css) linked to all HTML pages.
- A variety of selectors used: element, class, ID, descendant, pseudo-class (:hover), and pseudo-element (::before).
- Colors defined using named colors (red), HEX (#2c3e50), RGB (rgb(44, 62, 80)), and HSL (hsl(0, 0%, 100%)).
- CSS Box Model demonstrated with `box-sizing: border-box`, `margin`, and `padding`.
- Text alignment, transformation, decoration, letter-spacing, and text-shadow applied.
- `float: left` used to wrap text around an image on the About page.
- Positioning implemented:
  - `position: fixed` for the sticky header.
  - `position: relative` and `position: absolute` for the "Featured!" badge on the homepage image.
- Flexbox used to create the header layout.
- CSS Grid used to create the 2x2 artwork layout on the Gallery page.
- Styled lists with custom bullets (pseudo-element) and default style removal.
- Background properties used for the hero section: `background-image`, `background-size`, `background-position`, `background-repeat`.
- Border properties (`border`, `border-radius`) and `box-shadow` applied to various elements.
- CSS Transitions used for smooth hover effects on navigation links and gallery images.
- CSS Transform (`scale`) applied on hover to links and gallery images.
- CSS Animation using `@keyframes` for a blinking banner on the homepage.

=======================================================

Known Issues:
- The website is designed for desktop viewports only and is not responsive. The layout may not render correctly on mobile devices or smaller screens.
- All content is static and fictional. Links to external sites are placeholders.

=======================================================

Browser Tested:
- Google Chrome (Version 120+)
- Mozilla Firefox (Version 118+)