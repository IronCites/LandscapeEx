# GreenVista Landscape Design Website Template

## Overview
GreenVista is a modern, responsive website template for a fictional landscape design company. It features a clean design with a green color scheme and multiple sections to showcase services, portfolio, and company information.

## Features
- Responsive single-page design
- Modern UI with smooth animations
- Multiple sections: hero, about, services, features, process, portfolio, testimonials, call-to-action, and contact
- Mobile-friendly navigation
- Contact form
- Back-to-top button
- Smooth scrolling

## File Structure
```
green-vista/
├── css/
│   └── styles.css
├── images/
│   ├── hero.jpg
│   ├── about.jpg
│   ├── process.jpg
│   ├── cta-bg.jpg
│   ├── service-1.jpg
│   ├── service-2.jpg
│   ├── service-3.jpg
│   ├── portfolio-1.jpg
│   ├── portfolio-2.jpg
│   ├── portfolio-3.jpg
│   ├── portfolio-4.jpg
│   ├── portfolio-5.jpg
│   └── portfolio-6.jpg
├── js/
│   └── script.js
├── index.html
└── README.md
```

## Customization

### Images
Replace the placeholder images in the `images/` directory with your own images. Make sure to maintain the same filenames or update the references in the HTML and CSS files.

### Colors
The color scheme can be easily modified by changing the CSS variables in the `:root` selector in `css/styles.css`:

```css
:root {
    --primary-color: #4CAF50; /* Main green color */
    --primary-dark: #3b8c3f; /* Darker green for hover states */
    --primary-light: #81c784; /* Lighter green for accents */
    --secondary-color: #1b1b1b; /* Dark gray/black */
    --light-bg: #f5f8f5; /* Light green background */
    /* ... other variables ... */
}
```

### Content
Update the content in `index.html` to match your business information, services, and portfolio.

## Browser Compatibility
This template is compatible with all modern browsers including Chrome, Firefox, Safari, and Edge.

## Credits
- Font Awesome for icons
- Google Fonts for typography
- Unsplash for placeholder images

## License
Feel free to use this template for both personal and commercial projects.