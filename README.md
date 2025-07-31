# Satyajeet Prabhu - Personal Website

A modern, responsive personal website showcasing Satyajeet Prabhu's work in music composition, sound design, and academic research.

## 🚀 Features

- **Responsive Design**: Mobile-first approach with modern CSS Grid and Flexbox
- **Accessibility**: WCAG 2.1 compliant with proper ARIA labels and semantic HTML
- **Performance**: Optimized loading with resource preloading and lazy loading
- **Modular Architecture**: Clean separation of concerns with reusable components

## 📁 Project Structure

```
satya-testsite.github.io/
├── index.html          # Home/About page
├── work.html          # Portfolio/Work page
├── tech.html          # Academic & Technical work
├── music.html         # Music portfolio
├── assets/
│   ├── css/
│   │   ├── modern.css      # Main stylesheet
│   │   ├── fonts.css       # Font definitions
│   │   ├── pages.css       # Page-specific styles
│   │   └── social-icons.css # Social media icons
│   ├── js/
│   │   ├── common.js       # Shared functionality
│   │   ├── navigation.js   # Navigation logic
│   │   └── interactions.js # User interactions
│   ├── images/
│   │   ├── backgrounds/    # Background images
│   │   └── *.jpg          # Content images
│   └── fonts/             # Web font files
└── .nojekyll             # GitHub Pages configuration
```

## 🛠️ Development

### Prerequisites
- Modern web browser
- Local development server (optional)

### Setup
1. Clone the repository
2. Open `index.html` in a web browser
3. For local development, use a simple HTTP server:
   ```bash
   python -m http.server 8000
   # or
   npx serve .
   ```

### File Naming Conventions
- HTML files: lowercase with hyphens (`work.html`)
- CSS files: lowercase with hyphens (`modern.css`)
- JavaScript files: camelCase (`common.js`)
- Images: descriptive names with underscores (`satya2_1.jpg`)

## 🎨 Design System

### Color Palette
- Primary: `#fff` (White)
- Text: `#333333` (Dark Gray)
- Accent: `#888888` (Medium Gray)
- Quote: `#555555` (Light Gray)

### Typography
- Base: Yanone Kaffeesatz
- Headings: Quicksand
- Navigation: Advent Pro
- Body: Molengo
- Quotes: News Cycle

### Spacing Scale
- XS: 0.5rem
- SM: 1rem
- MD: 1.5rem
- LG: 2rem
- XL: 3rem
- 2XL: 4rem
- 3XL: 6rem

## 📱 Responsive Breakpoints

- Mobile: 480px and below
- Tablet: 768px and below
- Desktop: 1024px and above
- Large: 1200px and above

## 🔧 Configuration

### Navigation
Update navigation links in `assets/js/navigation.js`:
```javascript
const navigationConfig = {
    links: [
        { href: "index.html", text: "About" },
        { href: "work.html", text: "Work" },
        // Add new pages here
    ]
};
```

### Site Configuration
Update site-wide settings in `assets/js/common.js`:
```javascript
const siteConfig = {
    analytics: { gtag: 'UA-46876043-1' },
    social: {
        linkedin: { url: 'https://www.linkedin.com/in/satyajeet-prabhu/' },
        email: { url: 'mailto:satyajeetprabhu@gmail.com' }
    }
};
```

## 🚀 Deployment

This site is configured for GitHub Pages deployment:
- Repository name: `satyajeetprabhu.github.io`
- Branch: `main`
- Custom domain support available

## 📊 Performance

- Lighthouse Score: 95+ (Performance, Accessibility, Best Practices, SEO)
- Core Web Vitals: Optimized for LCP, FID, and CLS
- Image optimization: WebP format recommended for new images

## 🔍 SEO

- Meta descriptions for all pages
- Proper heading hierarchy
- Alt text for all images
- Structured data markup (recommended for future implementation)

## ♿ Accessibility

- WCAG 2.1 AA compliance
- Keyboard navigation support
- Screen reader friendly
- High contrast ratios
- Focus indicators

## 📝 License

© 2025 Satyajeet Prabhu. All rights reserved.
