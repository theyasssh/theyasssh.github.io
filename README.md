# Yash Khatri - Portfolio Website

A modern, animated portfolio website showcasing my work as an AI Engineer & Business Analyst. Built with pure HTML, CSS, and JavaScript - no frameworks required.

[![Live Demo](https://img.shields.io/badge/demo-live-brightgreen)](https://theyasssh.github.io)
[![HTML5](https://img.shields.io/badge/HTML-5-orange)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS-3-blue)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 🌟 Features

### Design & UX
- **Modern Dark Theme** - Sleek dark background with cyan accent colors
- **Smooth Animations** - Fade-in effects, scroll reveals, and interactive elements
- **Responsive Design** - Fully optimized for desktop, tablet, and mobile devices
- **Animated Project Cards** - Unique canvas animations for each project:
  - Neural network visualization
  - Wave bar animations
  - Scanning grid effects
  - Floating particle systems

### Sections
1. **Hero** - Eye-catching introduction with gradient name effect and call-to-action buttons
2. **About** - Personal story, statistics, and tech stack configuration
3. **Experience** - Professional work history with detailed descriptions
4. **Skills** - Technical proficiencies with animated progress bars
5. **Projects** - Portfolio of 4 major projects with live animations
6. **Research** - Current research interests and reading list
7. **Certifications** - Industry-recognized credentials
8. **Achievements** - Competition wins and academic excellence
9. **Education** - Academic background and qualifications
10. **Leadership** - Community service and organizational roles
11. **Contact** - Multiple ways to get in touch

### Interactive Elements
- Smooth scroll navigation
- Animated technology ticker
- Hover effects on cards and buttons
- Dynamic cursor glow effect
- Scroll-triggered reveals
- Mobile-friendly hamburger menu

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Custom properties, Flexbox, Grid, animations
- **JavaScript (ES6)** - DOM manipulation, IntersectionObserver API, Canvas API
- **Google Fonts** - Syne, Space Mono, Outfit typefaces

### No Dependencies
This website is built with vanilla web technologies - no frameworks, libraries, or build tools required. Just open `index.html` in a browser and it works!

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file (single-page application)
├── README.md          # This file
└── assets/            # (Optional) For additional resources
    └── images/        # Profile photos, project screenshots, etc.
```

## 🚀 Getting Started

### Option 1: View Locally
1. Download or clone the repository
2. Open `index.html` in your web browser
3. That's it! No installation or build process needed

### Option 2: Deploy to GitHub Pages
1. Create a new repository on GitHub
2. Upload `index.html` to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch" and choose `main` branch
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 3: Deploy to Netlify
1. Sign up at [Netlify](https://netlify.com)
2. Drag and drop `index.html` to Netlify's deploy zone
3. Get instant HTTPS hosting with custom domain support

### Option 4: Deploy to Vercel
1. Sign up at [Vercel](https://vercel.com)
2. Import your GitHub repository
3. Deploy with automatic HTTPS and CDN

## ⚙️ Customization Guide

### Updating Your Information

#### 1. Personal Details
```html
<!-- Line 6: Page title -->
<title>Your Name — Your Title</title>

<!-- Line 329: Navigation logo -->
<a href="#" class="nav-logo">Y<span>.</span>K</a>

<!-- Line 347-349: Hero section -->
<h1><span class="line">Your Name</span></h1>
<p class="hero-description">Your description here...</p>
```

#### 2. Contact Information
```html
<!-- Lines 725-729: Contact links -->
<a href="mailto:your.email@gmail.com">Email</a>
<a href="https://linkedin.com/in/yourusername">LinkedIn</a>
<a href="https://x.com/yourusername">Twitter</a>
<a href="tel:+1234567890">Phone</a>
<a href="https://github.com/yourusername">GitHub</a>
```

#### 3. Resume Download Link
```html
<!-- Line 356: Update Google Drive link -->
<a href="YOUR_RESUME_LINK" download>↓ Download Resume</a>
```

#### 4. Colors & Theme
```css
/* Lines 13-19: CSS variables */
:root {
  --bg-primary: #060611;      /* Main background */
  --accent: #00e5ff;          /* Primary accent color */
  --text-primary: #e8e8f0;    /* Main text color */
  /* Customize other colors as needed */
}
```

#### 5. Content Sections
Update the text in each section (`#about`, `#experience`, `#skills`, etc.) with your own:
- Work experience
- Projects
- Skills and proficiencies
- Certifications
- Achievements
- Education

### Adding New Projects

Find the projects section (around line 538) and copy this template:

```html
<div class="project-card reveal">
  <div class="project-banner banner-neural">
    <canvas id="yourCanvas"></canvas>
    <span class="project-banner-label">Your Category</span>
  </div>
  <div class="project-body">
    <div class="project-date">2024</div>
    <div class="project-title">Your Project Name</div>
    <div class="project-desc">Your project description...</div>
    <div class="project-tech">
      <span>Tech 1</span>
      <span>Tech 2</span>
    </div>
  </div>
</div>
```

## 🎨 Design System

### Color Palette
- **Primary Background:** `#060611` - Deep dark blue
- **Secondary Background:** `#0c0c1e` - Slightly lighter blue
- **Accent Cyan:** `#00e5ff` - Bright cyan for highlights
- **Accent Purple:** `#a855f7` - Purple for variety
- **Accent Warm:** `#ff6b35` - Orange for contrast
- **Text Primary:** `#e8e8f0` - Near white
- **Text Secondary:** `#8888a8` - Muted purple-gray

### Typography
- **Display Font:** Syne (800 weight) - For headings
- **Monospace Font:** Space Mono - For code and labels
- **Body Font:** Outfit (300-600 weight) - For paragraph text

### Spacing
- **Section Padding:** `7rem 3rem`
- **Card Padding:** `2.5rem - 3rem`
- **Gap Between Elements:** `1rem - 2rem`

## 🔧 Technical Features

### Animations
- **Canvas Animations:** Neural network nodes, particle systems
- **CSS Animations:** Fade-ins, slides, pulses, waves
- **IntersectionObserver:** Scroll-triggered reveals for performance

### Accessibility
- Semantic HTML5 elements
- ARIA labels on interactive elements
- Keyboard navigation support
- Reduced motion support (respects `prefers-reduced-motion`)

### Performance Optimizations
- Single HTML file - minimal HTTP requests
- Lazy animation initialization
- IntersectionObserver for efficient scroll tracking
- CSS transforms for hardware acceleration
- No external JavaScript libraries

### Browser Support
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

```css
/* Desktop: Default styles */

/* Tablet: max-width 1024px */
- Adjusted grid layouts
- Smaller section padding

/* Mobile: max-width 768px */
- Single column layouts
- Hamburger navigation menu
- Stacked buttons and cards

/* Small Mobile: max-width 480px */
- Further reduced text sizes
- Optimized touch targets
```

## 🤝 Contributing

While this is a personal portfolio, if you find bugs or have suggestions:
1. Open an issue describing the problem
2. Fork the repository
3. Create a feature branch
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Credits

**Design & Development:** Yash Khatri  
**Inspiration:** Modern portfolio design trends  
**Fonts:** Google Fonts (Syne, Space Mono, Outfit)  
**Icons:** Custom SVG icons

## 📞 Contact

- **Email:** iamyashkhatri.00@gmail.com
- **LinkedIn:** [linkedin.com/in/theyasssh](https://linkedin.com/in/theyasssh)
- **Twitter:** [x.com/theyasssh](https://x.com/theyasssh)
- **GitHub:** [github.com/theyasssh](https://github.com/theyasssh)

---

⭐ If you find this portfolio inspiring, please consider giving it a star!

**Built with ❤️ and lots of ☕ by Yash Khatri**
