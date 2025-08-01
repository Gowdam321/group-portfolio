# Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript featuring a beautiful dark blue and white theme.

## 🌟 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Professional dark blue and white theme with smooth animations
- **Interactive Navigation**: Smooth scrolling and active page highlighting
- **Project Showcase**: Filterable project gallery with detailed descriptions
- **Skills Visualization**: Animated progress bars for technical skills
- **Contact Form**: Functional contact form with validation
- **Social Media Integration**: Links to LinkedIn, GitHub, Twitter, and more
- **Loading Animations**: Smooth page transitions and element animations
- **Mobile-First**: Optimized for all screen sizes

## 📁 File Structure

```
portfolio/
├── index.html          # Home page
├── about.html          # About page with experience timeline
├── skills.html         # Skills page with progress bars
├── projects.html       # Projects showcase with filters
├── certifications.html # Certifications and achievements
├── contact.html        # Contact form and information
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🚀 Quick Start

1. **Download/Clone** the portfolio files to your local machine
2. **Open** `index.html` in your web browser
3. **Customize** the content to match your information
4. **Deploy** to your preferred hosting service

## 🎨 Customization Guide

### 1. Personal Information

Update the following in each HTML file:
- **Name**: Replace "Your Name" with your actual name
- **Title/Role**: Update job titles and descriptions
- **Contact Information**: Add your real email, phone, and location
- **Social Links**: Update LinkedIn, GitHub, Twitter URLs

### 2. Content Updates

#### Home Page (`index.html`)
- Update hero section with your name and tagline
- Modify the brief description
- Update statistics (years experience, projects, etc.)

#### About Page (`about.html`)
- Replace the personal story with your own
- Update work experience timeline
- Modify education details
- Add your actual contact information

#### Skills Page (`skills.html`)
- Update skill names and proficiency levels
- Modify skill descriptions
- Adjust progress bar percentages in `data-progress` attributes
- Add/remove skills as needed

#### Projects Page (`projects.html`)
- Replace project examples with your actual projects
- Update project descriptions and technologies used
- Add real project links (GitHub, live demo)
- Modify project categories and filters

#### Certifications Page (`certifications.html`)
- Replace with your actual certifications
- Update certification details, dates, and descriptions
- Add your real achievement statistics

#### Contact Page (`contact.html`)
- Update contact information
- Modify social media links
- Customize availability and preferences

### 3. Styling Customization

#### Color Scheme
The portfolio uses CSS custom properties for easy color customization. In `styles.css`, update:

```css
:root {
    --primary-color: #1a2332;      /* Main dark blue */
    --secondary-color: #2d3748;    /* Secondary dark blue */
    --accent-color: #3182ce;       /* Accent blue */
    --accent-light: #4299e1;       /* Light blue */
    --text-primary: #ffffff;       /* White text */
    --text-secondary: #e2e8f0;     /* Light gray text */
    --text-muted: #a0aec0;         /* Muted text */
    --background: #0f1419;         /* Background color */
    --surface: #1a2332;            /* Surface color */
    --border: #2d3748;             /* Border color */
}
```

#### Fonts
The portfolio uses the Inter font family. You can change it by updating the `font-family` property in the `body` selector.

### 4. Adding Images

To add your own images:
1. Create an `images/` folder
2. Add your images (profile photo, project screenshots, etc.)
3. Update the HTML to reference your images
4. For profile photos, replace the icon placeholders with `<img>` tags

### 5. Form Functionality

The contact form is currently set up for demonstration. To make it functional:

1. **EmailJS** (Recommended):
   ```html
   <!-- Add to contact.html head section -->
   <script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
   ```

2. **Netlify Forms**:
   Add `netlify` attribute to the form:
   ```html
   <form id="contact-form" class="contact-form" netlify>
   ```

3. **Custom Backend**:
   Update the form action to point to your backend endpoint.

## 📱 Responsive Design

The portfolio is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🚀 Deployment Options

### GitHub Pages
1. Create a GitHub repository
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch and save

### Netlify
1. Drag and drop your portfolio folder to Netlify
2. Your site will be live instantly
3. Customize domain if needed

### Vercel
1. Connect your GitHub repository
2. Vercel will automatically deploy
3. Updates are automatic on push

### Traditional Hosting
Upload files to any web hosting service via FTP or file manager.

## 🔧 Advanced Customization

### Adding New Pages
1. Create a new HTML file
2. Copy the navigation structure from existing pages
3. Add your content
4. Update navigation links in all pages
5. Add corresponding CSS styles

### Custom Animations
The portfolio uses CSS animations and JavaScript for interactions. You can:
- Modify animation durations in CSS
- Add new animations using `@keyframes`
- Customize JavaScript animations in `script.js`

### SEO Optimization
1. Update meta tags in each HTML file
2. Add Open Graph tags for social sharing
3. Include structured data markup
4. Optimize images and use alt text

## 📞 Support

If you need help customizing your portfolio:
1. Check the code comments for guidance
2. Modify one section at a time
3. Test changes in your browser
4. Use browser developer tools for debugging

## 📄 License

This portfolio template is free to use for personal and commercial projects.

## 🙏 Credits

- **Font Awesome**: Icons
- **Google Fonts**: Inter font family
- **CSS Grid & Flexbox**: Layout system
- **Modern CSS**: Custom properties and animations

---

**Happy coding! 🚀**

Your portfolio is now ready to showcase your skills and projects professionally! 