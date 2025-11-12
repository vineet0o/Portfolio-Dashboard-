# Vineet Kumar - Portfolio Website

A modern, responsive portfolio website showcasing data analytics projects, skills, and achievements.

## Features

- **Modern Design**: Clean, professional layout with tech-inspired color scheme
- **Responsive**: Fully responsive design that works on all devices
- **Smooth Animations**: Subtle animations and transitions for better UX
- **Sections Included**:
  - Home/Hero with introduction
  - About Me
  - Education
  - Skills
  - Projects
  - Certifications
  - Achievements
  - Resume Download
  - Contact Form

## Setup Instructions

1. **Replace Resume PDF**: 
   - Replace `assets/resume.pdf` with your actual resume PDF file

2. **Update Social Media Links**:
   - Open `index.html`
   - Find the Contact section (around line 400)
   - Update the LinkedIn, GitHub, and HackerRank URLs with your actual profile links

3. **Run the Website**:
   ```bash
   python -m http.server 8000
   ```
   Then open `http://localhost:8000` in your browser

## Customization

- **Colors**: Edit CSS variables in `styles.css` (lines 7-18)
- **Content**: All content is in `index.html` - easy to update
- **Contact Form**: Currently shows an alert. To enable email functionality, you can:
  - Use a service like Formspree (uncomment the code in `script.js`)
  - Set up your own backend API

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter)

## Browser Support

Works on all modern browsers (Chrome, Firefox, Safari, Edge).


