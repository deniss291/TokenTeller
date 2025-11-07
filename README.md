# TokenTeller Website

A beautiful, minimal landing page and whitepaper for TokenTeller - an AI-powered cryptocurrency token analysis service.

## 🎨 Design Features

- **Clean & Minimal**: Simple, elegant design that focuses on content
- **Navy Blue & Orange Color Scheme**: Professional colors representing trust and energy
- **Eagle Logo**: Symbolizing vision, precision, and intelligence
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Subtle animations enhance user experience
- **Professional Typography**: Inter font family for excellent readability

## 📁 File Structure

```
website/
├── index.html          # Main landing page
├── whitepaper.html     # Comprehensive whitepaper
├── styles.css          # Main stylesheet
├── whitepaper.css      # Whitepaper-specific styles
├── script.js           # Interactive features
└── README.md           # This file
```

## 🚀 Getting Started

### Option 1: Direct File Opening

Simply open `index.html` in any modern web browser:

```bash
open index.html
```

### Option 2: Local Web Server (Recommended)

For better performance and to avoid CORS issues:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (npx)
npx serve

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## 📄 Page Structure

### Landing Page (index.html)

1. **Navigation**: Fixed top navigation with smooth scroll
2. **Hero Section**: Eye-catching introduction with animated cards
3. **Features Section**: Six key features with icons
4. **How It Works**: Three-step process visualization
5. **Technology Section**: Tech stack showcase
6. **Analysis Example**: Sample analysis report
7. **CTA Section**: Call-to-action for whitepaper
8. **Footer**: Links and branding

### Whitepaper (whitepaper.html)

1. **Hero Section**: Title and metadata
2. **Table of Contents**: Quick navigation to sections
3. **11 Comprehensive Sections**:
   - Abstract
   - Introduction
   - The Problem
   - Our Solution
   - Technical Architecture
   - Analysis Framework
   - AI Integration
   - Virtuals Protocol Integration
   - Use Cases
   - Roadmap
   - Conclusion
4. **References**: Academic-style citations

## 🎨 Color Palette

```css
--navy: #0A1F44          /* Primary brand color */
--navy-light: #1a3a66    /* Hover states */
--navy-dark: #05142b     /* Accents */
--orange: #FF6B35        /* Call-to-action */
--orange-light: #ff8555  /* Hover states */
--orange-dark: #e55525   /* Active states */
--white: #FFFFFF         /* Background */
--gray-light: #F5F7FA    /* Sections */
--gray: #8B95A5          /* Secondary text */
--gray-dark: #4A5568     /* Body text */
```

## ✨ Features

### Interactive Elements

- Smooth scroll navigation
- Hover animations on cards and buttons
- Floating card animations in hero section
- Fade-in animations on scroll
- Number counter animations
- Responsive mobile menu

### Responsive Breakpoints

- Desktop: > 968px
- Tablet: 640px - 968px
- Mobile: < 640px

### Accessibility

- Semantic HTML5 structure
- Proper heading hierarchy
- Alt text ready for images
- Keyboard navigation support
- High contrast text
- Readable font sizes

## 🖼️ Logo & Branding

The eagle logo is implemented as an inline SVG with:
- Orange color (#FF6B35)
- Clean, geometric design
- Scalable vector format
- White accent detail (eye)

## 🔧 Customization

### Changing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --navy: #YourColor;
    --orange: #YourColor;
    /* ... other colors */
}
```

### Updating Content

All content is in the HTML files. Update text directly in:
- `index.html` for landing page content
- `whitepaper.html` for whitepaper content

### Modifying Animations

Animation settings are in `script.js`. Adjust:
- Animation duration
- Intersection observer thresholds
- Scroll behavior

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🚢 Deployment

### GitHub Pages

1. Push to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select main branch / docs folder
4. Access at `https://yourusername.github.io/repository-name`

### Netlify

1. Drag and drop the `website` folder to Netlify
2. Or connect your GitHub repository
3. Automatic deployment on push

### Vercel

```bash
vercel deploy
```

## 📋 SEO Optimization

To optimize for search engines, add:

1. Meta description in `<head>`:
```html
<meta name="description" content="Your description">
```

2. Open Graph tags:
```html
<meta property="og:title" content="TokenTeller">
<meta property="og:description" content="AI-Powered Token Analysis">
<meta property="og:image" content="path-to-image.jpg">
```

3. Twitter Card tags:
```html
<meta name="twitter:card" content="summary_large_image">
```

## 📝 License

This website is part of the TokenTeller project.

## 🤝 Contributing

To improve the website:

1. Make changes to HTML/CSS/JS files
2. Test responsiveness on multiple devices
3. Ensure all links work correctly
4. Validate HTML at https://validator.w3.org/
5. Test accessibility at https://wave.webaim.org/

## 📞 Support

For questions or issues related to the website, please refer to the main TokenTeller project repository.

---

**Built with ❤️ for the TokenTeller community**

