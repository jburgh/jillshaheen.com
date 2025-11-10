# jillshaheen.com

Professional portfolio website for Jill Shaheen - Technical Writer, Content Strategist, and Team Leader.

## Overview

This is a single-page portfolio website showcasing professional experience, technical skills, education, and projects. The site features a modern, responsive design with smooth scrolling navigation and interactive elements.

## Live Site

Visit the live portfolio at: [jillshaheen.com](https://jillshaheen.com)

## Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Smooth Scrolling Navigation**: Fixed navigation bar with smooth scroll-to-section functionality
- **Interactive Timeline**: Animated professional experience timeline
- **Skills Showcase**: Technical skills organized by category with icons
- **Projects Gallery**: Dynamic project cards with modal detail views
- **Contact Integration**: Direct email and LinkedIn profile links
- **Modern UI**: Clean, professional design with mid-century modern typography

## Technologies Used

### Frontend
- HTML5
- CSS3 (Custom styling)
- JavaScript (jQuery)
- Bootstrap 5.3.0
- Font Awesome 6.4.0
- Google Fonts (Oswald, Merriweather)

### Tools & Libraries
- jQuery 3.7.0
- Bootstrap Bundle (JS components)
- Custom animations and transitions

## Project Structure

```
jillshaheen.com/
├── index.html          # Main HTML file
├── styles.css          # Custom CSS styles
├── script.js           # JavaScript functionality
├── favicon_io/         # Favicon files
├── img/                # Image assets
│   └── profile.jpg     # Profile photo
├── projects/           # Project images and assets
│   ├── emr-console-thumb.png
│   ├── error-thumb.png
│   ├── notebooks.png
│   └── s3.png
├── profile.jpg         # Profile image (main)
├── profile2.jpg        # Alternate profile image
└── README.md           # This file
```

## Sections

1. **Hero Section**: Introduction with profile photo and call-to-action buttons
2. **About**: Professional summary and philosophy
3. **Professional Experience**: Timeline of work history including:
   - AWS (2022 - Present)
   - SugarCRM (2014 - 2022)
   - Aerotech Inc. (2007 - 2014)
4. **Technical Skills**: Organized by category:
   - Documentation
   - Development
   - AI/Automation
   - Design/Media
   - Project Management
   - Marketing/CRM
5. **Education**: Academic credentials from Duquesne University
6. **Projects**: Portfolio of notable work and achievements
7. **Contact**: Email and LinkedIn connection options

## Local Development

To run this website locally:

1. Clone the repository:
```bash
git clone https://github.com/jburgh/jillshaheen.com.git
cd jillshaheen.com
```

2. Open `index.html` in your web browser, or use a local server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js http-server
npx http-server
```

3. Navigate to `http://localhost:8000` (or the appropriate port)

## Customization

### Updating Content

- **Personal Information**: Edit the content in `index.html` within each section
- **Styles**: Modify `styles.css` for design changes
- **Images**: Replace images in the `img/` and `projects/` directories
- **Projects**: Add project data in `script.js` for dynamic loading

### Color Scheme

The site uses a professional color palette that can be customized in `styles.css`:
- Primary colors defined in CSS custom properties
- Mid-century modern inspired design elements
- Accessible color contrast ratios

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Optimized images for web
- Minified external libraries via CDN
- Efficient CSS animations
- Lazy loading for project images

## Contact

- **Email**: jillshaheen@gmail.com
- **LinkedIn**: [linkedin.com/in/jillshaheen](https://www.linkedin.com/in/jillshaheen)

## License

© 2025 Jill Shaheen. All rights reserved.

## Acknowledgments

- Bootstrap for responsive framework
- Font Awesome for icons
- Google Fonts for typography
