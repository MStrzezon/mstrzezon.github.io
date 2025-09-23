---
layout: default
---

<div class="hero-section">
  <h1>👋 Hello, I'm Michał Strzeżoń</h1>
  <p class="hero-subtitle">Software Engineer with AI/ML knowledge</p>
</div>

---

## 🚀 Featured Projects

<div class="projects-grid">
  
  <div class="project-card">
    <div class="project-header">
      <h3>✈️ Flylytics</h3>
      <div class="project-status">🚧 In Development</div>
    </div>
    <p>Advanced ADS-B trajectory analysis platform for aviation data visualization and analytics.</p>
    <div class="tech-stack">
      <span class="tech-tag">Python</span>
      <span class="tech-tag">Streamlit</span>
      <span class="tech-tag">Plotly</span>
      <span class="tech-tag">GeoPandas</span>
    </div>
    <div class="project-links">
      <a href="https://github.com/mstrzezon/flylytics" target="_blank">GitHub</a>
      <a href="/projects/flylytics">Learn More</a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-header">
      <h3>⚽ QuickMatch</h3>
      <div class="project-status completed">✅ Completed</div>
    </div>
    <p>Full-stack web application for organizing football matches with real-time booking system and user management.</p>
    <div class="tech-stack">
      <span class="tech-tag">Django</span>
      <span class="tech-tag">React</span>
      <span class="tech-tag">REST API</span>
      <span class="tech-tag">MySQL</span>
    </div>
    <div class="project-links">
      <a href="https://github.com/TripleM-MMM/QuickMatch" target="_blank">GitHub</a>
      <a href="/projects/quickmatch">Learn More</a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-header">
      <h3>🃏 Socket Poker Game</h3>
      <div class="project-status completed">✅ Completed</div>
    </div>
    <p>Multi-player poker game with client-server architecture, socket communication and comprehensive game protocol.</p>
    <div class="tech-stack">
      <span class="tech-tag">Java</span>
      <span class="tech-tag">Sockets</span>
      <span class="tech-tag">Maven</span>
      <span class="tech-tag">OOP</span>
    </div>
    <div class="project-links">
      <a href="https://github.com/mstrzezon/Poker" target="_blank">GitHub</a>
      <a href="/projects/poker">Learn More</a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-header">
      <h3>📄 JPK Generator</h3>
      <div class="project-status completed">✅ Completed</div>
    </div>
    <p>Java tool for converting Excel/CSV files to JPK XML format for Polish tax reporting compliance.</p>
    <div class="tech-stack">
      <span class="tech-tag">Java</span>
      <span class="tech-tag">JAXB</span>
      <span class="tech-tag">Apache POI</span>
      <span class="tech-tag">XML</span>
    </div>
    <div class="project-links">
      <a href="https://github.com/mstrzezon/generator_jpk" target="_blank">GitHub</a>
      <a href="/projects/jpk-generator">Learn More</a>
    </div>
  </div>

  <div class="project-card">
    <div class="project-header">
      <h3>🔬 Physicist's Toolbox</h3>
      <div class="project-status completed">✅ Completed</div>
    </div>
    <p>Intuitive physics calculation app covering kinematics, dynamics, thermodynamics, and more.</p>
    <div class="tech-stack">
      <span class="tech-tag">Physics</span>
      <span class="tech-tag">Mathematics</span>
      <span class="tech-tag">Educational</span>
    </div>
    <div class="project-links">
      <a href="/projects/physicist-toolbox">Learn More</a>
    </div>
  </div>

</div>

---

## 📬 Get In Touch

I'm always interested in discussing new opportunities, collaboration projects, or just chatting about technology and aviation analytics!

<div class="contact-links">
  <a href="mailto:michal.m.strzezon@gmail.com" class="contact-btn">
    📧 Email Me
  </a>
  <a href="https://github.com/mstrzezon" target="_blank" class="contact-btn">
    🐙 GitHub
  </a>
  <a href="https://www.linkedin.com/in/micha%C5%82-strze%C5%BCo%C5%84-a6128a223/" target="_blank" class="contact-btn">
    💼 LinkedIn
  </a>
</div>

---

<div class="footer">
  <p>© 2025 Michał Strzeżoń • Built with Jekyll & ❤️</p>
</div>

<style>
/* Custom Styles for Homepage */
.hero-section {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  border-radius: 16px;
  margin-bottom: 4rem;
  box-shadow: 0 10px 30px rgba(102, 126, 234, 0.3);
}


/* Education Timeline */
.education-timeline {
  margin: 2rem 0;
}

.education-item {
  background: linear-gradient(135deg, #f8f9fa 0%, #ffffff 100%);
  border-radius: 16px;
  padding: 2.5rem;
  margin-bottom: 2rem;
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.06);
  border-left: 5px solid #28a745;
  transition: all 0.3s ease;
  position: relative;
}

.education-item:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 35px rgba(0, 0, 0, 0.12);
}

.education-item::before {
  content: '';
  position: absolute;
  left: -8px;
  top: 2rem;
  width: 16px;
  height: 16px;
  background: #28a745;
  border-radius: 50%;
  border: 3px solid white;
  box-shadow: 0 2px 8px rgba(40, 167, 69, 0.3);
}

.education-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 1rem;
  flex-wrap: wrap;
  gap: 1rem;
}

.education-header h4 {
  margin: 0;
  color: #2c3e50;
  font-size: 1.3rem;
  font-weight: 600;
  flex: 1;
  min-width: 300px;
}

.education-period {
  background: linear-gradient(135deg, #e3f2fd 0%, #f3e5f5 100%);
  color: #1976d2;
  padding: 6px 16px;
  border-radius: 20px;
  font-size: 0.9rem;
  font-weight: 600;
  white-space: nowrap;
  border: 1px solid #bbdefb;
}

.education-institution {
  color: #28a745;
  font-weight: 600;
  font-size: 1.1rem;
  margin-bottom: 1.5rem;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

.education-details {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

.education-row {
  display: flex;
  align-items: flex-start;
  gap: 1rem;
  padding: 0.75rem 0;
  border-bottom: 1px solid #f0f2f5;
}

.education-row:last-child {
  border-bottom: none;
}

.education-row .label {
  font-weight: 600;
  color: #495057;
  min-width: 120px;
  flex-shrink: 0;
}

.education-row .value {
  color: #2c3e50;
  font-weight: 500;
  flex: 1;
}

.grade-excellent {
  background: linear-gradient(135deg, #28a745, #20c997);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  font-weight: 700;
  font-size: 1.1rem;
}

.research-group {
  display: inline-block;
  background: #e3f2fd;
  color: #1976d2;
  padding: 4px 12px;
  border-radius: 16px;
  font-size: 0.9rem;
  font-weight: 600;
  margin-right: 0.5rem;
  margin-bottom: 0.25rem;
  border: 1px solid #bbdefb;
}

/* Education highlights */
.education-highlights {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 12px;
  margin: 2rem 0;
  border-left: 5px solid #28a745;
}

.education-highlights h4 {
  color: #2c3e50;
  margin-bottom: 1rem;
}

.education-highlights ul {
  list-style: none;
  padding: 0;
}

.education-highlights li {
  padding: 0.5rem 0;
  color: #495057;
  border-bottom: 1px solid #e9ecef;
}

.education-highlights li:last-child {
  border-bottom: none;
}

.education-highlights li::before {
  content: '🎓';
  margin-right: 0.5rem;
}

.hero-section h1 {
  font-size: 3rem;
  font-weight: 700;
  margin-bottom: 1rem;
  color: white;
}

.hero-subtitle {
  font-size: 1.5rem;
  font-weight: 400;
  margin: 1rem 0;
  opacity: 0.95;
  color: white;
}

.hero-description {
  font-size: 1.2rem;
  opacity: 0.9;
  max-width: 700px;
  margin: 1.5rem auto 2.5rem auto;
  line-height: 1.7;
  color: white;
}

.hero-buttons {
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}

.btn {
  display: inline-block;
  padding: 14px 28px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
  font-size: 1.1rem;
  transition: all 0.3s ease;
  border: 2px solid transparent;
  min-width: 160px;
  text-align: center;
}

.btn-primary {
  background: #28a745;
  color: white;
  border-color: #28a745;
}

.btn-primary:hover {
  background: #218838;
  border-color: #218838;
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(40, 167, 69, 0.4);
  text-decoration: none;
  color: white;
}

.btn-secondary {
  background: transparent;
  color: white;
  border-color: white;
}

.btn-secondary:hover {
  background: white;
  color: #667eea;
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(255, 255, 255, 0.3);
  text-decoration: none;
}

/* Projects */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(400px, 1fr));
  gap: 2.5rem;
  margin: 3rem 0;
}

.project-card {
  background: white;
  border-radius: 16px;
  padding: 2.5rem;
  box-shadow: 0 8px 25px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
  border: 1px solid #f0f2f5;
}

.project-card:hover {
  transform: translateY(-8px);
  box-shadow: 0 15px 40px rgba(0, 0, 0, 0.15);
}

.project-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 1.5rem;
}

.project-header h3 {
  margin: 0;
  color: #2c3e50;
  font-size: 1.4rem;
  font-weight: 600;
}

.project-status {
  font-size: 0.85rem;
  padding: 6px 12px;
  border-radius: 20px;
  background: #fff3cd;
  color: #856404;
  font-weight: 600;
  border: 1px solid #ffeaa7;
}

.project-status.completed {
  background: #d4edda;
  color: #155724;
  border-color: #c3e6cb;
}

.tech-stack {
  margin: 1.5rem 0;
  display: flex;
  flex-wrap: wrap;
  gap: 0.5rem;
}

.tech-tag {
  background: #f8f9fa;
  color: #495057;
  padding: 6px 14px;
  border-radius: 20px;
  font-size: 0.9rem;
  font-weight: 500;
  border: 1px solid #e9ecef;
  transition: all 0.3s ease;
}

.tech-tag:hover {
  background: #667eea;
  color: white;
  border-color: #667eea;
}

.project-links {
  margin-top: 2rem;
  display: flex;
  gap: 1rem;
}

.project-links a {
  color: #667eea;
  text-decoration: none;
  font-weight: 600;
  padding: 8px 16px;
  border-radius: 6px;
  transition: all 0.3s ease;
  border: 1px solid transparent;
}

.project-links a:hover {
  background: #667eea;
  color: white;
  border-color: #667eea;
  text-decoration: none;
}

/* Skills */
.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 2rem;
  margin: 3rem 0;
}

.skill-category {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 12px;
  border-left: 5px solid #667eea;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.05);
  transition: all 0.3s ease;
}

.skill-category:hover {
  transform: translateY(-2px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
}

.skill-category h4 {
  margin-top: 0;
  color: #2c3e50;
  font-size: 1.3rem;
  margin-bottom: 1.5rem;
}

.skill-category ul {
  list-style: none;
  padding: 0;
  margin: 0;
}

.skill-category li {
  padding: 0.75rem 0;
  border-bottom: 1px solid #e9ecef;
  font-size: 1.05rem;
  color: #495057;
}

.skill-category li:last-child {
  border-bottom: none;
}

/* Contact */
.contact-links {
  display: flex;
  flex-wrap: wrap;
  gap: 1.5rem;
  justify-content: center;
  margin: 3rem 0;
}

.contact-btn {
  display: inline-flex;
  align-items: center;
  gap: 0.5rem;
  padding: 14px 24px;
  background: #667eea;
  color: white;
  text-decoration: none;
  border-radius: 8px;
  transition: all 0.3s ease;
  font-weight: 600;
  border: 2px solid #667eea;
  min-width: 150px;
  justify-content: center;
}

.contact-btn:hover {
  background: #5a6fd8;
  border-color: #5a6fd8;
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(102, 126, 234, 0.3);
  text-decoration: none;
  color: white;
}

/* Responsive */
@media (max-width: 768px) {
  .hero-section {
    padding: 3rem 1.5rem;
    margin-bottom: 3rem;
  }
  
  .hero-section h1 {
    font-size: 2.2rem;
  }
  
  .hero-subtitle {
    font-size: 1.3rem;
  }
  
  .hero-description {
    font-size: 1.1rem;
  }
  
  .hero-buttons {
    flex-direction: column;
    align-items: center;
  }
  
  .btn {
    width: 100%;
    max-width: 250px;
  }
  
  .projects-grid {
    grid-template-columns: 1fr;
    gap: 2rem;
  }
  
  .project-card {
    padding: 2rem;
  }
  
  .skills-grid {
    grid-template-columns: 1fr;
  }
  
  .contact-links {
    flex-direction: column;
    align-items: center;
  }
  
  .contact-btn {
    width: 100%;
    max-width: 250px;
  }
  
  .project-header {
    flex-direction: column;
    align-items: flex-start;
    gap: 1rem;
  }
  
  .project-links {
    flex-direction: column;
    gap: 0.5rem;
  }
  
  .project-links a {
    text-align: center;
  }
  
  /* Experience responsive */
  .experience-item {
    padding: 2rem;
  }
  
  .experience-header {
    flex-direction: column;
    align-items: flex-start;
    gap: 0.5rem;
  }
  
  .experience-header h3 {
    font-size: 1.2rem;
    min-width: auto;
  }
  
  .experience-period {
    align-self: flex-start;
  }
  
  .experience-description li::before {
    left: -0.5rem;
  }
  
  .education-highlights {
    padding: 1.5rem;
  }
}

#projects,
#about,
#experience {
  scroll-margin-top: 80px;
}

/* Mobile Responsiveness */
@media (max-width: 768px) {
  .education-item {
    padding: 1.5rem;
    margin-left: 1rem;
  }
  
  .education-header {
    flex-direction: column;
    align-items: flex-start;
    gap: 0.5rem;
  }
  
  .education-header h4 {
    min-width: auto;
    font-size: 1.2rem;
  }
  
  .education-period {
    align-self: flex-start;
  }
  
  .education-row {
    flex-direction: column;
    gap: 0.25rem;
    padding: 0.5rem 0;
  }
  
  .education-row .label {
    min-width: auto;
    font-size: 0.9rem;
  }
  
  .research-group {
    display: block;
    margin-bottom: 0.5rem;
  }
}

/* Dark mode support */
@media (prefers-color-scheme: dark) {
  .education-item {
    background: linear-gradient(135deg, #f8f9fa 0%, #ffffff 100%);
    border-left-color: #28a745;
    box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
  }
  
  .education-item::before {
    background: #28a745;
  }
  
  .education-header h4 {
    color: #2c3e50;
  }
  
  .education-institution {
    color: #28a745;
  }
  
  .education-row {
    border-bottom-color: #e9ecef;
  }
  
  .education-row .label {
    color: #495057;
  }
  
  .education-row .value {
    color: #2c3e50;
  }
  
  .research-group {
    background: #e3f2fd;
    color: #1976d2;
    border-color: #bbdefb;
  }
}

/* Animation for timeline items */
@keyframes slideInFromLeft {
  from {
    opacity: 0;
    transform: translateX(-30px);
  }
  to {
    opacity: 1;
    transform: translateX(0);
  }
}

.education-item {
  animation: slideInFromLeft 0.6s ease-out;
}

.education-item:nth-child(2) {
  animation-delay: 0.2s;
}
</style>
