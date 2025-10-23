# Portfolio - Lam Tan Thinh

Modern dark-themed portfolio website showcasing front-end development and HTML banner design projects.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 👨‍💻 About

**Name:** Lam Tan Thinh
**Role:** HTML Banner Designer & Front-End Developer
**Education:** Computer Science (2021-2025) - Ho Chi Minh City University of Technology
**Email:** tanthinhvnex@gmail.com
**GitHub:** [@tanthinhvnex](https://github.com/tanthinhvnex)

## ✨ Features

### Design & UX
- 🌙 **Dark Mode Theme** - Sleek dark interface with pastel blue accents
- 🎨 **Animated Hero Banner** - Gradient orbs, floating shapes, morphing blobs, and particle effects
- 💫 **Smooth Animations** - Fade-in effects, hover transitions, and scroll animations
- 📱 **Fully Responsive** - Mobile-first design with hamburger menu

### Technical Features
- ⚡ **Live Project Previews** - Embedded iframes showing real GitHub Pages
- 🔗 **Direct Links** - Live Demo and GitHub repository buttons for each project
- 🎯 **Performance Optimized** - Lazy loading iframes, CSS animations with GPU acceleration
- 🎭 **Interactive Elements** - Hover effects, smooth scrolling, active link highlighting

## 📁 Project Structure

```
fe-portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styles (dark theme, animations, responsive)
├── script.js           # JavaScript (particles, navigation, interactions)
├── images/             # Project screenshots (optional)
│   └── README.md       # Screenshot guide
└── README.md           # This file
```

## 🎨 Color Scheme

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

## 🚀 Featured Projects

### Landing Pages (4 projects)
1. **Real Estate Landing Page** - [Live](https://tanthinhvnex.github.io/landing-page-real-estate/) | [Code](https://github.com/tanthinhvnex/landing-page-real-estate)
2. **Online Courses Landing Page** - [Live](https://tanthinhvnex.github.io/online-courses-landing-page/) | [Code](https://github.com/tanthinhvnex/online-courses-landing-page)
3. **Dental Clinic Landing Page** - [Live](https://tanthinhvnex.github.io/dental-clinic-landing-page/) | [Code](https://github.com/tanthinhvnex/dental-clinic-landing-page)
4. **Pet Care Service Landing Page** - [Live](https://tanthinhvnex.github.io/pet-care-service-landing-page/) | [Code](https://github.com/tanthinhvnex/pet-care-service-landing-page)

### Full-Stack Web Applications (Coming Soon)
- Web Application 1
- Web Application 2

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Grid, Flexbox, Animations, Custom Properties
- **JavaScript (ES6+)** - Canvas API, Intersection Observer, DOM Manipulation
- **Font Awesome 6.4.0** - Icons
- **GitHub Pages** - Hosting

## 📦 Installation & Setup

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/tanthinhvnex/fe-portfolio.git
   cd fe-portfolio
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   # Or use Live Server extension in VS Code
   ```

### Deploy to GitHub Pages

1. **Create a new repository** named `[username].github.io`

2. **Push your code**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Portfolio website"
   git branch -M main
   git remote add origin https://github.com/tanthinhvnex/tanthinhvnex.github.io.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to Settings → Pages
   - Source: `main` branch, `/ (root)` folder
   - Save and wait 2-3 minutes
   - Visit: `https://[username].github.io`

## ⚙️ Customization Guide

### Update Personal Information

**Contact Details** (index.html line ~291-299):
```html
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="tel:+84867177379">0867 177 379</a>
<a href="https://github.com/yourusername">github.com/yourusername</a>
<a href="https://linkedin.com/in/yourprofile">linkedin.com/in/yourprofile</a>
```

### Add New Project

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

## 🎯 Performance Features

- **Lazy Loading** - iframes load only when scrolled into view
- **CSS Animations** - Hardware-accelerated with `transform` and `opacity`
- **Particle System** - Canvas-based with optimized rendering
- **Responsive Images** - Proper sizing for different devices

## 📱 Responsive Breakpoints

```css
/* Mobile */
@media (max-width: 480px) { }

/* Tablet */
@media (max-width: 768px) { }

/* Desktop */
Default styles
```

## 🎭 Animation Effects

### Hero Banner
- Gradient Orbs (3 layers)
- Floating Shapes
- Morphing Blob
- Particle Network (Canvas)
- Animated Title Gradient

### Interactions
- Hover scale on project cards
- Smooth scroll navigation
- Fade-in on scroll (Intersection Observer)
- Active link highlighting

## 📝 To-Do List

- [ ] Add 2 Full-Stack Web Application projects
- [ ] Implement dark/light mode toggle (optional)
- [ ] Add project screenshots as fallback for iframes
- [ ] Integrate contact form with backend (EmailJS/Formspre)
- [ ] Add Google Analytics
- [ ] Create blog section
- [ ] Add testimonials section

## 🤝 Contributing

This is a personal portfolio, but feel free to fork and customize for your own use!

## 📄 License

MIT License - Free to use for personal portfolios

## 🔗 Links

- **Portfolio:** https://tanthinhvnex.github.io
- **GitHub:** https://github.com/tanthinhvnex
- **LinkedIn:** https://www.linkedin.com/in/thinh-lam-a7b7361a7/
- **Facebook:** https://www.facebook.com/tanthinhvnex/

---

**Built with ❤️ by Lam Tan Thinh** | 2025
