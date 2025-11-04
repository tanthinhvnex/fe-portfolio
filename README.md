# Portfolio - Lam Tan Thinh

Modern dark-themed portfolio website showcasing full-stack web development projects and landing pages.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## About

**Name:** Lam Tan Thinh
**Role:** Fresher Full-Stack Web Developer
**Education:** Computer Science (2021-2025) - Ho Chi Minh City University of Technology (HCMUT - Bach Khoa)
**High School:** Nguyen Thien Thanh Gifted High School (2018-2021) - Physics Specialization, Tra Vinh
**Email:** tanthinhvnex@gmail.com
**GitHub:** [@tanthinhvnex](https://github.com/tanthinhvnex)

## Features

### Design & UX
- **Dark Mode Theme** - Sleek dark interface with pastel blue accents
- **Animated Hero Banner** - Gradient orbs, floating shapes, morphing blobs, and particle effects
- **Smooth Animations** - Fade-in effects, hover transitions, and scroll animations
- **Fully Responsive** - Mobile-first design with hamburger menu

### Technical Features
- **Image Carousels** - Interactive carousels for full-stack project screenshots with navigation and indicators
- **Live Project Previews** - Embedded iframes showing real GitHub Pages for landing pages
- **Direct Links** - Live Demo and GitHub repository buttons for each project
- **Performance Optimized** - Lazy loading iframes, CSS animations with GPU acceleration
- **Interactive Elements** - Hover effects, smooth scrolling, active link highlighting
- **Portfolio Switcher** - Link to Data Analyst/Business Intelligence portfolio

## Project Structure

```
dev-portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styles (dark theme, animations, responsive)
├── script.js           # JavaScript (particles, navigation, carousel, interactions)
├── grocery_coffee/     # Coffee shop project screenshots
├── shoes_store/        # Shoes store project screenshots
├── smart_farm/         # Smart farm IoT project screenshots
├── green_garden/       # Green garden project screenshots
└── README.md           # This file
```

## Color Scheme

```css
/* Pastel Blue Theme */
--primary-color: #60a5fa;     /* Light Blue */
--secondary-color: #3b82f6;   /* Medium Blue */
--accent-color: #93c5fd;      /* Pastel Blue */

/* Dark Background */
--bg-color: #0a0a0f;          /* Deep Black */
--bg-light: #18181b;          /* Dark Gray */
--bg-card: #1c1c21;           /* Card Background */
```

## Featured Projects

### Full-Stack Web Applications (4 projects)
1. **Coffee Shop E-commerce** - Full-stack grocery e-commerce website specialized in coffee products. Features responsive design, dark/light mode toggle, shopping cart, checkout system, and user profile management. [GitHub](https://github.com/tanthinhvnex/LTWeb)
2. **Shoes Store E-commerce** - Full-stack e-commerce platform for shoes and footwear. Features product browsing, shopping cart, user authentication, admin dashboard, and warehouse management. [GitHub](https://github.com/tanthinhvnex/shoes-store)
3. **Smart Farm IoT System** - IoT-based smart agriculture system for monitoring and controlling environmental factors. Features real-time monitoring of temperature, humidity, and light; automatic/manual control of devices. Private repository - contact for access.
4. **Green Garden E-commerce** - Full-stack e-commerce platform specialized in ornamental plants and gardening products. Features product catalog, shopping cart, secure payment system. Private repository - contact for access.

### Landing Pages (4 projects)
1. **Real Estate Landing Page** - [Live](https://tanthinhvnex.github.io/landing-page-real-estate/) | [Code](https://github.com/tanthinhvnex/landing-page-real-estate)
2. **Online Courses Landing Page** - [Live](https://tanthinhvnex.github.io/online-courses-landing-page/) | [Code](https://github.com/tanthinhvnex/online-courses-landing-page)
3. **Dental Clinic Landing Page** - [Live](https://tanthinhvnex.github.io/dental-clinic-landing-page/) | [Code](https://github.com/tanthinhvnex/dental-clinic-landing-page)
4. **Pet Care Service Landing Page** - [Live](https://tanthinhvnex.github.io/pet-care-service-landing-page/) | [Code](https://github.com/tanthinhvnex/pet-care-service-landing-page)

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Grid, Flexbox, Animations, Custom Properties
- **JavaScript (ES6+)** - Canvas API, Intersection Observer, DOM Manipulation
- **Font Awesome 6.4.0** - Icons
- **GitHub Pages** - Hosting

## Installation & Setup

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/tanthinhvnex/dev-portfolio.git
   cd dev-portfolio
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   # Or use Live Server extension in VS Code
   ```

### Deploy to GitHub Pages

1. **Create a new repository** named `dev-portfolio`

2. **Push your code**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Developer Portfolio website"
   git branch -M main
   git remote add origin https://github.com/tanthinhvnex/dev-portfolio.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Source: `main` branch, `/ (root)` folder
   - Save and wait 2-3 minutes
   - Visit: `https://tanthinhvnex.github.io/dev-portfolio/`

## Customization Guide

### Update Personal Information

**Hero Section** (index.html line ~37-39):
```html
<h1 class="hero-title">YOUR NAME</h1>
<p class="hero-subtitle">Your Role</p>
<p class="hero-description">Your specialization description</p>
```

**Contact Details** (index.html line ~543-564):
```html
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="tel:+1234567890">Your Phone</a>
<a href="https://github.com/yourusername">github.com/yourusername</a>
<a href="https://linkedin.com/in/yourprofile">linkedin.com/in/yourprofile</a>
```

### Add New Full-Stack Project with Carousel

```html
<div class="project-card fullstack-card">
    <div class="project-carousel">
        <div class="carousel-container">
            <div class="carousel-slides">
                <div class="carousel-slide active">
                    <img src="path/to/screenshot1.png" alt="Description">
                    <div class="carousel-caption">Screenshot Title</div>
                </div>
                <!-- Add more slides -->
            </div>
            <button class="carousel-btn carousel-prev">
                <i class="fas fa-chevron-left"></i>
            </button>
            <button class="carousel-btn carousel-next">
                <i class="fas fa-chevron-right"></i>
            </button>
        </div>
        <div class="carousel-indicators"></div>
    </div>
    <div class="project-info">
        <h4>Project Name</h4>
        <p>Project description...</p>
        <div class="project-note-with-btn">
            <div class="project-note">
                <i class="fas fa-info-circle"></i>
                <span>Additional info or instructions</span>
            </div>
            <a href="https://github.com/username/repo" target="_blank"
               class="project-btn project-btn-github project-btn-inline">
                <i class="fab fa-github"></i> GitHub
            </a>
        </div>
    </div>
</div>
```

### Add New Landing Page Project

```html
<div class="project-card">
    <div class="project-image">
        <iframe
            src="https://yourusername.github.io/project-name/"
            frameborder="0"
            scrolling="no"
            loading="lazy"
            title="Project Preview"></iframe>
        <div class="project-overlay">
            <a href="https://yourusername.github.io/project-name/" class="project-link" target="_blank">
                <i class="fas fa-external-link-alt"></i>
            </a>
        </div>
    </div>
    <div class="project-info">
        <h4>Project Name</h4>
        <p>Project description here...</p>
        <div class="project-links">
            <a href="https://yourusername.github.io/project-name/" target="_blank" class="project-btn">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="https://github.com/yourusername/project-name" target="_blank" class="project-btn project-btn-github">
                <i class="fab fa-github"></i> GitHub
            </a>
        </div>
    </div>
</div>
```

### Customize Colors

Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #60a5fa;      /* Change to your brand color */
    --secondary-color: #3b82f6;
    --accent-color: #93c5fd;
}
```

## Performance Features

- **Lazy Loading** - iframes load only when scrolled into view
- **CSS Animations** - Hardware-accelerated with `transform` and `opacity`
- **Particle System** - Canvas-based with optimized rendering
- **Responsive Images** - Proper sizing for different devices

## Responsive Breakpoints

```css
/* Mobile */
@media (max-width: 480px) { }

/* Tablet */
@media (max-width: 768px) { }

/* Desktop */
Default styles
```

## Animation Effects

### Hero Banner
- Gradient Orbs (3 layers)
- Floating Shapes
- Morphing Blob
- Particle Network (Canvas)
- Animated Title Gradient

### Interactions
- Hover scale on project cards
- Carousel navigation (prev/next buttons, indicators)
- Portfolio switcher with hover effects
- Smooth scroll navigation
- Fade-in on scroll (Intersection Observer)
- Active link highlighting

### Statistics
- **8+** Completed Projects (4 Full-Stack Apps + 4 Landing Pages)
- **4** Landing Pages
- **4** Full-Stack Web Applications

## Other Portfolios

This portfolio showcases my work as a **Developer**. For my other expertise:

- **Data Analyst/Business Intelligence Portfolio**: [View Portfolio](https://tanthinhvnex.github.io/data-analyst-portfolio/)
  - Data analysis projects
  - Business intelligence dashboards
  - Insights and visualizations

## Skills Showcase

- **HTML5** - Semantic HTML, SEO optimization, Accessibility
- **CSS3** - Flexbox, Grid, Animation, Responsive Design
- **JavaScript** - ES6+, DOM Manipulation, Interactive UI
- **Responsive Design** - Responsive Layouts & Cross-Browser Compatibility
- **Web Development** - Full-Stack Development, API Integration, Database Design
- **Version Control** - GitHub, Branching, Commit Workflow, Merge & Collaboration

## Links

- **Developer Portfolio:** https://tanthinhvnex.github.io/dev-portfolio/
- **Data Analyst Portfolio:** https://tanthinhvnex.github.io/data-analyst-portfolio/
- **GitHub:** https://github.com/tanthinhvnex
- **LinkedIn:** https://www.linkedin.com/in/thinh-lam-a7b7361a7/
- **Facebook:** https://www.facebook.com/tanthinhvnex/
- **Email:** tanthinhvnex@gmail.com
- **Phone:** 0867 177 379

---

**Built with by Lam Tan Thinh** | 2025
