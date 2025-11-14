# SMACIRCLE S1 Ultra-light Ebike

**Seed Idea:** My Fictional Product

This is a responsive website for "SMACIRCLE S1 Ultra-light Ebike" built via HTML and CSS.

## Design Rationale

**Global Layout:**
The main page layout (header, main, footer) is built using
**CSS Grid**
This allows for a simple '1fr' row to push the footer to the bottom of the viewport, creating a "sticky footer" effect.
**Components:**
    **Header:** The navigation bar uses **Flexbox** ('justify-content: space-between') to cleanly separate the title and the nav links.
    **Features:** The cards are arranged using **CSS Grid** ('grid-template-columns: 1fr 1fr 1fr'), which allows for easy adjustments on different screen sizes.
**Responsiveness:** The layout uses two media query breakpoints to adjust for tablet and mobile:
    * At '992px', the feature grid changes from 3 to 2 columns.
    * At '768px', the feature grid changes to 1 column, and the header navigation stacks vertically.

## CSS-Only Interactive Components

1. **Feature Cards:** On ':hover', the cards scale up ('transform: scale(1.05)') with a smooth 'transition'.
2. **Nav Links:** On ':hover', the links change 'background-color' and 'color'.
3. **Form Inputs:** On ':focus', all inputs and buttons receive a custom blue 'box-shadow' outline for accessibility.

## Screenshots
# Desktop View 
assets/desktop.png
# Mobile View
assets/mobile.png

## Validator Proofs
# HTML Proof
assets/html-proof.png
# CSS Proof
assets/css-proof.png