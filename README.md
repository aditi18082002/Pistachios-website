# Pistachios-website

# Documentation

This documentation describes the structure and functionality of the HTML code provided. The code represents a webpage that includes external resources, navigation, content sections, and JavaScript for an image slider. Below is an overview of the HTML structure and its components.

# Document Overview

- Document Type: HTML5 (<!DOCTYPE html>).
- Document Language: English (`<html lang="en">`).

# Document Head

The `<head>` section contains metadata and external resources used by the document.

- Character Encoding: Declared as UTF-8 (`<meta charset="UTF-8">`) for proper text rendering.
- Compatibility: Ensures compatibility with the latest version of Internet Explorer (`<meta http-equiv="X-UA-Compatible" content="IE=edge">`).
- Viewport Settings: Defines viewport settings for responsive design (`<meta name="viewport" content="width=device-width, initial-scale=1.0">`).
- Title: Sets the page title to "Document" (`<title>Document</title>`).
- External Stylesheets: Links external CSS files for styling.
  - Swiper CSS: `<link rel="stylesheet" href="https://unpkg.com/swiper@8/swiper-bundle.min.css" />`
  - Font Awesome Icons CSS: `<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.15.4/css/all.css" ...>`
  - Custom Styles: `<link rel="stylesheet" href="style1.css">`

# Document Body

The `<body>` section contains the main content of the webpage, divided into various sections.

# Container

- `<div class="container">`: Acts as a container for the entire webpage.

# Wave Background

- `<div class="wave">`: Includes a wave background image (`<img src="bg.png" alt="">`).

# Navigation

- `<nav>`: Represents the navigation bar.
- `<ul>`: Unordered list for navigation items.
- Navigation Items:
  - Home: `<li><a href="#">Home</a></li>`
  - Products: `<li><a href="#">Products</a></li>`
  - Service: `<li><a href="#">Service</a></li>`
  - Types: `<li><a href="#">Types</a></li>`
  - FAQ: `<li><a href="#">FAQ</a></li>`
- Logo Image: `<img src="logo.png" alt="">`

# Main Content

- `<div class="main-content">`: Contains the primary content of the webpage.
- Image Slider (`Swiper`):
  - `<div class="swiper mySwiper">`: Initializes an image slider.
  - `<div class="swiper-wrapper">`: Contains individual slides.
  - Slides (Example):
    - `<div class="swiper-slide"><img src="img1.png" alt=""></div>`
  - Main Text:
    - `<div class="main-text">`: Contains a heading and a "Know More" button.
    - Heading: `<h1>The Pistachios</h1>`
    - Button: `<button>Know More</button>`

# Right Section

- `<div class="right">`: Contains three feature boxes.
- Feature Box (Example):
  - `<div class="box">`: Represents a single feature box.
  - Image: `<img src="img4.png" alt="">`
  - Inner Box:
    - `<div class="inner-box">`: Contains a feature title (e.g., "100% Organic").
    - Feature Title: `<h3>100% Organic</h3>`

# Social Links

- `<div class="social-links">`: Displays social media icons.
- Icons (Font Awesome):
  - Instagram: `<i class="fab fa-instagram"></i>`
  - Facebook: `<i class="fab fa-facebook-f"></i>`
  - Twitter: `<i class="fab fa-twitter"></i>`
  - Email: `<i class="far fa-envelope"></i>`

 # JavaScript

- JavaScript is included at the end of the document.
- It initializes the Swiper image slider for the carousel.
- Swiper Configuration:
  - `slidesPerView: 1`: Shows one slide at a time.
  - `spaceBetween: 30`: Provides 30px spacing between slides.
  - `loop: true`: Enables infinite looping of slides.

```html
<script src="https://unpkg.com/swiper@8/swiper-bundle.min.js"></script>
<script>
    var swiper = new Swiper(".mySwiper", {
        slidesPerView: 1,
        spaceBetween: 30,
        loop: true,
    });
</script>
```
This code creates a structured webpage with navigation, content sections, and interactive features.
