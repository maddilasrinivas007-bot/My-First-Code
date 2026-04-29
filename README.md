# Professional Portfolio Website

A fully responsive, modern portfolio website built with **HTML**, **CSS**, and **JavaScript**. Perfect for showcasing your projects, experience, and skills to potential employers and clients.

## 🌟 Features

### Core Sections
- ✅ **Hero Section** - Eye-catching introduction with call-to-action buttons
- ✅ **About Me** - Personal introduction with statistics
- ✅ **Experience** - Timeline view of work experience
- ✅ **Education** - Educational background display
- ✅ **Skills** - Skills with progress bars organized by category
- ✅ **Projects** - Featured projects with links to GitHub and live demos
- ✅ **Certifications** - Professional certifications and achievements
- ✅ **Contact Section** - Contact information and contact form

### Additional Features
- 🌙 **Dark/Light Mode Toggle** - Save preference in browser localStorage
- 📱 **Fully Responsive** - Works perfectly on desktop, tablet, and mobile
- ⚡ **Smooth Animations** - CSS animations and Intersection Observer effects
- 🎯 **Smooth Scrolling** - Smooth navigation between sections
- 📍 **Active Navigation Indicator** - Shows current section in navbar
- ⬆️ **Scroll-to-Top Button** - Quick return to top
- 💬 **Contact Form Validation** - Client-side form validation
- 🎨 **Modern Design** - Clean, professional styling with gradients
- ⌨️ **Keyboard Shortcuts** - Press 'H' for home, 'C' for contact
- 🏆 **Professional Typography** - Beautiful fonts and spacing

## 📁 File Structure

```
My First Code/
├── index.html      # Main HTML file with all sections
├── styles.css      # Complete styling and responsive design
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## 🚀 Getting Started

### 1. View the Website
Simply open `index.html` in your web browser:
- Double-click `index.html`
- Or right-click → "Open with" → Choose your browser

### 2. Live Server (Recommended)
For a better development experience, use VS Code Live Server:
1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## ✏️ Customization Guide

### 1. **Basic Information**
Edit `index.html` to update:

**Replace these in the Hero Section:**
```html
<h1 class="hero-title">Hi, I'm Your Name</h1>
<p class="hero-subtitle">Full Stack Developer | Problem Solver | Tech Enthusiast</p>
```

**Update About Section:**
```html
<p>I'm a passionate developer with expertise...</p>
```

### 2. **Experience Timeline**
Update your work experience in the Experience section:
```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <h3 class="experience-title">Your Job Title</h3>
        <p class="company">Company Name | 2023 - Present</p>
        <p class="experience-description">Your description here...</p>
        <ul class="experience-highlights">
            <li>Achievement 1</li>
            <li>Achievement 2</li>
        </ul>
    </div>
</div>
```

### 3. **Education**
Update your education in the Education section:
```html
<div class="education-card">
    <div class="education-icon">🎓</div>
    <h3>Your Degree Name</h3>
    <p class="education-institute">University Name | 2015 - 2019</p>
    <p class="education-details">Your details here</p>
</div>
```

### 4. **Skills**
Add or modify your skills with progress percentages:
```html
<div class="skill-item">
    <span class="skill-name">Your Skill</span>
    <div class="skill-bar">
        <div class="skill-progress" style="width: 85%"></div>
    </div>
</div>
```

### 5. **Projects**
Update your projects with descriptions and links:
```html
<div class="project-card">
    <div class="project-image">
        <div class="placeholder-image">🎯</div>
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourproject" target="_blank">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="https://yourproject-demo.com" target="_blank">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
        </div>
    </div>
</div>
```

### 6. **Certifications**
Add your certifications:
```html
<div class="certification-card">
    <div class="cert-icon">🏅</div>
    <h3>Certification Name</h3>
    <p class="cert-issuer">Issuing Organization</p>
    <p class="cert-date">Issued: Month Year</p>
    <p class="cert-description">Certification description...</p>
    <a href="certificate-url" class="cert-link">View Certificate →</a>
</div>
```

### 7. **Contact Information**
Update your contact details:
```html
<div class="contact-card">
    <i class="fas fa-envelope"></i>
    <h3>Email</h3>
    <a href="mailto:your.email@example.com">your.email@example.com</a>
</div>

<a href="https://linkedin.com/in/yourprofile" target="_blank">
    linkedin.com/in/yourprofile
</a>
```

### 8. **Statistics**
Update the stats section in About:
```html
<div class="stat">
    <h3>5+</h3>
    <p>Years Experience</p>
</div>
```

### 9. **Footer**
Update the footer copyright:
```html
<p>&copy; 2024 Your Name. All rights reserved.</p>
```

## 🎨 Color Customization

To change the color scheme, edit the CSS variables in `styles.css`:

```css
:root {
    /* Change primary color */
    --primary-color: #2563eb;      /* Current: Blue */
    --secondary-color: #1e40af;    /* Current: Dark Blue */
    --accent-color: #0ea5e9;       /* Current: Light Blue */
    
    /* Text and background colors */
    --text-color: #1f2937;
    --bg-color: #ffffff;
    --bg-light: #f9fafb;
}
```

### Popular Color Schemes:
- **Purple Theme:** `#7c3aed` (primary)
- **Green Theme:** `#10b981` (primary)
- **Orange Theme:** `#f59e0b` (primary)
- **Red Theme:** `#ef4444` (primary)

## 📱 Responsive Breakpoints

The website is fully responsive with breakpoints at:
- **Desktop:** 1200px and above
- **Tablet:** 769px - 1199px
- **Mobile:** Below 768px

## 🔧 JavaScript Features

### Available Functions:
- **Dark Mode Toggle** - Saves preference in localStorage
- **Mobile Menu** - Hamburger menu for mobile devices
- **Smooth Scrolling** - Navigate sections smoothly
- **Form Validation** - Validates contact form
- **Animations** - Triggers animations on scroll
- **Active Nav Indicator** - Shows which section you're viewing
- **Scroll-to-Top Button** - Appears when scrolling down

### Keyboard Shortcuts:
- **H** - Scroll to Home
- **C** - Scroll to Contact

## 📧 Contact Form Setup

### Option 1: Mailto (Default)
The form uses mailto links. Users can submit messages to their email client.

### Option 2: Backend Integration
To send emails directly, modify `script.js`:

```javascript
// Replace the mailto link with your backend API
fetch('https://your-api.com/send-email', {
    method: 'POST',
    headers: { 'Content-Type': 'application/json' },
    body: JSON.stringify({ name, email, subject, message })
})
```

## 🌐 Deployment

### GitHub Pages (Free)
1. Create a GitHub repository
2. Push your files to the repository
3. Go to Settings → Pages
4. Select main branch as source
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Netlify
1. Sign up at netlify.com
2. Drag and drop your project folder
3. Your site will be instantly live

### Vercel
1. Sign up at vercel.com
2. Import your GitHub repository
3. Deploy automatically

## 🎯 Tips for Best Results

1. **Add Real Images** - Replace emoji placeholders with actual project images
2. **Update All Links** - Replace placeholder GitHub/LinkedIn/email links
3. **Customize Colors** - Adjust CSS variables to match your brand
4. **Add More Projects** - Copy the project card template to add more work
5. **Optimize for SEO** - Update the `<title>` and meta tags in `index.html`
6. **Test Responsiveness** - Check on various devices using browser DevTools
7. **Performance** - Compress images before uploading

## 📝 SEO Optimization

Update the following in `index.html` for better SEO:

```html
<title>Your Name - Full Stack Developer Portfolio</title>
<meta name="description" content="Portfolio of [Your Name], a [your title] showcasing projects, experience, and skills.">
<meta name="keywords" content="portfolio, developer, projects, full stack">
<meta name="author" content="Your Name">
```

## 🐛 Troubleshooting

### Images not loading?
- Ensure image paths are correct
- Use absolute URLs for external images
- Check file permissions

### Styles not applying?
- Clear browser cache (Ctrl+F5 or Cmd+Shift+R)
- Ensure styles.css is in the same directory
- Check for CSS syntax errors

### JavaScript not working?
- Ensure script.js is in the same directory
- Check browser console for errors (F12)
- Verify Font Awesome CDN link is working

## 📚 Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [JavaScript.info](https://javascript.info/)
- [Font Awesome Icons](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)

## 📄 License

This template is free to use and modify for personal and commercial projects.

## 💡 Future Enhancements

Consider adding:
- Blog section
- Testimonials carousel
- Photo gallery
- Resume download button
- Analytics tracking
- Newsletter signup
- Social media feed integration

## 🤝 Support

If you encounter any issues or need modifications, refer to the troubleshooting section or consult the resources listed above.

---

**Happy Building! 🚀**

Your portfolio website is now ready. Customize it with your information and deploy it to showcase your amazing work to the world!
