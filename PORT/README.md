# Modern Portfolio Website

A beautiful, responsive portfolio website built with HTML, CSS, and JavaScript. Features a modern design with smooth animations, mobile-friendly navigation, and interactive elements.

## 🚀 Features

- **Responsive Design**: Works perfectly on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and form validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Functional contact form with validation
- **SEO Optimized**: Proper meta tags and semantic HTML
- **Fast Loading**: Optimized for performance

## 📁 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Clone or Download** the files to your local machine
2. **Open** `index.html` in your web browser to preview
3. **Customize** the content according to your needs (see customization guide below)

## 🎨 Customization Guide

### Personal Information
Edit the following in `index.html`:

- **Name**: Replace "Your Name" with your actual name
- **Title**: Update the job title in the hero section
- **Description**: Modify the about section content
- **Contact Details**: Update email, phone, and location
- **Social Links**: Add your social media profiles

### Projects
Update the projects section with your own work:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description goes here.</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="your-demo-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
        </div>
    </div>
</div>
```

### Skills
Modify the skills section to match your expertise:

```html
<div class="skill-item">
    <i class="fab fa-react"></i>
    <span>React</span>
</div>
```

### Colors and Styling
Customize the color scheme in `styles.css`:

- **Primary Color**: `#2563eb` (blue)
- **Secondary Color**: `#fbbf24` (yellow)
- **Gradient**: `linear-gradient(135deg, #667eea 0%, #764ba2 100%)`

## 🌐 Deployment to Netlify

### Method 1: Drag & Drop (Easiest)
1. Go to [netlify.com](https://netlify.com)
2. Sign up or log in to your account
3. Drag and drop your portfolio folder to the Netlify dashboard
4. Your site will be deployed instantly with a random URL
5. Click "Site settings" to customize the URL

### Method 2: Git Integration (Recommended)
1. Push your portfolio to a GitHub repository
2. Connect your GitHub account to Netlify
3. Select your portfolio repository
4. Deploy settings:
   - **Build command**: Leave empty (static site)
   - **Publish directory**: Leave as root (./)
5. Click "Deploy site"

### Method 3: Netlify CLI
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy your site
netlify deploy

# Deploy to production
netlify deploy --prod
```

## 🔧 Custom Domain Setup

1. In your Netlify dashboard, go to "Site settings"
2. Click "Domain management"
3. Click "Add custom domain"
4. Enter your domain name
5. Follow the DNS configuration instructions

## 📱 Mobile Optimization

The website is fully responsive and includes:
- Mobile-first design approach
- Touch-friendly navigation
- Optimized images and content
- Fast loading times

## 🎯 SEO Optimization

The website includes:
- Proper meta tags
- Semantic HTML structure
- Optimized headings hierarchy
- Alt text for images
- Fast loading times

## 🔒 Security Features

- Form validation
- XSS protection
- Secure external links
- HTTPS ready

## 📈 Performance Tips

1. **Optimize Images**: Use WebP format when possible
2. **Minimize CSS/JS**: Consider minifying files for production
3. **Use CDN**: External libraries are loaded from CDN
4. **Lazy Loading**: Implement for images if needed

## 🐛 Troubleshooting

### Common Issues:

1. **Images not loading**: Check file paths and ensure images exist
2. **Fonts not loading**: Verify internet connection for Google Fonts
3. **Form not working**: Check JavaScript console for errors
4. **Mobile menu not working**: Ensure JavaScript is enabled

### Browser Support:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📞 Support

If you encounter any issues:
1. Check the browser console for errors
2. Verify all file paths are correct
3. Ensure all files are in the same directory
4. Test in different browsers

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to contribute to this project by:
- Reporting bugs
- Suggesting new features
- Submitting pull requests

---

**Happy Coding! 🚀** 