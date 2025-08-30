# My Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and mobile-first responsive layout.

## 🚀 Features

- **Responsive Design**: Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Smooth scrolling, hover effects, and form validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **Smooth Animations**: CSS animations and JavaScript-powered interactions
- **SEO Friendly**: Semantic HTML structure
- **Fast Loading**: Optimized CSS and JavaScript

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Download/Clone**: Save all files to your local machine
2. **Open**: Double-click `index.html` or open it in your web browser
3. **Customize**: Edit the content to match your information
4. **Deploy**: Upload to any web hosting service (GitHub Pages, Netlify, Vercel, etc.)

## ✏️ Customization Guide

### Personal Information

Edit the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Sandeep Hasantha</span>
</h1>
<p class="hero-subtitle">Full Stack Developer & Designer</p>
```

#### About Section
```html
<p>I'm a passionate developer with a love for creating meaningful digital experiences...</p>
<div class="about-stats">
    <div class="stat">
        <h3>3+</h3>
        <p>Years Experience</p>
    </div>
    <!-- Update your stats -->
</div>
```

#### Skills Section
```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <span>React</span>
</div>
<!-- Add/remove skills as needed -->
```

#### Projects Section
```html
<div class="project-card">
    <h3>E-Commerce Platform</h3>
    <p>Your project description...</p>
    <div class="project-tech">
        <span>React</span>
        <span>Node.js</span>
    </div>
    <div class="project-links">
        <a href="your-demo-link" class="btn btn-small">Live Demo</a>
        <a href="your-github-link" class="btn btn-small btn-outline">GitHub</a>
    </div>
</div>
```

#### Contact Section
```html
<div class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
<div class="contact-method">
    <i class="fas fa-phone"></i>
    <span>+1 (555) 123-4567</span>
</div>
<div class="contact-method">
    <i class="fas fa-map-marker-alt"></i>
    <span>Your City, Country</span>
</div>
```

### Styling Customization

Edit `styles.css` to change colors, fonts, and layout:

#### Color Scheme
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #ffd700;
    --text-color: #333;
    --bg-color: #ffffff;
}
```

#### Fonts
```css
@import url('https://fonts.googleapis.com/css2?family=Your+Font:wght@300;400;500;600;700&display=swap');

body {
    font-family: 'Your Font', sans-serif;
}
```

### Adding Your Images

1. **Profile Picture**: Replace the placeholder in the hero section
2. **About Image**: Add your photo or illustration in the about section
3. **Project Images**: Add screenshots or mockups for your projects

```html
<!-- Replace placeholder divs with actual images -->
<img src="path/to/your/image.jpg" alt="Your Name" class="profile-image">
```

## 🌐 Deployment Options

### GitHub Pages
1. Create a new repository
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch and save

### Netlify
1. Drag and drop your portfolio folder to [netlify.com](https://netlify.com)
2. Get your live URL instantly

### Vercel
1. Connect your GitHub repository to [vercel.com](https://vercel.com)
2. Automatic deployments on every push

## 📱 Mobile Optimization

The portfolio is fully responsive and includes:
- Mobile-first design approach
- Touch-friendly navigation
- Optimized layouts for small screens
- Fast loading on mobile devices

## 🎨 Design Features

- **Gradient Backgrounds**: Modern gradient color schemes
- **Card-based Layout**: Clean, organized content presentation
- **Hover Effects**: Interactive elements with smooth transitions
- **Typography**: Professional font hierarchy and spacing
- **Icons**: Font Awesome icons for visual appeal

## 🔧 Technical Features

- **CSS Grid & Flexbox**: Modern layout techniques
- **CSS Animations**: Smooth transitions and keyframe animations
- **JavaScript ES6+**: Modern JavaScript features
- **Intersection Observer**: Scroll-triggered animations
- **Form Validation**: Client-side form validation
- **Local Storage**: Optional data persistence

## 📈 Performance Tips

1. **Optimize Images**: Compress images before adding
2. **Minify CSS/JS**: Use minified versions for production
3. **CDN**: Use CDN for external resources (already included)
4. **Lazy Loading**: Implement lazy loading for images if needed

## 🚀 Future Enhancements

Consider adding:
- Blog section
- Portfolio filtering
- Dark/Light theme toggle
- Multi-language support
- Analytics integration
- SEO optimization
- Performance monitoring

## 📞 Support

If you need help customizing your portfolio:
1. Check the HTML structure
2. Review CSS classes and selectors
3. Test JavaScript functionality in browser console
4. Validate HTML and CSS using online validators

## 📄 License

This portfolio template is free to use and modify for personal and commercial projects.

---

**Happy Coding! 🎉**

Your portfolio is now ready to showcase your skills and projects to the world!
