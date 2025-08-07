# SAMPATH - Developer Portfolio

A modern, responsive portfolio website built with HTML, CSS, and JavaScript featuring a developer theme with dark colors, code-style elements, and smooth animations.

## 🚀 Features

- **Modern Developer Theme**: Dark color scheme with code-style elements
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: CSS animations and JavaScript interactions
- **Interactive Elements**: Hover effects, typing animations, and smooth scrolling
- **Contact Form**: Functional contact form with validation
- **Professional Sections**: Hero, About, Experience, Projects, Skills, and Contact
- **Code Terminal**: Interactive terminal window in the hero section
- **Mobile Navigation**: Hamburger menu for mobile devices

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles and animations
├── js/
│   └── script.js       # JavaScript functionality
├── images/             # Image assets (if needed)
├── assets/             # Additional assets
└── README.md           # This file
```

## 🎨 Design Features

### Color Scheme
- **Primary**: `#00d4ff` (Cyan blue)
- **Secondary**: `#ff6b6b` (Coral red)
- **Accent**: `#4ecdc4` (Teal)
- **Background**: Dark theme with multiple shades
- **Text**: White and gray variations for hierarchy

### Typography
- **Main Font**: Inter (Google Fonts)
- **Code Font**: Fira Code (Monospace for code elements)

### Interactive Elements
- Hover effects on cards and buttons
- Smooth scrolling navigation
- Typing animation for hero section
- Terminal-style code window
- Ripple effects on buttons
- Scroll-to-top button
- Mobile-responsive navigation

## 🛠️ Customization

### 1. Personal Information
Edit the following sections in `index.html`:

- **Hero Section**: Update name, title, and description
- **About Section**: Modify personal description and education details
- **Experience Section**: Update work experience with your details
- **Projects Section**: Replace with your own projects
- **Skills Section**: Update skills and technologies
- **Contact Section**: Update contact information

### 2. Colors
Modify the CSS variables in `css/style.css`:

```css
:root {
    --primary-color: #00d4ff;    /* Main accent color */
    --secondary-color: #ff6b6b;  /* Secondary accent */
    --accent-color: #4ecdc4;     /* Additional accent */
    --bg-dark: #0a0a0a;          /* Main background */
    --bg-darker: #050505;        /* Darker background */
    --bg-light: #1a1a1a;         /* Light background */
    /* ... other variables */
}
```

### 3. Images
Replace the Unsplash image URLs with your own images:

- **Hero Section**: Update the profile image URL
- **Projects Section**: Replace project images with your own
- **About Section**: Update the developer image

### 4. Content
Update the following content sections:

#### Experience
Replace the job entries with your work experience:
```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <div class="job-header">
            <h3>Your Job Title</h3>
            <span class="company">Company Name</span>
            <span class="duration">Date Range</span>
        </div>
        <span class="location">Location</span>
        <div class="tech-stack">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <ul class="job-achievements">
            <li>Your achievement 1</li>
            <li>Your achievement 2</li>
        </ul>
    </div>
</div>
```

#### Projects
Update project cards with your projects:
```html
<div class="project-card">
    <div class="project-image">
        <img src="your-project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link"><i class="fab fa-github"></i> Code</a>
            <a href="#" class="project-link"><i class="fas fa-external-link-alt"></i> Demo</a>
        </div>
    </div>
</div>
```

#### Skills
Update the skills section with your expertise:
```html
<div class="skill-category">
    <h3>Category Name</h3>
    <div class="skill-tags">
        <span class="skill-tag">Skill 1</span>
        <span class="skill-tag">Skill 2</span>
    </div>
</div>
```

## 🚀 Deployment

### Local Development
1. Clone or download the portfolio files
2. Open `index.html` in your web browser
3. The website will work locally without any server setup

### GitHub Pages
1. Create a new repository on GitHub
2. Upload all portfolio files to the repository
3. Go to Settings > Pages
4. Select source as "Deploy from a branch"
5. Choose the main branch and save
6. Your portfolio will be available at `https://yourusername.github.io/repositoryname`

### Netlify
1. Create a Netlify account
2. Drag and drop the portfolio folder to Netlify
3. Your site will be deployed automatically
4. You can customize the URL in the site settings

### Vercel
1. Create a Vercel account
2. Import your GitHub repository
3. Deploy automatically with each push

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Performance Features

- Optimized CSS with CSS custom properties
- Efficient JavaScript with debounced scroll events
- Lazy loading for images
- Smooth animations with hardware acceleration
- Responsive images from Unsplash CDN

## 🔧 Troubleshooting

### Common Issues

1. **Images not loading**: Check if the Unsplash URLs are accessible
2. **Fonts not loading**: Ensure internet connection for Google Fonts
3. **Animations not working**: Check if JavaScript is enabled
4. **Mobile menu not working**: Ensure JavaScript is loaded properly

### Performance Tips

- Optimize images before uploading
- Minify CSS and JavaScript for production
- Use a CDN for external resources
- Enable gzip compression on your server

## 📄 License

This portfolio template is free to use for personal and commercial projects. Attribution is appreciated but not required.

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you make improvements, consider sharing them with the community.

## 📞 Support

If you need help customizing or deploying your portfolio, feel free to reach out!

---

**Built with ❤️ and lots of coffee ☕**
