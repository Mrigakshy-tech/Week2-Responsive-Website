# Testing notes

The source has been structured for browser testing at 360px, 768px, and 1280px.
Recommended manual checks:

1. Open `Source_Code/index.html` in Chrome.
2. Use DevTools responsive mode and enter 360px, 768px, and 1280px.
3. Confirm the mobile navigation toggle opens/closes and sets `aria-expanded`.
4. Click each navigation link and verify its section target.
5. Confirm there is no horizontal scrolling at narrow widths.

The PNGs in `Output/` are the direct browser screenshots from my Chrome session.

## Mobile overflow refinement

The mobile CSS includes additional heading-size and wrapping rules for narrow screens (including widths at or below 380px).
