Bharath's Portfolio ✨
A modern, responsive portfolio website showcasing creative web development, UI/UX design, and digital creativity. Built with pure HTML, CSS, and vanilla JavaScript.

🚀 Features
Fully Responsive - Perfect on desktop, tablet, and mobile

Dark/Light Mode - Automatic theme toggle with localStorage

Smooth Animations - Floating hero image, hover effects, and transitions

Portfolio Filter - Filter projects by category (Web, Creatives, Photography)

Interactive Navigation - Mobile hamburger menu + scroll-based active states

Modern Glassmorphism - Backdrop blur effects and gradient designs

Performance Optimized - Single HTML file, no external dependencies beyond CDNs

📱 Live Demo
🔗 Deployed on GitHub Pages (https://bharathkr8798.github.io/Bharath-Portfolio/)

🎨 Portfolio Highlights
| Category        | Projects                                    | Tech Used                     |
| --------------- | ------------------------------------------- | ----------------------------- |
| Web Development | Heaven Tours, Resume Builder, Voting Portal | HTML, CSS, JS, React          |
| Creative Design | Yoga Creative, Spark Tank posters           | Photoshop, Illustrator, Canva |
| Photography     | Sea Port, Beach View                        | Professional Photography      |

💼 Skills
hero-image.png
about-image.png
Web HTT.png
web 02.png
web 3.jpg
ı s for everybody (A3).jpg
Spark Tank Guest Creative.jpg
Img 1.jpg
pic.jpeg

🌟 Key Features Explained
1. Theme Toggle // Persists user preference in localStorage
localStorage.setItem('theme', body.classList.contains('dark-mode') ? 'dark' : 'light');
2. Smooth Scrolling Navigation // Intersection Observer for active nav states
const observer = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) setActive(entry.target.id);
  });
});
3. Portfolio Filtering
Click category buttons to filter projects

Smooth transitions and hover effects

Mobile-optimized grid layout







