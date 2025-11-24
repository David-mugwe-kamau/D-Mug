# D MUG - Web Developer Portfolio

A modern, responsive portfolio website showcasing web development skills and projects. Built with vanilla HTML, CSS, and JavaScript.

## 🌟 Features

### Core Features
- **Responsive Design**: Fully responsive layout that works on all devices
- **Light/Dark Theme Toggle**: Switch between light and dark themes with preference saved in localStorage
- **Parallax Background**: Subtle parallax effect on the background image for depth
- **Smooth Animations**: Fade-in animations on scroll using Intersection Observer API
- **Smooth Scrolling**: Native smooth scroll behavior throughout the site

### Sections
1. **Hero Section**: Introduction and professional description
2. **Skills & Technologies**: Grid showcasing technical skills (React, JavaScript, CSS3, HTML5, SASS, Node.js, Git, Webpack, Responsive Design, Performance, Accessibility, UX/UI Design)
3. **Featured Project**: JazzMan Housecalls - Professional barber booking platform
4. **Contact Section**: Multiple contact options (Email, WhatsApp, Phone)

### Interactive Elements
- **Theme Toggle Button**: Top-right corner button to switch themes
- **Scroll-to-Top Button**: Appears after scrolling 300px, smoothly scrolls to top
- **Contact Buttons**: 
  - Email: davidmugwekamau@gmail.com
  - WhatsApp: +254704629818
  - Phone: +254704629818
- **Project Link**: Direct link to JazzMan Housecalls project

## 📁 File Structure

```
D mug/
├── index.html          # Main HTML file
├── style.css          # All styles and responsive design
├── script.js          # JavaScript functionality
└── README.md          # This file
```

## 🚀 Getting Started

### Local Development

1. **Clone or download** this repository
2. **Open `index.html`** in your web browser
   - Simply double-click the file, or
   - Use a local server (recommended):
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```
3. **Navigate to** `http://localhost:8000` in your browser

### No Build Process Required
This is a static website with no build process, dependencies, or package managers needed. Just open the HTML file!

## 🎨 Customization

### Changing Colors
Edit `style.css` to modify:
- Theme colors (gradients, backgrounds)
- Button colors
- Text colors

### Adding Projects
In `index.html`, add new project cards in the `.projects` section:
```html
<div class="project-card">
    <h3>Project Name</h3>
    <p>Project description...</p>
    <div class="project-buttons">
        <a href="project-url" class="project-btn">View Project</a>
    </div>
</div>
```

### Adding Skills
In `index.html`, add new skill items in the `.skills-grid`:
```html
<div class="skill-item">
    <div class="skill-icon">🎨</div>
    <span>Skill Name</span>
</div>
```

### Updating Contact Information
Edit the contact section in `index.html`:
- Email: Change `href="mailto:your-email@example.com"`
- WhatsApp: Change `href="https://wa.me/your-number"`
- Phone: Change `href="tel:your-number"`

### Changing Background Image
In `style.css`, update the `.parallax-bg` background-image URL:
```css
background-image: url('your-image-url');
```

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with flexbox, grid, animations
- **JavaScript (ES6+)**: 
  - Theme toggle with localStorage
  - Parallax scrolling
  - Intersection Observer API for animations
  - Smooth scroll functionality

## 📝 SEO Features

- Meta description and keywords
- Open Graph tags for social sharing
- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images (when added)

## 🚀 Deployment

### ✅ Currently Deployed On: Render.com

**Live URL**: https://d-mug.onrender.com  
**GitHub Repository**: https://github.com/David-mugwe-kamau/D-Mug  
**Status**: ✅ Live and Active

### Deployment Configuration
- **Platform**: Render.com (Static Site)
- **Repository**: Connected to GitHub
- **Branch**: `main`
- **Build Command**: Empty (no build process)
- **Publish Directory**: `.` (root directory)
- **Auto-Deploy**: Enabled

### Other Deployment Options

#### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select main branch
5. Your site will be live at `https://yourusername.github.io/repository-name`

#### Option 2: Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Your site is live instantly!

#### Option 3: Vercel (Free)
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository or upload files
3. Deploy with one click

#### Option 4: Any Web Hosting
Upload all files via FTP to your hosting provider's public_html or www directory.

## 📧 Contact

- **Email**: davidmugwekamau@gmail.com
- **WhatsApp**: +254704629818
- **Phone**: +2547046298818
- **Location**: Nairobi, Kenya (EAT)

## 📄 License

© 2025 D MUG. All rights reserved.

## 🎯 Future Enhancements

Potential additions:
- More project showcases
- Blog section
- Testimonials
- Contact form
- Download resume/CV
- Social media links
- Analytics integration

---

**Built with ❤️ by David Mugwe Kamau**

