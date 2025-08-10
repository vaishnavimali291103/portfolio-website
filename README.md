# Vaishnavi Mali - Portfolio Website

## Overview
This is a personal portfolio website for Vaishnavi Mali, a final-year B.Tech student and aspiring software developer. The website showcases her skills, experience, education, and projects in a modern, responsive design.

## Features
- Responsive design that works on all devices (desktop, tablet, mobile)
- Interactive elements with smooth animations
- Sections for About, Education, Experience, Skills, Projects, and Contact
- Modern UI with a clean, professional look
- Typewriter effect on the homepage
- Contact form for easy communication
- SVG illustrations for visual appeal

## Technologies Used
- HTML5
- CSS3 (with flexbox and grid layouts)
- JavaScript (vanilla, no frameworks)
- SVG for illustrations
- Font Awesome for icons
- Google Fonts (Poppins)

## File Structure
```
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── images/             # Image directory
│   ├── hero-bg.svg     # Hero section background
│   ├── fertilizer-app.svg  # Project illustration
│   └── healthcare-system.svg  # Project illustration
└── README.md           # This file
```

## Customization Guide

### Changing Personal Information
To update personal information, edit the relevant sections in `index.html`:

1. **Name and Title**: Update in the hero section and about section
2. **Contact Information**: Update in the about section and contact section
3. **Education Details**: Modify the timeline items in the education section
4. **Experience**: Update the experience cards with your work history
5. **Skills**: Adjust skill levels and add/remove skills as needed
6. **Projects**: Update project details and links

### Styling Customization
To change the visual appearance:

1. **Colors**: Edit the CSS variables at the top of `styles.css`:
   ```css
   :root {
       --primary-color: #6c63ff;
       --secondary-color: #f50057;
       /* other variables */
   }
   ```

2. **Fonts**: Replace the Google Font import in `index.html` and update the font-family in `styles.css`

3. **Layout**: Adjust the responsive breakpoints in the media queries at the bottom of `styles.css`

### Adding Projects
To add a new project:

1. Copy an existing project card in the projects section of `index.html`
2. Update the content with your project details
3. Create a new SVG illustration in the images folder if needed
4. Update the image path in the project card

## Browser Compatibility
This website is compatible with all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## Future Improvements
- Add a blog section
- Implement dark/light mode toggle
- Add more interactive elements
- Integrate a backend for the contact form

## License
Feel free to use this template for your own portfolio with appropriate attribution.

---

© 2024 Vaishnavi Mali. All Rights Reserved.