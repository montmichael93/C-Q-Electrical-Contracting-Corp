# C Q Electrical Contracting Corp Website

A modern, responsive front-end website for C Q Electrical Contracting Corp.

## Features

- **Responsive Design**: Fully responsive layout that works on all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations and transitions
- **Multiple Pages**: 
  - Home page with hero section, services preview, testimonials
  - Services page with detailed service listings
  - About page with company story and values
  - Contact page with contact form
- **Interactive Elements**: 
  - Mobile-friendly navigation menu
  - Smooth scrolling
  - Form validation
  - Scroll animations

## File Structure

```
family-electric-website/
├── index.html          # Home page
├── services.html       # Services page
├── about.html          # About page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## Getting Started

1. **Clone or download** this repository to your local machine

2. **Open the website**:
   - Simply open `index.html` in your web browser
   - Or use a local development server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Navigate** to `http://localhost:8000` (or the port you specified)

## Customization

### Update Contact Information

Edit the contact details in all HTML files:
- Phone number: `917-335-6688`
- Email: `info@familyelectric.com`
- Address: `123 Main Street, Your City, ST 12345`

### Update Business Hours

Modify the business hours in the footer section of each HTML file.

### Change Colors

Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #FFB800;    /* Main brand color */
    --secondary-color: #1A1A1A;  /* Dark text color */
    /* ... other colors */
}
```

### Add Real Images

Replace the placeholder image divs with actual images:
```html
<!-- Replace this -->
<div class="image-placeholder">
    <span>⚡</span>
</div>

<!-- With this -->
<img src="path/to/your/image.jpg" alt="Description">
```

### Connect Contact Form

The contact form currently shows a success message. To connect it to a backend:

1. Set up a server endpoint to handle form submissions
2. Update the JavaScript in `script.js` (see the commented code in the form handler)
3. Add proper form validation and error handling

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and custom properties
- **JavaScript (Vanilla)**: No frameworks required
- **Google Fonts**: Inter font family

## License

This project is open source and available for use.

## Notes

- This is a front-end only website. No backend server is required to run it.
- The contact form is set up for demonstration. You'll need to connect it to a backend service for actual form submissions.
- All contact information, addresses, and business details should be updated to match your actual business information.
# C-Q-Electrical-Contracting-Corp.-
git remote set-url origin https://github.com/montmichael93/C-Q-Electrical-Contracting-Corp.git
