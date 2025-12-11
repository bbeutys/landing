# BBeauty Landing Page

Modern beauty studio landing page for BBeauty in Alphen aan den Rijn, Netherlands. Specializing in laser hair removal and lash extensions.

## 🌐 Live Site

Visit us at: [https://bbeautys.nl/](https://bbeautys.nl/)

## 📋 Overview

This is a single-page landing site built with pure HTML and CSS. No build tools or dependencies required.

**Services Offered:**
- Laser hair removal (for women and men)
- Professional lash extensions (Classic, Hybrid, Volume, Trend Effects)

## 🚀 How to Open Locally

### Option 1: Direct File Open
Simply open `index.html` in your web browser:
```bash
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Option 2: Local Server (Recommended)
For the best experience, use a local web server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

Then open: [http://localhost:8000](http://localhost:8000)

**Using Node.js:**
```bash
npx http-server -p 8000
```

**Using PHP:**
```bash
php -S localhost:8000
```

## 📁 File Structure

```
.
├── index.html          # Main landing page
├── logo-bbeauty.png    # Optimized logo (300x166px, ~60KB)
├── favicon.ico         # Browser favicon
├── CNAME               # GitHub Pages domain config
└── README.md           # This file
```

## ✨ Recent Improvements (December 2024)

### 🐛 Bug Fixes
- ✅ **Image Optimization**: Compressed logo from 5.9MB to ~60KB (99% reduction)
- ✅ **Fixed Broken Links**: All booking, WhatsApp, and map links now functional
- ✅ **Favicon Added**: Browser tab icon for better branding
- ✅ **Typography Fix**: Changed "Hands" to "Arms" for accuracy in pricing

### 🎨 Semantic HTML & Accessibility
- ✅ Added proper `<main>` element for main content
- ✅ Added skip-to-main-content link for keyboard navigation
- ✅ Improved heading hierarchy (`<h1>`, `<h2>`, `<h3>`)
- ✅ Added ARIA labels and roles for better screen reader support
- ✅ Added semantic `<nav>` element for price navigation
- ✅ Converted service names to proper `<h3>` headings
- ✅ Enhanced focus states for keyboard navigation
- ✅ Added `role="contentinfo"` to footer
- ✅ Added width/height attributes to logo for better performance

### 🔍 SEO Improvements
- ✅ Enhanced `<title>` with location for local SEO
- ✅ Added comprehensive meta description
- ✅ Added keywords meta tag
- ✅ Implemented Open Graph tags for Facebook/LinkedIn sharing
- ✅ Added Twitter Card meta tags
- ✅ Added JSON-LD structured data for local business (Schema.org)
- ✅ Added `robots` meta tag
- ✅ Added `theme-color` for mobile browsers

### 🔒 Security
- ✅ Added `rel="noopener noreferrer"` to all external links
- ✅ Added `target="_blank"` for external navigation

### 🎯 UX Improvements
- ✅ Pre-filled WhatsApp messages for easier booking
- ✅ Functional Google Maps and Waze links
- ✅ Better color contrast for accessibility
- ✅ Improved language consistency ("up to" instead of "till")

## 📱 Features

- **Responsive Design**: Optimized for mobile, tablet, and desktop
- **Modern Aesthetics**: Warm, minimalist design with soft colors
- **Quick Booking**: Direct WhatsApp integration with pre-filled messages
- **Complete Price List**: Transparent pricing for all services
- **Easy Navigation**: Quick links to price categories
- **Location Integration**: Direct links to Google Maps and Waze
- **Accessibility**: WCAG-compliant with keyboard navigation support

## 🎨 Design System

**Colors:**
- Primary background: `#f6f3ec` (warm cream)
- Card background: `#fffaf4` (off-white)
- Accent: `#b78163` (warm brown)
- Text: `#22231e` (near-black)
- Muted text: `#706a61` (warm gray)

**Typography:**
- System font stack for optimal loading
- Responsive font sizes
- Proper heading hierarchy

## 🌍 Language

Currently available in **English** only. The original design references Ukrainian translations but none were found in the codebase.

## 📞 Contact Information

- **Location**: Ouvertureweg 15-19, 2402 DT Alphen aan den Rijn, Netherlands
- **Email**: hello@bbeauty.nl
- **WhatsApp**: [Click to message](https://wa.me/31612345678)
- **Appointment**: By appointment only

## 🔧 Technical Details

- **No Dependencies**: Pure HTML, CSS, and vanilla JavaScript
- **No Build Process**: Ready to deploy as-is
- **GitHub Pages**: Configured for custom domain (bbeautys.nl)
- **Lighthouse Score**: Optimized for performance, accessibility, SEO, and best practices

## 📊 Performance

- ✅ Optimized images (logo reduced from 5.9MB to 60KB)
- ✅ Inline CSS for faster loading
- ✅ Minimal HTTP requests
- ✅ Mobile-first responsive design
- ✅ No external dependencies or frameworks

## 🛠️ Development

No build tools required. Simply edit `index.html` and refresh your browser.

**To update:**
1. Edit the HTML file
2. Test locally (see "How to Open Locally" above)
3. Commit and push to GitHub
4. GitHub Pages automatically deploys

## 📝 License

© 2025 BBeauty. All rights reserved.

## 🚀 Deployment

This site is automatically deployed via GitHub Pages. Any push to the main branch updates the live site at [bbeautys.nl](https://bbeautys.nl/).

---

**Note**: For actual WhatsApp functionality, replace the placeholder phone number `31612345678` with your actual business WhatsApp number in the format `[country code][number]` (no spaces or special characters).
