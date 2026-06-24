# Kay Manpower Naija - Website

A professional, responsive website for an international recruitment agency and travel service company operating in Nigeria.

## 🌍 About Kay Manpower Naija

Kay Manpower Naija is a comprehensive platform that offers three main services:
- **Recruitment Services** - Connect professionals with international employers
- **International Education** - Guide students to top universities worldwide
- **Travel & Overseas Opportunities** - Assist with visas, work permits, and relocation

## 📁 Project Structure

```
Kay Project/
│
├── index.html                 # Homepage - main entry point
├── recruitment.html          # Recruitment services page
├── education.html            # International education page
├── travel.html               # Travel & visa services page
├── opportunities.html        # All opportunities listing page
│
├── assets/
│   ├── css/
│   │   └── style.css         # Main stylesheet with Bootstrap customization
│   │
│   └── js/
│       └── main.js           # JavaScript for interactivity
│
└── README.md                 # This file
```

## 🎨 Features

### Homepage (index.html)
- **Hero Section** - Eye-catching welcome banner
- **Services Overview** - Three main service cards with features
- **Featured Opportunities** - Latest job, education, and travel opportunities
- **About Section** - Company information and mission
- **Contact Form** - Get in touch with the team
- **Navigation** - Sticky header with responsive menu

### Service Pages

#### Recruitment Services (recruitment.html)
- Detailed service descriptions
- Featured job listings with salary ranges
- 4-step recruitment process
- Skills and requirements
- Call-to-action buttons

#### International Education (education.html)
- Study program information
- Featured university programs
- Scholarship details
- Study destinations (Canada, UK, Germany, Australia, USA, Netherlands)
- Application process guide

#### Travel & Overseas (travel.html)
- Visa types and requirements
- Visa processing information
- Documentation checklists
- FAQ section
- Country-specific information

#### All Opportunities (opportunities.html)
- Job openings (internships, full-time positions)
- Education programs
- Scholarships
- Interactive filters by type and country
- Search functionality

## 🛠️ Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styles and animations
- **Bootstrap 5** - Responsive grid and components
- **JavaScript (Vanilla)** - Form handling and interactivity
- **Font Awesome 6** - Icons

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop (1200px and above)
- Tablets (768px - 1199px)
- Mobile devices (below 768px)

## 🎯 Key Features

### Navigation
- Sticky navbar that stays visible while scrolling
- Responsive hamburger menu on mobile
- Smooth scrolling to sections
- Active link highlighting

### Interactive Elements
- Form validation and submission handling
- Filter and search functionality on opportunities page
- Smooth animations and transitions
- Hover effects on cards and buttons
- Alert notifications for user actions

### Accessibility
- Proper semantic HTML
- Alt text for images
- ARIA labels where needed
- Keyboard navigation support
- Focus indicators

## 🚀 Getting Started

### Local Development

1. **Extract the project files** to your desired location
2. **Open index.html** in a web browser (or use a local server)
3. **Navigate** through the pages using the menu

### Using a Local Server (Recommended)

For better functionality, use a local server:

**Using Python:**
```bash
# Python 3.x
python -m http.server 8000

# Python 2.x
python -m SimpleHTTPServer 8000
```

**Using Node.js (http-server):**
```bash
npm install -g http-server
http-server
```

Then open `http://localhost:8000` in your browser.

## 📝 Customization

### Colors
Edit the CSS variables in `assets/css/style.css`:
```css
:root {
    --primary-color: #0d6efd;
    --secondary-color: #198754;
    --info-color: #0dcaf0;
}
```

### Contact Information
Update contact details in:
- `index.html` - Contact section and footer
- `recruitment.html` - Footer
- `education.html` - Footer
- `travel.html` - Footer

### Social Media Links
Update social links in footer sections of all pages

### Email Configuration
Update email addresses:
- `info@kaympower.com` - Change to your email
- Phone number: `+234 (0) 123 456 7890`
- Location: Lagos, Nigeria

## 📋 Form Integration

### Contact Form
The contact form in the homepage currently:
- Validates required fields
- Shows success message
- Clears form after submission

**To integrate with email service:**
1. Use a service like Formspree, Netlify Forms, or EmailJS
2. Update the form's action attribute and method
3. Add backend processing as needed

## 🔍 SEO Optimization

To improve SEO, update:
- `<title>` tags - Make them descriptive and unique
- `<meta name="description">` - Add meta descriptions
- Heading hierarchy (H1, H2, H3)
- Image alt text
- Schema markup (structured data)

## 🎓 Page Descriptions

### Meta Tags Template
```html
<meta name="description" content="Kay Manpower Naija - International recruitment, education, and travel services for Nigerian professionals.">
<meta name="keywords" content="recruitment, education, visas, overseas opportunities">
<meta name="author" content="Kay Manpower Naija">
```

## 📊 Analytics

To add Google Analytics or other tracking:
1. Get your tracking ID
2. Add the tracking code to each page's `<head>` section
3. Or use Google Tag Manager for easier management

## 🐛 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📞 Support & Maintenance

### Regular Updates
- Update opportunities regularly
- Keep contact information current
- Refresh featured programs
- Monitor form submissions

### Performance Tips
- Optimize images for web
- Minify CSS and JavaScript
- Use a CDN for assets
- Enable browser caching

## 📜 License

This website design is provided for use by Kay Manpower Naija.

## 🤝 Contact Information

**Kay Manpower Naija**
- Email: info@kaympower.com
- Phone: +234 (0) 123 456 7890
- Location: Lagos, Nigeria

---

**Last Updated:** June 2026

For updates, improvements, or additional features, contact the development team.
