# Dutch Cleaning Website

A professional, modern janitorial and commercial cleaning services website built with HTML, CSS, and JavaScript.

## 🌐 Website Features

- **Professional Design**: Clean, modern aesthetic with blue and green color scheme
- **Responsive Layout**: Fully mobile-responsive design
- **Service Showcase**: Highlight 6 service categories
- **Trust Building**: Client testimonials, certifications, and stats
- **Contact Form**: Easy quote request system
- **Call-to-Action**: Multiple conversion points throughout
- **Smooth Animations**: Interactive elements and transitions

## 🚀 Quick Start

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/DutchCleaning/Dutch-Cleaning-Website.git
cd Dutch-Cleaning-Website
```

2. Open in your browser:
   - Simply open `index.html` in your web browser
   - Or use a local server like Python's built-in server:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## 📁 Project Structure

```
Dutch-Cleaning-Website/
├── index.html          # Main HTML file
├── styles.css          # Styling and responsive design
├── script.js           # Interactive functionality
├── README.md           # This file
└── .github/
    └── workflows/
        └── deploy.yml  # GitHub Pages deployment
```

## 🎨 Customization

### Update Company Information
Edit the following in `index.html`:
- Company name and logo
- Phone number
- Email address
- Service descriptions
- Testimonials

### Update Colors
In `styles.css`, modify the CSS variables:
```css
:root {
    --primary-color: #1e3a8a;        /* Navy blue */
    --secondary-color: #3b82f6;      /* Bright blue */
    --accent-color: #10b981;         /* Green */
}
```

### Add Your Images
Replace placeholders with actual images:
1. Add your images to the repository
2. Update image paths in `index.html`

## 🌍 GitHub Pages Deployment

Your website is automatically deployed to GitHub Pages!

### Access Your Live Site
Visit: `https://DutchCleaning.github.io/Dutch-Cleaning-Website/`

### How It Works
- The `.github/workflows/deploy.yml` file automatically deploys your site whenever you push to the `main` branch
- GitHub Pages serves your website for free
- Updates are live within seconds of pushing to main

### Enable GitHub Pages (if needed)
1. Go to your repository settings
2. Navigate to "Pages" section
3. Set Source to "GitHub Actions"
4. Save

## 📝 Adding Content

### Add New Sections
Create new sections in `index.html` and add corresponding styles in `styles.css`

### Add Services
Edit the services grid in the "Our Services" section:
```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-icon-name"></i>
    </div>
    <h3>Service Name</h3>
    <p>Service description...</p>
</div>
```

### Update Contact Form
Modify form fields and styling in the contact section

## 🔧 Features

### Services Section
- 6 customizable service categories with icons
- Hover effects and smooth animations

### Why Choose Us
- 6 feature highlights
- Statistics display
- Trust-building elements

### Testimonials
- Client testimonials with star ratings
- Professional presentation

### Contact Form
- Service type selection
- Easy quote request
- Success notifications

## 📱 Responsive Design

The website is optimized for:
- Desktop computers (1200px+)
- Tablets (768px - 1199px)
- Mobile phones (under 768px)

## 🎯 SEO Optimization

The website includes:
- Meta descriptions
- Semantic HTML structure
- Mobile-first design
- Fast loading times

## 📧 Contact Form Integration

The contact form currently shows a success message. To send actual emails, integrate with:
- **Formspree**: https://formspree.io/
- **EmailJS**: https://www.emailjs.com/
- **Netlify Forms**: https://www.netlify.com/products/forms/
- Your own backend service

## 🎓 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Grid and Flexbox
- **JavaScript**: Vanilla JS for interactivity
- **Font Awesome**: Icon library
- **GitHub Pages**: Free hosting

## 📄 License

This project is open source and available under the MIT License.

## 🤝 Contributing

Feel free to customize and improve this website for your business needs!

## 📞 Support

For questions or issues, please create an issue in the repository.

---

**Dutch Cleaning Website** - Professional Janitorial Services Online
