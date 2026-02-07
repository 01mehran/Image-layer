# Dynamic Image Hover Layer 🎨

A lightweight, reusable HTML/CSS component that reveals a dynamic information layer when hovering over an image. Perfect for showcasing sports players, products, portfolios, or any collection of items.

## preview 📷

> desktop
> ![demo](./images/desktop.png)

> hover effect
> ![demo](./images/demo-hover.png)

## ✨ Features

- Clean Hover Effect: Smooth CSS transition reveals a semi-transparent overlay.
- Dynamic Content Layer: Display any information (name, bio, stats, price, etc.) on hover.
- Fully Customizable: Easily modify colors, opacity, animation speed, and content.
- Interactive & Extensible: The overlay layer can contain links, buttons, or any HTML element. Make it clickable to navigate to a details page.
- Pure HTML/CSS: No JavaScript required for the basic hover effect. Lightweight and fast.
- Responsive Foundation: Built with flexible units for easy adaptation to different layouts.

## 🚀 How to Use

1.  Include the CSS in your <head>:

    <link rel="stylesheet" href="path/to/hover-layer.css">

2.  Use the HTML Structure for each item:

```html
<div class="image-wrapper">
  <img src="./images/CR7.jpg" alt="cr7" />
  <div class="layer" style="--bg: #e92929">
    <h2>CR7</h2>
    <span>The best player in the world (GOAT)</span>
  </div>
</div>
```

3.  Customize the content inside .hover-layer for your use case (e.g., product name, price, "Add to Cart" button).

## 🛠️ Customization

### Change Colors & Opacity

Edit the CSS variables in :root or directly in the .hover-layer class:
`css
.hover-layer {
background: rgba(0, 0, 0, 0.75); /_ Dark overlay _/
/_ Change to any color, e.g., rgba(52, 152, 219, 0.8) for blue _/
}
