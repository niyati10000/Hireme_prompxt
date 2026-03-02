🌟 Niyati Bansal's Portfolio Website
A stunning, interactive portfolio website with aurora effects, particle animations, and 3D tilt features. Built with pure HTML, CSS, and JavaScript.

https://via.placeholder.com/800x400/0a192f/00ffff?text=Niyati+Bansal+Portfolio

✨ Live Demo
🔗 GitHub Pages URL: https://niyati10000.github.io/Hireme_prompxt/

🎯 Features
🎨 Visual Effects
Dynamic Aurora Background - Moving gradients with layered light effects

Particle.js Integration - Floating particles with interactive grab effect

3D Tilt Card - Main card rotates based on mouse position (max ±10°)

Glass Morphism - Blurred, semi-transparent card with neon borders

Custom Cursor Effects - Interactive elements respond to hover

📱 Content Sections
Profile Header - Name, role, education, and avatar

Terminal-style Bio - Typewriter effect showcasing key achievements

Skills Cloud - Interactive skill chips with hover effects

Work Experience - Detailed internship descriptions

Featured Projects - 3 major projects with tech stacks

Achievements Grid - Hackathon wins and recognitions

Positions of Responsibility - Leadership roles

Social Links - GitHub, LinkedIn, Twitter buttons

🚀 Project Cards
Project	Tech Stack	Links
E-Bookshop	HTML5, CSS3, JavaScript, JWT	GitHub only
ClinicConnect	Python, Flask, SQLite, Twilio	Live Demo + GitHub
LexAI	Python, Flask, BERT, Gemini, Chart.js	GitHub only
📄 Resume Features
Hardcoded Resume Download - Generates PDF with complete resume content

Terminal Bio - Shows real resume highlights (GPA, internships, skills)

Skills Cloud - Visual representation of all technical skills from resume

🛠️ Technologies Used
Frontend
HTML5

CSS3 (Animations, Grid, Flexbox, 3D transforms)

Vanilla JavaScript

particles.js

Design Elements
Glass morphism (backdrop-filter: blur)

CSS keyframe animations

Gradient overlays

Responsive grid layouts

Custom cursor animations

📁 File Structure
text
Niyati_promptX/
│
├── hire_me.html          # Main portfolio file (can be renamed to index.html)
├── README.md              # This documentation file
└── .git/                  # Git repository (hidden)
🔧 Hidden Features & Easter Eggs
🎭 Easter Eggs
Particle Interaction - Hover over particles to see them connect

Click Particles - Click anywhere on particle background to create new particles

3D Tilt Secret - Move mouse to extreme corners for max 10° rotation

Cursor Blink - Terminal cursor has a subtle glow animation

Skill Chip Glow - Hover over skills for cyan glow effect

⚙️ Technical Hidden Features
Dynamic Typewriter - Automatically types bio lines with timing delays

Resume Generator - Creates PDF on-the-fly with complete resume data

Aurora Layers - 3 separate overlay animations blending together

Responsive Grid - Projects grid auto-adjusts from 3 to 2 to 1 column

Memory-efficient Particles - Optimized particle count (65) for performance

🚀 How to Use
Local Development
Clone the repository

bash
git clone https://github.com/niyati10000/Hireme_prompxt.git
Open hire_me.html in your browser

Make changes and refresh to see updates

Deploy to GitHub Pages
Rename hire_me.html to index.html

Push to GitHub

Go to repository Settings → Pages

Select main branch as source

Your site will be live at https://[username].github.io/[repo-name]/

🎨 Customization Guide
Change Colors
css
/* In the <style> section, modify these values */
body::before {
  background: radial-gradient(circle at 30% 40%, rgba(90, 200, 250, 0.35) 0%, ...);
  /* Change RGB values for different aurora colors */
}
Update Projects
Find the .projects-grid section and modify:

html
<div class="project-card">
  <h3>Your Project Name</h3>
  <p>Description</p>
  <div class="project-tech">
    <span>Tech1</span><span>Tech2</span>
  </div>
</div>
Change Resume Content
Update the generateResumePDF() function with your latest information.

📱 Responsive Design
The portfolio is fully responsive and works on:

Desktop (1200px+): Full 3-column layout

Tablet (768px - 1199px): 2-column layout

Mobile (<768px): 1-column stacked layout

⚡ Performance Optimizations
Lightweight animations using CSS transforms

Optimized particle count for smooth performance

Lazy-loaded external libraries

Efficient CSS selectors

Minimal JavaScript footprint

🔐 Security Features
No external dependencies except particles.js

Hardcoded resume data (no API calls)

Safe HTML/CSS/JS - no eval() or dangerous functions

All links open in _blank with proper security

🐛 Known Issues & Fixes
Issue	Solution
Particles not showing	Check if particles.js loaded correctly
3D tilt not working	Ensure mouse is over card area
Download button not working	Browser may block popups - allow downloads
Aurora animation lag	Reduce opacity or particle count
📝 To-Do / Future Enhancements
Add dark/light mode toggle

Include blog section

Add contact form with EmailJS

Create project carousel

Add more interactive easter eggs

Include testimonials section

🤝 Contributing
Feel free to fork this project and customize it for your own portfolio. If you find bugs or have suggestions, open an issue!

📄 License
MIT License - feel free to use this for your own portfolio!

📞 Contact
Niyati Bansal

GitHub: @niyati10000

LinkedIn: Niyati Bansal

Email: niyati.b@example.edu

🎉 Acknowledgments
particles.js library for background effects

Inspired by modern glass-morphism designs

Aurora effects from CSS gradient experiments

Made with 💙 by Niyati Bansal

