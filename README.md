# Davis Rowan V - Portfolio Website

A modern, responsive portfolio website showcasing my work as a Mechanical Engineering student.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Recruiter-first layout**: Designed for fast scanning (clear hierarchy, highlights first, concise bullets)
- **Sections**:
  - Hero (value proposition + contact)
  - Recruiter highlights (internship bullets)
  - Skills
  - Experience & certificates
  - Education timeline
  - Contact form

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- JavaScript (Vanilla JS)
- Google Fonts (Inter)

## Getting Started

1. **Open the website**:
   - Simply open `index.html` in your web browser
   - Or use a local server for better development experience

2. **Using a local server** (recommended):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```
   
   Then navigate to `http://localhost:8000` in your browser

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # Stylesheet
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Customization

### Updating Personal Information

Edit `index.html` to update:
- Name, title, and description in the hero section
- Recruiter highlights and internship bullets
- Skills
- Experience & certificates
- Education timeline
- Contact information


### Changing Colors

Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --primary-dark: #1e40af;
    --secondary-color: #3b82f6;
    /* ... */
}
```

### Adding Projects

Add project cards in the experience section or create a new projects section following the existing card structure.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contact

- **Email**: cadcamdavis@gmail.com
- **Phone**: _not listed publicly_
- **Location**: Chennai 600056, India

## License

This portfolio is open source and available for personal use.

---

Built with ❤️ by Davis Rowan V
