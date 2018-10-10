# Img Lazy Load
A JS Lazy Load script for html images.

## Getting Started
You need to link JS file in  **bottom** of your HTML file.

```html
<script src="img-lazy-load.js"></script>
```

Then change the **src** attribute by **data-src** for example:

```html
<img data-src="example-img.jpg">
```

Finally only need to initialize the "LazyLoad()" function when document ready:

```javascript
window.onload = function() {
  LazyLoad()
};
```
