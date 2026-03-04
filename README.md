# Prokaryon Bio Lab Website

A fully responsive, production-ready website built with pure HTML, CSS, and JavaScript.

## Features

- ✅ Fully responsive design (mobile-first approach)
- ✅ Pure HTML, CSS, and JavaScript (no frameworks)
- ✅ Semantic HTML and accessibility best practices
- ✅ Contact form with validation
- ✅ Smooth scrolling navigation
- ✅ Mobile-friendly hamburger menu
- ✅ Modern, clean UI design

## Getting Started

Simply open `index.html` in your web browser. No build process or dependencies required!

### Using a Local Server (Recommended)

For best results, use a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

## Project Structure

```
├── index.html      # Main HTML file
├── styles.css      # All CSS styles
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## Sections

1. **Header/Navbar** - Sticky navigation with mobile menu
2. **Hero Section** - Main banner with CTA buttons
3. **About Section** - Company overview
4. **Focus Areas** - 6 focus area cards (Cell Culture, Virology, etc.)
5. **Services** - What we do section with 7 services
6. **Internships & Training** - Training program information
7. **Equipment** - 9 equipment items in grid layout
8. **Why Choose Us** - 5 benefit cards
9. **Contact** - Contact information and form with validation
10. **Footer** - Quick links and contact info

## Technologies Used

- HTML5
- CSS3 (with CSS Variables)
- Vanilla JavaScript (ES6+)

## Customization

- Colors can be customized in `styles.css` using CSS variables in `:root`
- Component styles can be modified directly in `styles.css`
- Content can be updated in `index.html`
- Form validation logic is in `script.js`

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## Features Explained

### Mobile Menu
The hamburger menu automatically appears on screens smaller than 768px and provides smooth navigation.

### Form Validation
The contact form includes client-side validation for:
- Name (required)
- Email (required, valid email format)
- Phone (required, valid phone format)
- Message (required)

### Smooth Scrolling
All anchor links use smooth scrolling for better user experience.

### Responsive Design
The site uses a mobile-first approach with breakpoints at:
- Mobile: < 640px
- Tablet: 640px - 1024px
- Desktop: > 1024px
