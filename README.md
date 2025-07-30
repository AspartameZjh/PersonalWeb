# Futuristic Personal Portfolio Website

A modern, responsive personal portfolio website with a cosmic theme and dark/light mode toggle. Built with HTML5, CSS3, and vanilla JavaScript.

## 🌟 Features

### Design & Theme
- **Futuristic Cosmic Design**: Dark blues, purples, and neon accents
- **Dark/Light Theme Toggle**: Smooth transitions between themes
- **Responsive Design**: Works perfectly on all devices
- **Modern Typography**: Orbitron for headers, Rajdhani for body text

### Interactive Elements
- **Animated Background**: Twinkling stars and floating planets
- **Smooth Scrolling**: Navigation with smooth section transitions
- **Hover Effects**: Interactive cards and buttons with animations
- **Typing Animation**: Hero title with typewriter effect
- **Particle Effects**: Dynamic particles in the hero section

### Sections
- **Homepage**: Hero section with animated elements
- **Resume**: Professional layout for skills, experience, and education
- **Projects**: Grid-based project showcase with tech tags
- **Contact**: Contact information with hover effects

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation
1. Download or clone the repository
2. Open `index.html` in your web browser
3. The website should load with the dark theme by default

### File Structure
```
Personal Web 2/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and theme variables
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎨 Customization Guide

### Personal Information
Edit the following in `index.html`:

1. **Page Title**: Change `<title>Your Name - Personal Portfolio</title>`
2. **Hero Section**: Update name, role, and description
3. **Resume Section**: Modify skills, experience, and education
4. **Projects Section**: Add your own projects with descriptions
5. **Contact Section**: Update contact information

### Colors & Theme
The color scheme is defined in CSS variables in `styles.css`:

```css
:root {
    --bg-primary: #0a0a0f;        /* Main background */
    --bg-secondary: #1a1a2e;      /* Secondary background */
    --accent-primary: #00d4ff;    /* Primary accent (cyan) */
    --accent-secondary: #ff6b6b;  /* Secondary accent (coral) */
    --accent-tertiary: #4ecdc4;   /* Tertiary accent (teal) */
}
```

### Fonts
The website uses Google Fonts:
- **Orbitron**: For headings and titles
- **Rajdhani**: For body text and descriptions

### Adding Projects
To add a new project, copy this structure in the projects section:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-placeholder"></div>
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">
            Your project description here.
        </p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Live Demo</a>
        </div>
    </div>
</div>
```

## 🌙 Theme Toggle

The theme toggle is located in the top-right corner of the navigation bar. It features:
- **Sun/Moon Icons**: Visual indication of current theme
- **Smooth Transitions**: All elements transition smoothly
- **Local Storage**: Theme preference is saved and remembered

## 📱 Responsive Design

The website is fully responsive and includes:
- **Mobile-First Approach**: Optimized for mobile devices
- **Flexible Grids**: Projects and resume sections adapt to screen size
- **Touch-Friendly**: Optimized for touch interactions
- **Readable Typography**: Font sizes adjust for different screens

## ⚡ Performance Features

- **Optimized Animations**: Smooth 60fps animations
- **Throttled Scroll Events**: Performance-optimized scrolling
- **Intersection Observer**: Efficient element animations
- **Minimal Dependencies**: Only uses Font Awesome for icons

## 🎯 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 🔧 Advanced Customization

### Adding New Sections
1. Add the HTML structure in `index.html`
2. Add corresponding CSS styles in `styles.css`
3. Add any JavaScript functionality in `script.js`

### Modifying Animations
Animations are defined in CSS using `@keyframes`. Key animations include:
- `twinkle`: Star background animation
- `float`: Planet and element floating
- `pulse`: Logo glow effect
- `ripple-animation`: Button click effects

### Custom JavaScript Features
The JavaScript includes:
- Theme toggle with localStorage
- Smooth scrolling navigation
- Intersection Observer for animations
- Parallax effects
- Typing animation
- Particle system

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you make improvements, consider sharing them!

## 📞 Support

If you need help customizing the website or have questions, feel free to reach out!

---

**Enjoy your new futuristic portfolio website! 🚀** 