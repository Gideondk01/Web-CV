# Web-CV - Personal CV Website

A modern, responsive CV website built with HTML, CSS, and JavaScript. Perfect for showcasing your professional profile, experience, projects, and skills.

## Features

✨ **Fully Responsive** - Mobile-first design that works on all devices  
🎨 **Modern Design** - Clean and professional appearance  
⚡ **Fast Loading** - Pure HTML/CSS/JavaScript, no frameworks  
📱 **Mobile Menu** - Hamburger menu for mobile navigation  
🔗 **Smooth Navigation** - Smooth scrolling between sections  
🎯 **SEO Friendly** - Semantic HTML structure  

## Project Structure

```
Web-CV/
├── index.html       # Main HTML file with all sections
├── styles.css       # Responsive styling
├── script.js        # Interactive features (mobile menu, smooth scroll)
└── README.md        # This file
```

## Quick Start

1. **Open in Browser**: Simply open `index.html` in your web browser
2. **Customize Content**: Edit the sections in `index.html` with your own information
3. **Update Styling**: Modify colors and fonts in `styles.css` (CSS variables at the top)
4. **Deploy**: Upload all files to your web hosting

## Customization Guide

### Change Personal Information

Edit these sections in `index.html`:

- **Name & Title**: Update the hero section heading and logo
- **About Section**: Replace the about text and skills
- **Experience**: Update your job history in the timeline
- **Projects**: Add your portfolio projects
- **Contact**: Update email, phone, and social links

### Update Colors

Modify the CSS variables at the top of `styles.css`:

```css
:root {
    --primary-color: #2563eb;        /* Main blue */
    --secondary-color: #1e40af;      /* Darker blue */
    --text-dark: #1f2937;            /* Dark text */
    --text-light: #6b7280;           /* Light gray text */
    --bg-light: #f9fafb;             /* Light background */
    --bg-white: #ffffff;             /* White background */
}
```

### Add Social Media Links

In the contact section, update the social links with your actual URLs:

```html
<a href="https://github.com/yourprofile" target="_blank">GitHub</a>
<a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
<a href="https://twitter.com/yourprofile" target="_blank">Twitter</a>
```

## Sections Overview

### Hero Section
- Eye-catching introduction with title and CTA button

### About Section
- Personal bio and key skills displayed in a grid

### Experience Section
- Timeline view of your professional experience
- Company names and job responsibilities

### Projects Section
- Showcase your portfolio projects
- Each project includes description and tech stack tags

### Contact Section
- Contact information and social media links
- Multiple ways for people to reach you

## Browser Support

Works on all modern browsers:
- Chrome/Chromium
- Firefox
- Safari
- Edge

## Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## Tips for Best Results

1. **Keep it Updated**: Regularly update your experience and projects
2. **High Quality Content**: Use clear, professional language
3. **Active Links**: Make sure all social links are correct
4. **Fresh Projects**: Show your most recent and impressive work
5. **Mobile Testing**: Always test on mobile devices before deploying

## Deployment Options

- **GitHub Pages**: Free hosting with Git
- **Netlify**: Simple deployment with auto-updates
- **Vercel**: High-performance static hosting
- **Any Web Host**: FTP upload to any standard hosting provider

## License

Free to use and modify for personal use.