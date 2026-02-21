# Bharath Portfolio

## Overview

A modern, responsive portfolio website showcasing expertise in web development, UI/UX design, and digital creativity. Built with pure HTML, CSS, and vanilla JavaScript, this portfolio demonstrates proficiency in creating performant, user-centric web applications.

## Key Features

- **Fully Responsive Design** – Optimized for desktop, tablet, and mobile devices
- **Theme Toggle** – Dark and light mode with persistent user preference storage
- **Smooth Animations** – Floating hero images, hover effects, and smooth transitions
- **Portfolio Filtering** – Filter projects by category (Web Development, Design, Photography)
- **Interactive Navigation** – Mobile hamburger menu with scroll-based active state indicators
- **Modern Design Patterns** – Glassmorphism effects with backdrop blur and gradient designs
- **Performance Optimized** – Single HTML file with no external framework dependencies

## Live Demo

View the portfolio online: [https://bharathkr8798.github.io/Bharath-Portfolio/](https://bharathkr8798.github.io/Bharath-Portfolio/)

## Project Highlights

| Category | Projects | Technologies |
|----------|----------|---------------|
| Web Development | Heaven Tours, Resume Builder, Voting Portal | HTML, CSS, JavaScript, React |
| Design | Yoga Creative, Spark Tank Posters | Adobe Photoshop, Illustrator, Canva |
| Photography | Sea Port, Beach Landscapes | Professional Photography |

## Technical Skills

- **Frontend Development:** HTML5, CSS3, JavaScript (ES6+)
- **Frameworks & Libraries:** React.js
- **Design Tools:** Adobe Creative Suite, Canva
- **Design Principles:** UI/UX Design, Responsive Design, Accessibility
- **Performance:** Optimization, SEO best practices

## Installation and Setup

Simply clone the repository and open `index.html` in your preferred web browser:

```bash
git clone https://github.com/Bharathkr8798/Bharath-Portfolio.git
cd Bharath-Portfolio
open index.html
```

No build tools or dependencies required.

## Usage

- **Browse Projects:** Navigate through the portfolio sections to view work samples
- **Filter Projects:** Click category buttons to filter projects by type
- **Toggle Theme:** Use the theme toggle to switch between light and dark modes (preference is saved)
- **Responsive Layout:** View on different screen sizes to see responsive design in action

## Technical Implementation

### Theme Persistence
User theme preference is automatically saved to browser localStorage and restored on subsequent visits:
```javascript
localStorage.setItem('theme', body.classList.contains('dark-mode') ? 'dark' : 'light');
```

### Active Navigation State
Intersection Observer API is used to detect viewport visibility and update active navigation states in real-time:
```javascript
const observer = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) setActive(entry.target.id);
  });
});
```

### Portfolio Filtering
Projects are filtered dynamically using category-based classification with smooth CSS transitions for enhanced user experience.

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Deployment

This project is deployed on GitHub Pages and automatically deploys on every push to the main branch.

## Contact

For inquiries or collaboration opportunities, please reach out through the contact section on the portfolio website.

---

**Last Updated:** February 2026
