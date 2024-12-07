# Customization Instructions
## Vue.js
- Update `scripts.js` for new Vue components.
- Mount Vue apps on Shopify DOM elements.

## GSAP
- Define animations in `scripts.js`.
- Example: `gsap.to('.element', { x: 200, duration: 1.5 });`

## LazySizes
- Use `data-src` for images in `theme.liquid`.
- Example:
  ```html
  <img class="lazyload" data-src="{{ 'image.jpg' | asset_url }}" alt="Example Image">
  ```

