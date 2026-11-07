# rameshsoft-website

Static clone of rameshsoft.com - India's No.1 JAVA Automation Training Institute

## Screenshot
![Cloned website screenshot](screenshot.png)

## Overview
This is a 100% static clone of [rameshsoft.com](https://rameshsoft.com/), created for offline viewing and archival purposes.

## Structure
- `index.html` - Main HTML file (all assets rewritten to local paths)
- `css/` - 14 stylesheets (Bootstrap, Font Awesome, Owl Carousel, theme styles)
- `js/` - 16 JavaScript files (jQuery, Bootstrap, BXSlider, Divi Builder, etc.)
- `fonts/` - Google Fonts CSS + Font Awesome webfonts (woff2, woff, ttf, eot, svg)
- `img/` - 33 images (logo, hero banners, course thumbnails, gallery, team photos)

## Serve locally
```bash
python3 -m http.server 8080 --directory .
# Open http://localhost:8080/
```

## Original Site
- **URL**: https://rameshsoft.com/
- **Description**: India's No.1 JAVA Automation Training Institute
- **Courses**: Core Java, Selenium, Appium, Protractor, Python, Hibernate, Web Services, Spring, Salesforce

## Notes
- All external asset URLs rewritten to local paths
- Cloudflare email obfuscation decoded to real mailto link
- Dead eduflips.com background images replaced with local equivalents
- Contact Form 7 & Divi Builder scripts included but require WordPress backend to function
- External links (social media, Google Maps, course pages) still point to live site