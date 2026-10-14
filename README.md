# Responsive Pure JavaScript Masonry Layout

A lightweight, dependency-free Masonry layout template built with vanilla JavaScript and SCSS.

It dynamically calculates item positioning after all images have fully loaded, delivering precise responsive column layouts across various screen sizes.

---

## Key Features

- **Zero Dependencies**  
  Built entirely with Pure JS and SCSS without relying on jQuery or external libraries, making it fast and easy to port into any web project.
- **Image Load Detection**  
  Uses `Promise.all` to wait for all image assets to load before calculating layout heights, preventing overlap and layout shifts.
- **Responsive & Smooth Transitions**  
  Dynamically recalculates column counts on window resize with CSS transition support for fluid card repositioning.

---

## Usage

1. Add the container (`#container`) and items (`.item`) to your HTML markup.
2. Include `masonry.js` and `masonry.scss` (or compiled CSS) in your project.

```html
<div id="container">
  <div class="item">
    <img src="path/to/image.jpg" alt="" />
    <p>Caption Text</p>
  </div>
  <!-- Additional items -->
</div>

<script src="js/masonry.js"></script>
