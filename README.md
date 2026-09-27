# Trip_advisor

A front-end recreation of the Tripadvisor homepage, built with plain HTML and CSS (no frameworks, no build step). This was made by studying a screen recording of the real site and rebuilding the layout, spacing, and colors by eye.

What's inside
Header – logo, "Plan with AI" pill button, nav links, and a Sign in button
Hero search section – the big "Where to?" heading with tabs (Search All / Things to Do / Hotels / Restaurants) and a search bar with Ask AI + Search buttons
Promo banner – green highlight section with a background graphic and a "Book now" call to action
Interest grid – Outdoors, Food, Culture, Water cards
Tour/hotel card rows – "Outdoor adventures" and "Top-rated tour operators" sections with ratings, review counts, and tags
Footer – link columns, legal links, currency/region dropdowns, and social icons

Files
index.html   → all the page markup
style.css    → all the styling
assets/      → images used in the interest cards and listing 

Responsiveness

The layout adapts across screen sizes:

On smaller screens, the search bar switches from one pill shape into a stacked layout (input on top, buttons below) so nothing feels squeezed.
The category tabs (Search All, Things to Do, etc.) scroll sideways on mobile instead of wrapping awkwardly.
The "Plan with AI" button stays visible at every screen size, with a hover/press effect on larger screens where a mouse is available.
Card grids (interests, hotels, tour operators) reflow into fewer columns as the screen narrows.

It's been checked on common breakpoints (desktop, tablet, and phone widths), but if you spot a screen size where something looks off, that's an easy thing to tell me and get fixed.
