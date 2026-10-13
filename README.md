# Budget Tracker - Week 4 Layout & Responsive Design

An advanced, responsive personal budget tracker built with modern CSS Grid, Flexbox, Micro-interactions, and Automatic Dark Mode.

## Features & Implementation
- **CSS Grid & Flexbox Layout:** Uses a multi-column CSS Grid dashboard setup on desktop screens, neatly positioning the input form alongside the expense table, with Flexbox handling inner alignments.
- **Responsive Media Query:** Automatically collapses the layout into a streamlined, clean single-column stack below `768px` screen widths, fully verified via DevTools.
- **Card Micro-interactions:** Cards feature subtle, high-performance transitions (`transform: translateY(-4px)` and enhanced `box-shadow`) executing in under `250ms` on both mouse hover and keyboard focus (`tabindex="0"`).
- **Dark Theme (Stretch Goal):** Implements system-aware dark styling by overriding `--root` CSS variables inside a `@media (prefers-color-scheme: dark)` query.

## File Structure
- `index.html`: Dashboard structure with proper semantic tags and accessibility attributes.
- `style.css`: Core layout rules, CSS Grid/Flexbox structures, responsive breakpoints, animations, and color scheme variables.
- `README.md`: Technical documentation.
