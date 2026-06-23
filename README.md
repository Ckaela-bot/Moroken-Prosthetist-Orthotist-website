# Moroken Prosthetist & Orthotist Website

A modern, responsive professional services website for Moroken Prosthetist & Orthotist, showcasing prosthetic and orthotic solutions and services in Pretoria.

**GitHub Repository:** [Ckaela-bot/Moroken-Prosthetist-Orthotist-website](https://github.com/Ckaela-bot/Moroken-Prosthetist-Orthotist-website)

## Features

✨ **Modern Professional Design**
- Premium light theme with blue and grey color scheme
- Smooth scrolling and transitions with cubic-bezier animations
- Professional gradient text effects
- Glass-morphism effects on cards
- Top-notch styling with premium visual hierarchy

📱 **Fully Responsive Layout**
- Desktop, tablet, and mobile optimized
- Hamburger menu for mobile devices
- Premium animations and transitions
- Touch-friendly interface
- Optimized responsive breakpoints at 768px and 480px

🎯 **Key Sections**
- **Hero Section:** Impressive statistics (10+ Patients Served, 2+ Years Experience, 100% Satisfaction Rate)
- **About Section:** Company mission, expertise badges, and professional introduction
- **Services Section:** Prosthetics, Orthotics, Adjustments & Maintenance, Consultations
- **Testimonials:** Client success stories with 5-star ratings
- **Contact Section:** Appointment booking form and contact information
- **Footer:** Company information and social links

🔧 **Interactive Features**
- Premium navigation with gradient underlines and hover animations
- Smooth contact form with validation
- Mobile-friendly responsive design
- Scroll animations and transitions
- Working appointment booking system

## File Structure

```
d:\MY Website\
├── index.html          # Main HTML structure
├── styles.css          # Professional styling with CSS variables
├── script.js           # Form handling and navigation
├── README.md          # Documentation
├── QUICKSTART.md      # Quick start guide
├── CUSTOMIZATION.md   # Customization guide
└── assets/            # Images and media
```

## How to Use

1. **Open the website locally:**
   - Open `index.html` in your web browser
   - Or use a local server (VS Code Live Server extension recommended)

2. **Navigate the site:**
   - Click navigation links to jump to sections
   - Scroll to explore different sections
   - Use mobile hamburger menu on smaller screens

3. **Contact/Appointment Form:**
   - Fill in the appointment form in the Contact section
   - Submit to send email to oratilemaroke@gmail.com
   - Form includes name, email, phone, service selection, and message fields

## Customization Guide

### Colors
Edit the CSS variables in `styles.css` (lines 8-20):
```css
:root {
    --primary-blue: #0066cc;       /* Main brand color */
    --dark-blue: #003d7a;          /* Hover states */
    --light-blue: #e6f0ff;         /* Backgrounds */
    --accent-color: #00a3e0;       /* Secondary highlights */
    --grey: #f5f5f5;               /* Light backgrounds */
    /* ... more colors ... */
}
```

### Content Updates
Edit these sections in `index.html`:
- **Navigation Logo:** Change company name in `.nav-logo`
- **Hero Section:** Update title, subtitle, and statistics
- **About Section:** Update company description and mission
- **Services:** Add/modify services in `.services-grid`
- **Testimonials:** Add/update client testimonials
- **Contact:** Update email, phone, address, and form fields

### Contact Information
Update in `index.html`:
- Email: oratilemaroke@gmail.com
- Phone: +27 79 309 4179
- Address: 6375 Tabane Street, Zone 5 Ga-Rankuwa Pretoria Noord

## Technologies Used

- HTML5
- CSS3 (with CSS variables and animations)
- JavaScript (vanilla)
- Google Fonts (Poppins, Inter)
- Font Awesome 6.4.0 (icons)

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

This website is a professional services site for Moroken Prosthetist & Orthotist.
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p class="project-role">Your Role | Achievement</p>
        <p class="project-description">Description</p>
        <div class="project-tags">
            <span>Tag1</span>
            <span>Tag2</span>
        </div>
    </div>
</div>
```

## Icons Used

The site uses Font Awesome icons. Find more at https://fontawesome.com/icons

Common icons used:
- `fa-code` - Code icon
- `fa-mobile-alt` - Mobile app
- `fa-dumbbell` - Fitness
- `fa-boot` - Products
- `fa-trophy` - Awards
- `fa-star` - Recognition
- `fa-graduation-cap` - Education
- `fa-envelope` - Email
- `fa-phone` - Phone
- `fab fa-linkedin` - LinkedIn
- `fab fa-github` - GitHub

## Advanced Customization

### Add Resume PDF
Replace the "Request Full Resume" button:
```html
<a href="resume.pdf" download class="btn btn-primary">
    <i class="fas fa-download"></i> Download Resume
</a>
```

### Add Project Images
Replace the icon div with an image:
```html
<div class="project-image">
    <img src="project-image.jpg" alt="Project name">
</div>
```

Update the CSS to handle images:
```css
.project-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

### Analytics
Add Google Analytics by adding to `<head>`:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());
    gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Deployment

### Option 1: GitHub Pages
1. Create a GitHub repository
2. Upload files to main branch
3. Enable GitHub Pages in repository settings
4. Site will be live at `https://yourusername.github.io/repo-name`

### Option 2: Netlify
1. Connect your GitHub repository
2. Set publish directory to `/` (root)
3. Deploy automatically on push

### Option 3: Traditional Hosting
1. Upload all files to your hosting provider
2. Set `index.html` as the default/index file
3. Ensure CSS and JS files are in the same directory

## Performance Optimization

The site is optimized for:
- Fast loading (minimal dependencies)
- Smooth animations (GPU-accelerated)
- Mobile performance
- Search engine optimization (SEO)

### Further optimization options:
- Minify CSS and JS files
- Compress images
- Enable gzip compression on server
- Use CDN for assets

## Troubleshooting

**Contact form not working?**
- Ensure your email client is set as default
- The form uses mailto: which opens your email client
- For backend email handling, integrate with services like Formspree or EmailJS

**Mobile menu not responsive?**
- Clear browser cache
- Check browser compatibility
- Ensure JavaScript is enabled

**Animations choppy?**
- Reduce animation complexity in CSS
- Check browser GPU acceleration settings
- Update browser to latest version

## Technologies Used

- HTML5
- CSS3 (with modern features like Grid, Flexbox, Gradients)
- JavaScript (Vanilla - no frameworks)
- Font Awesome Icons (CDN)
- Google Fonts (Poppins, Inter)

## SEO Optimization

The site includes:
- Semantic HTML structure
- Meta viewport for mobile
- Descriptive page title
- Proper heading hierarchy
- Image alt attributes (for future images)

## Additional Resources

- Font Awesome: https://fontawesome.com
- Google Fonts: https://fonts.google.com
- CSS Gradients: https://cssgradient.io
- Animation tools: https://animista.net

## Future Enhancements

Consider adding:
- Blog section for tech articles
- Live project demos/portfolio items
- Testimonials section
- Downloadable resume PDF
- Dark/light theme toggle
- Multi-language support
- Backend contact form with database

## Support & Feedback

For customization help or issues:
- Review the CSS comments for styling explanations
- Check Font Awesome documentation for icon names
- Test in different browsers for compatibility

---

**Created:** May 2026
**Portfolio Owner:** Cliff Kaela
**Website:** Your Custom Portfolio

Enjoy your professional portfolio! 🚀
=======
# CLIFF-KAELA-PORTFOLIO-WEBSITE
>>>>>>> target/main
