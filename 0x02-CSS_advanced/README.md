# 0x02. Advanced CSS

## Table of Contents

1. [Selectors, Properties, and Values](#selectors-properties-and-values)
2. [Block vs. Inline Styling](#block-vs-inline-styling)
3. [Ensuring Consistency Across Browsers (CSS Reset)](#ensuring-consistency-across-browsers-css-reset)
4. [Setting up CSS Variables](#setting-up-css-variables)
5. [Inline, Embedded, and External CSS](#inline-embedded-and-external-css)
6. [Understanding Grid Systems (with Floats)](#understanding-grid-systems-with-floats)
7. [Icons: Webfonts vs. SVG Icons](#icons-webfonts-vs-svg-icons)
8. [Pseudo-Classes vs. Pseudo-Elements](#pseudo-classes-vs-pseudo-elements)
9. [Creating Background Gradients](#creating-background-gradients)
10. [Animating Elements in CSS](#animating-elements-in-css)
11. [Transforming Elements (2D, 3D)](#transforming-elements-2d-3d)
12. [Understanding Vendor Prefixes](#understanding-vendor-prefixes)
13. [Other Resources](#other-resources)

---

### Selectors, Properties, and Values

CSS utilizes selectors to target HTML elements and apply styles using properties and values. Selectors can target elements by their type, class, ID, attributes, or relationship to other elements. Properties define the style aspect being modified, while values determine the specific appearance.

Learn more: [MDN Web Docs - CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)

### Block vs. Inline Styling

In CSS, block-level elements start on a new line and take up the full width available, while inline elements do not start on a new line and only take up as much width as necessary. Understanding these distinctions is crucial for proper layout and styling.

Learn more: [CSS-Tricks - Understanding CSS Layout](https://css-tricks.com/understanding-css-layout-block-formatting-context/)

### Ensuring Consistency Across Browsers (CSS Reset)

To ensure consistent rendering of styles across different browsers, CSS resets are used to remove default browser styling. This helps establish a consistent baseline for styling across various platforms and browsers.

Learn more: [CSS Tools: Reset CSS](https://meyerweb.com/eric/tools/css/reset/)

### Setting up CSS Variables

CSS variables, also known as custom properties, allow for the creation of reusable values in CSS. They enhance maintainability and make it easier to update styles across an entire website by changing only a few variables.

Learn more: [MDN Web Docs - Using CSS custom properties (variables)](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties)

### Inline, Embedded, and External CSS

Inline CSS is applied directly to individual HTML elements using the `style` attribute. Embedded CSS is included within the `<style>` tags in the HTML document. External CSS is stored in separate .css files and linked to HTML documents using the `<link>` tag.

Learn more: [W3Schools - CSS Tutorial](https://www.w3schools.com/css/)

### Understanding Grid Systems (with Floats)

Grid systems in CSS allow for the creation of complex layouts by dividing the page into rows and columns. Floats were traditionally used for creating grid-like layouts before the advent of modern CSS Grid and Flexbox layouts.

Learn more: [CSS-Tricks - Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

### Icons: Webfonts vs. SVG Icons

Icons can be implemented in CSS using either webfonts (such as Font Awesome) or SVG icons. Webfonts allow for scalable vector icons using font glyphs, while SVG icons are XML-based and offer more control and flexibility.

Learn more: [CSS-Tricks - Icon Fonts vs SVGs](https://css-tricks.com/icon-fonts-vs-svg/)

### Pseudo-Classes vs. Pseudo-Elements

Pseudo-classes target elements based on their state or position, such as `:hover` or `:first-child`. Pseudo-elements, on the other hand, target specific parts of elements, such as `::before` or `::after`, allowing for the creation of additional content or styling.

Learn more: [MDN Web Docs - Pseudo-classes and pseudo-elements](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes)

### Creating Background Gradients

CSS allows for the creation of gradient backgrounds using the `linear-gradient()` or `radial-gradient()` functions. Gradients can add depth and visual interest to backgrounds, enhancing the overall design.

Learn more: [CSS-Tricks - Gradients](https://css-tricks.com/css3-gradients/)

### Animating Elements in CSS

CSS animations enable the smooth transition of element properties over time, such as opacity, position, or scale. Animations can enhance user experience and add interactivity to web pages.

Learn more: [MDN Web Docs - CSS Animations](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations)

### Transforming Elements (2D, 3D)

CSS transformations allow for the modification of an element's appearance by scaling, rotating, skewing, or translating it in 2D or 3D space. These transformations can create visually compelling effects and animations.

Learn more: [CSS-Tricks - Transform](https://css-tricks.com/almanac/properties/t/transform/)

### Understanding Vendor Prefixes

Vendor prefixes are prefixes added to CSS properties to ensure compatibility with specific browsers during periods of experimental or non-standard feature implementation. While less common now due to improved browser support, they were previously crucial for cross-browser compatibility.

Learn more: [MDN Web Docs - Vendor Prefixes](https://developer.mozilla.org/en-US/docs/Glossary/Vendor_Prefix)

### Other Resources

- [CSS Reference - A free visual guide to CSS](https://cssreference.io/)
- [Can I use,,, Support tables for HTML5, CSS3, etc](https://caniuse.com/)
- [CSS Reference](http://ref.openweb.io/CSS/)
- [CSS Properties | HTML Dog](https://htmldog.com/references/css/properties/)
- [Box Sizing](https://css-tricks.com/box-sizing/)
- [CSS specificity calculator](https://www.codecaptain.io/tools/css-specificity-calculator)
- [Play with CSS selector](https://frontend30.com/css-selectors-cheatsheet/)
