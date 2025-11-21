# FountWolff English

A professional website for FountWolff English - Online English classes for career professionals.

## About

FountWolff English offers advanced English instruction tailored to professionals looking to enhance their careers. Founded and taught by Daniel Wolff, a former New York City legal proofreader with a solid educational background in pedagogy.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Navigation**: Smooth scrolling and mobile-friendly menu
- **Contact Form**: Integrated contact form with validation
- **Multiple Class Options**: Group classes, one-on-one lessons, and business English courses

## File Structure

```
fountwolff_english/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── assets/             # Images and media files
│   └── teacher-photo.jpg  # Add teacher photo here
└── README.md           # This file
```

## Setup Instructions

1. **Add Images**: Place the teacher photo and any other images in the `assets/` folder
   - Recommended: `teacher-photo.jpg` for the About section

2. **Open the Website**: Simply open `index.html` in a web browser

3. **Customize Content**: 
   - Edit contact information in `index.html`
   - Adjust colors in `styles.css` (see CSS variables at the top)
   - Modify class descriptions as needed

## Customization

### Colors
The color scheme can be easily modified in `styles.css` by changing the CSS variables:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    /* ... other colors */
}
```

### Adding New Sections
To add a new section, follow the existing pattern in `index.html`:

1. Add a `<section>` with a unique ID
2. Include it in the navigation menu
3. Style it in `styles.css`

### Contact Form Integration
The contact form currently displays a success message. To integrate with a backend:

1. Update the form submission handler in `script.js`
2. Add your email service API or server endpoint
3. Handle the response appropriately

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Poppins)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Future Enhancements

- [ ] Add blog section for English learning tips
- [ ] Integrate payment system for class enrollment
- [ ] Add student login portal
- [ ] Include video testimonials
- [ ] Add live chat support

## License

© 2025 FountWolff English. All rights reserved.

## Contact

For questions about the website or classes, visit [https://fountwolffenglish.com](https://fountwolffenglish.com)
