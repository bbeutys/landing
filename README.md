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

## ✨ Recent Improvements (December 2025)

### 🌍 New Features (Latest Update)
- ✅ **Refined Typography**: Elegant Google Fonts (Cormorant for headings, Inter for body text) with fallback stacks
- ✅ **Improved Ukrainian Translation**: Natural phrasing with "Всі ноги" (All legs) instead of "Повні ноги", consistent use of "Усе" vs "Все"
- ✅ **Correct WhatsApp Number**: Updated to +31633915100 across all 8+ booking links
- ✅ **Better Text Logic**: Changed "Full Price List" to "Service Prices", "Full" to "Complete" for clarity
- ✅ **Enhanced Button States**: Improved hover/focus/active states with visual feedback and box shadows
- ✅ **Better Centering**: Fixed button and navigation alignment issues
- ✅ **Subtle Background Design**: Integrated existing images as decorative watermarks (back.png, mini-icon.png)
- ✅ **Mobile-First Responsive**: Enhanced touch targets (44-48px min), better spacing, optimized for all screen sizes
- ✅ **Ukrainian Language Support**: Full Ukrainian translation with language switcher (🇬🇧/🇺🇦)
- ✅ **Language Persistence**: Selected language saved in localStorage
- ✅ **Sectional Price List**: Category-based price display with Bundles shown by default
- ✅ **Smooth Animations**: Fade-in effects on scroll with prefers-reduced-motion support
- ✅ **Updated Map Links**: Google Maps and Waze links with correct address

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
- Accent: `#b78163` (warm brown/terracotta)
- Text: `#22231e` (near-black)
- Muted text: `#706a61` (warm gray)

**Typography:**
- Headings: Cormorant (serif, elegant)
- Body: Inter (sans-serif, readable)
- System font fallbacks for optimal loading
- Responsive font sizes
- Proper heading hierarchy

**Visual Design:**
- Subtle background textures using existing images
- Minimalist aesthetic with warm tones
- Decorative watermark elements
- Smooth transitions and hover effects

## 🌍 Language

Currently available in **English** and **Ukrainian** (Українська). 

- Language switcher in the header (🇬🇧/🇺🇦)
- Selected language persists across page visits (localStorage)
- Default language: English

## 📞 Contact Information

- **Location**: Ouvertureweg 15 - 19, 2402 DT Alphen aan den Rijn, Netherlands
- **Email**: hello@bbeauty.nl
- **WhatsApp**: [+31 6 33915100](https://wa.me/31633915100)
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

## 🎯 Features Implemented

### Language Switcher
- **Dual Language Support**: English and Ukrainian with flag emoji buttons (🇬🇧/🇺🇦)
- **Instant Translation**: All content translates immediately on language switch
- **Persistent Selection**: User's language choice saved in localStorage
- **Full Coverage**: All sections translated including hero, services, prices, contact

### Price List Categories
- **Category Filtering**: Buttons to filter prices by category
- **Default View**: Bundles (Best Value) shown by default
- **Categories**:
  - Bundles (Combo packages)
  - Women · Body & Bikini
  - Women · Face & Mini
  - Men Only · Laser
  - Lash Extensions
- **Active State**: Clear visual indication of selected category

### Animations
- **Fade-in on Scroll**: Sections smoothly appear as user scrolls
- **Hover Transitions**: Smooth button and link hover effects
- **Smooth Scrolling**: Native smooth scroll for anchor links
- **Accessibility**: Respects `prefers-reduced-motion` for users who prefer reduced animations

### Mobile Optimization
- **Touch-Friendly**: All buttons meet 44px minimum touch target size
- **Responsive Layout**: Optimized for iPhone, Android, and tablets
- **No Horizontal Scroll**: Content fits viewport on all screen sizes
- **Stacked Layout**: Single-column layout on mobile for better readability
- **Readable Text**: Font sizes adjusted for mobile viewing

## 📝 License

© 2025 BBeauty. All rights reserved.

## 🚀 Deployment

This site is automatically deployed via GitHub Pages. Any push to the main branch updates the live site at [bbeautys.nl](https://bbeautys.nl/).
