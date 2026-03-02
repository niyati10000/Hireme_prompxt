# 🌟 Niyati Bansal's Portfolio Website

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)

A stunning, interactive portfolio website featuring dynamic aurora effects, particle animations, and 3D tilt interactivity. Built entirely with pure HTML, CSS, and vanilla JavaScript for maximum performance and zero bloat.

**✨ Live Demo:** [View Portfolio Here](https://niyati10000.github.io/Hireme_prompxt/)

---

## 🎯 Key Features

### 🎨 Visual & Interactive Effects
* **Dynamic Aurora Background:** Moving gradients with layered light effects.
* **Particle.js Integration:** Floating particles with an interactive grab effect on hover.
* **3D Tilt Card:** The main container dynamically rotates based on mouse position (max ±10°).
* **Glass Morphism:** Blurred, semi-transparent card design with neon borders.
* **Custom Cursor:** Interactive elements respond seamlessly to hover states.

### 📱 Content Sections
* **Profile Header:** Clean display of name, role, education, and avatar.
* **Terminal-style Bio:** Typewriter effect showcasing key achievements and introductions.
* **Skills Cloud:** Interactive skill chips with glowing hover effects.
* **Work Experience:** Detailed descriptions of internships and professional roles.
* **Featured Projects:** Highlights of 3 major projects along with their tech stacks.
* **Achievements & PORs:** Grids detailing hackathon wins, recognitions, and leadership roles.

---

## 🚀 Featured Projects

| Project | Tech Stack | Links |
| :--- | :--- | :--- |
| **E-Bookshop** | HTML5, CSS3, JavaScript, JWT | GitHub only |
| **ClinicConnect** | Python, Flask, SQLite, Twilio | Live Demo + GitHub |
| **LexAI** | Python, Flask, BERT, Gemini, Chart.js | GitHub only |

---

## 📄 Dynamic Resume Features
* **On-the-Fly PDF Generation:** A hardcoded resume download button that generates a PDF containing complete resume content directly from the browser.
* **Terminal Bio:** Displays real resume highlights (GPA, internships, skills) dynamically.
* **Skills Cloud:** A visual, interactive representation of all technical skills extracted from the resume.

---

## 🛠️ Technologies Used

* **Frontend:** HTML5, CSS3 (Animations, Grid, Flexbox, 3D transforms), Vanilla JavaScript.
* **Libraries:** `particles.js` (for background effects).
* **Design Elements:** Glass morphism (`backdrop-filter: blur`), CSS keyframe animations, gradient overlays, responsive grid layouts.

---

## 📁 File Structure

```text
Niyati_promptX/
│
├── hire_me.html          # Main portfolio file (can be renamed to index.html for deployment)
├── README.md             # Project documentation
└── .git/                 # Git repository (hidden)🚀 How to Use & DeployLocal DevelopmentClone the repository:Bashgit clone [https://github.com/niyati10000/Hireme_prompxt.git](https://github.com/niyati10000/Hireme_prompxt.git)
cd Hireme_prompxt
Open hire_me.html directly in your web browser.Make your desired changes and refresh the browser to see updates.Deploy to GitHub PagesRename hire_me.html to index.html.Commit and push the changes to your GitHub repository.Go to your repository Settings → Pages.Select the main branch as your source and save.Your site will be live at: https://[username].github.io/[repo-name]/🎨 Customization GuideChange Aurora ColorsLocate the <style> section and modify the background gradient values:CSSbody::before {
  background: radial-gradient(circle at 30% 40%, rgba(90, 200, 250, 0.35) 0%, ...);
  /* Adjust RGB values to customize the aurora colors */
}
Update ProjectsFind the .projects-grid section in the HTML and modify the content:HTML<div class="project-card">
  <h3>Your Project Name</h3>
  <p>Project Description</p>
  <div class="project-tech">
    <span>Tech 1</span><span>Tech 2</span>
  </div>
</div>
Note: To update the downloadable resume content, modify the data inside the generateResumePDF() JavaScript function.🔧 Hidden Features & Easter Eggs🎭 Particle Interaction: Hover over the background particles to see them connect, or click anywhere to spawn new ones.🤫 3D Tilt Secret: Move your mouse to the extreme corners of the card to witness the maximum 10° rotation.✨ UI Details: Watch for the subtle glow animation on the terminal cursor and the cyan glow effect when hovering over skill chips.⚙️ Under the Hood: Features a dynamic typewriter with timing delays, memory-efficient particle rendering (capped at 65 particles), and 3 separate aurora layers blending seamlessly.📱 Responsiveness & PerformanceDesktop (1200px+): Full 3-column layout.Tablet (768px - 1199px): Balanced 2-column layout.Mobile (<768px): Stacked 1-column layout for easy reading.Optimizations: Lightweight CSS transforms, lazy-loaded external libraries, minimal JS footprint, and no external dependencies (aside from particles.js).🐛 Known Issues & TroubleshootingIssueSolutionParticles not showingCheck if the particles.js library has loaded correctly.3D tilt not workingEnsure the mouse pointer is actively over the main card area.Download button failsYour browser may be blocking popups. Allow downloads for the site.Aurora animation lagReduce the opacity or lower the particle count in the JS config.🔮 Future Enhancements[ ] Add dark/light mode toggle.[ ] Include a dedicated blog section.[ ] Add a functional contact form using EmailJS.[ ] Create a project carousel for better mobile viewing.[ ] Include a testimonials section.🤝 ContributingFeel free to fork this project and customize it for your own portfolio! If you find bugs or have feature suggestions, please open an issue or submit a pull request.📄 LicenseThis project is licensed under the MIT License - feel free to use, modify, and distribute this for your own portfolio!📞 ContactNiyati BansalGitHub: @niyati10000LinkedIn: Niyati BansalEmail: niyati.b@example.eduInspired by modern glass-morphism designs. Made with 💙 by Niyati Bansal.
