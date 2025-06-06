# Unbitable Cyber Security Website

This is a responsive website for Unbitable Cyber Security, created based on the provided template design and content files.

## Website Structure

- `index.html` - The main homepage
- `css/style.css` - Main stylesheet for the entire website
- `js/main.js` - JavaScript functionality
- `images/` - Contains all image assets
- `pages/` - Contains all content pages

## Content Pages

The website includes the following content pages:

1. Password Security (`pages/password-security.html`)
2. Antivirus (`pages/antivirus.html`)
3. Email Security (`pages/email-security.html`)
4. Public WiFi (`pages/public-wifi.html`)
5. Data Leakage (`pages/data-leakage.html`)
6. Device Usage (`pages/device-usage.html`)
7. Software Security (`pages/software-security.html`)
8. Image Usage Online (`pages/image-usage.html`)
9. Privacy Policy (`pages/privacy-policy.html`)
10. Terms and Conditions (`pages/terms-conditions.html`)
11. Cookie Policy (`pages/cookie-policy.html`)

## How to Modify the Website

### Changing Content

1. To modify the content of any page, simply edit the corresponding HTML file in the `pages/` directory.
2. The content is structured with HTML tags:
   - `<h1>`, `<h2>`, `<h3>` for headings
   - `<p>` for paragraphs
   - `<ul>` and `<li>` for lists

### Changing Styles

1. All styling is contained in the `css/style.css` file.
2. The website uses CSS variables for colors, which can be easily changed at the top of the CSS file:
   ```css
   :root {
       --primary-color: #00c8ff;
       --secondary-color: #0066cc;
       --dark-blue: #001a33;
       --light-blue: #e6f7ff;
       --white: #ffffff;
       --black: #000000;
       --gray: #f0f0f0;
   }
   ```

### Adding New Pages

1. Copy the `page-template.html` file from the `pages/` directory
2. Rename it to your desired page name
3. Update the title, description, and content
4. Add a link to the new page in the navigation menu in all HTML files

## Responsive Design

The website is fully responsive and works on all device sizes:

- Desktop (1200px and above)
- Tablet (768px to 1199px)
- Mobile (below 768px)

The responsive behavior is handled through media queries in the CSS file.

## Images

- The website uses the provided logo and shield images
- Background elements use the dots pattern images
- All images are in the `images/` directory

## JavaScript Functionality

The `main.js` file includes:

1. Mobile menu toggle functionality
2. Smooth scrolling for anchor links
3. Animation on scroll effects

## Browser Compatibility

The website is compatible with modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Credits

Created for Unbitable Cyber Security based on the provided template and content.

