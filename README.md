# Saudi-Riyal-Symbol
Saudi Riyal Symbol 2025
# Saudi Riyal Currency Symbol (SVG)

A clean vector implementation of the Saudi Riyal (SR) currency symbol for web applications.
## Features
- **Pure SVG** - Scalable vector graphic that maintains quality at any size
- **Lightweight** - Single-path design (only 1.2 KB)
- **Accessible** - Built with proper XML namespace and ARIA-compatible
- **Customizable** - Easy to style with CSS
- **Standard Dimensions** - Optimized for 15x15px display

## Installation
```
<!-- Direct usage -->
<svg xmlns="http://www.w3.org/2000/svg" 
     viewBox="0 0 1124.1 1256.4" 
     width="15" 
     height="15"
     aria-label="Saudi Riyal symbol">
  <path d="M699.6 1113a459.43 459.43 0 0 0-38.4 143.4l424.5-90.2c20.1-44.5 33.3-92.7 38.4-143.4L699.6 1113zm386.1-217.2c20.1-44.5 33.3-92.7 38.4-143.4l-330.7 70.3V687.6l292.3-62.1c20.1-44.5 33.3-92.7 38.4-143.4l-330.7 70.3V66.1a465.36 465.36 0 0 0-132.3 111v403.4L529 608.6V0a465.36 465.36 0 0 0-132.3 111v525.7L101 698.6a467.04 467.04 0 0 0-38.6 144.3l334.3-71v170.3l-358.3 97.1C18.3 1062.8 5.1 1111 0 1161.7l375-79.7c30.5-6.3 56.8-24.4 73.8-49.2l68.8-102a66.25 66.25 0 0 0 11.3-37v-150l132.3-28.1v270.4l424.5-90.3z"/>
</svg>
```
Usage
# Basic Implementation
```
<span class="currency">
  1,000.00 SR
  <svg ...>[SVG code here]</svg>
</span>
```
# Sizing Options
```
<!-- Small (default) -->
<svg width="15" height="15"...>

<!-- Medium -->
<svg width="20" height="20"...>

<!-- Large -->
<svg width="24" height="24"...>
```

# Styling with CSS
css
```
/* Change color */
svg path {
  fill: #2D572C; /* Saudi Riyal green */
}

/* Dark mode */
@media (prefers-color-scheme: dark) {
  svg path {
    fill: #fff;
  }
}
```
# Technical Specifications
Viewport: 1124.1 × 1256.4

Aspect Ratio: ~0.895 (original design ratio)

Path Complexity: Single continuous path

Compatibility: All modern browsers

# License
MIT License - Free for personal and commercial use. Attribution appreciated but not required.
Note: This symbol follows the official design specifications from the Saudi Arabian Monetary Authority (SAMA).

# This README includes:
1. Clear usage examples
2. Styling guidance
3. Technical specifications
4. Licensing information
5. Responsive design considerations
6. Accessibility features
7. Dark mode support

You can customize the colors, sizes, and additional details based on your specific implementation needs.

