---
layout: default
title: Projects
permalink: /projects/
---

# 🚀 My Projects

Welcome to my project portfolio! Here you'll find a collection of applications and tools I've developed, ranging from aviation data analytics to educational physics tools.

---

## Featured Projects

<div class="projects-showcase">

### ✈️ [Flylytics](./flylytics/)
**ADS-B Trajectory Analysis Platform**

Advanced web application for analyzing aircraft trajectories from ADS-B data, featuring interactive visualizations and comprehensive analytics.

- **Status**: 🚧 In Active Development
- **Tech Stack**: Python, Streamlit, Plotly, GeoPandas
- **Focus**: Aviation Data Analytics, Geospatial Analysis

[Learn More →](./flylytics/) | [GitHub](https://github.com/mstrzezon/flylytics) | [Live Demo](https://flylytics.streamlit.app)

---

### 🔬 [Physicist's Toolbox](./physicist-toolbox/)
**Comprehensive Physics Calculator**

Educational application covering six major physics domains with intuitive interface for students and educators.

- **Status**: ✅ Completed
- **Tech Stack**: Python, NumPy, SciPy
- **Focus**: Educational Tools, Physics Calculations

[Learn More →](./physicist-toolbox/) | [GitHub](https://github.com/mstrzezon/physicist-toolbox)

</div>

---

## Project Categories

### 🛩️ **Data Analytics & Visualization**
Projects focused on extracting insights from complex datasets and creating meaningful visualizations.

- **Flylytics**: Aviation trajectory analysis and flight data visualization
- *More analytics projects coming soon...*

### 🎓 **Educational Tools**
Applications designed to enhance learning and teaching experiences.

- **Physicist's Toolbox**: Comprehensive physics calculation suite
- *Additional educational tools in development...*

### 🔬 **Research & Experimentation**
Experimental projects and research initiatives exploring new technologies and methodologies.

- *Research projects documentation coming soon...*

---

## Development Philosophy

My approach to project development focuses on:

### 🎯 **User-Centered Design**
- Intuitive interfaces that prioritize user experience
- Clear documentation and helpful error messages
- Accessibility considerations for diverse users

### 🔧 **Technical Excellence**
- Clean, maintainable code architecture
- Comprehensive testing and validation
- Performance optimization and scalability

### 📚 **Educational Value**
- Projects that solve real-world problems
- Open-source contributions to benefit the community
- Knowledge sharing through documentation

### 🌱 **Continuous Improvement**
- Regular updates and feature enhancements
- Community feedback integration
- Technology stack modernization

---

## Technologies I Work With

<div class="tech-categories">

### **Programming Languages**
- **Python** - Primary language for data analysis and web applications
- **JavaScript** - Web development and interactive features
- **SQL** - Database queries and data manipulation

### **Data Science & Analytics**
- **Pandas, NumPy** - Data manipulation and numerical computing
- **Plotly, Matplotlib** - Data visualization and charting
- **GeoPandas** - Geospatial data analysis
- **SciPy** - Scientific computing and statistics

### **Web Development**
- **Streamlit** - Rapid web application development
- **HTML/CSS** - Frontend development and styling
- **Jekyll** - Static site generation (this website!)

### **Tools & Platforms**
- **Git** - Version control and collaboration
- **GitHub** - Code hosting and project management
- **Docker** - Application containerization
- **VS Code** - Primary development environment

</div>

---

## Get Involved

I'm always excited to collaborate on interesting projects or discuss new ideas!

### 🤝 **Collaboration Opportunities**
- **Open Source Contributions**: Most projects welcome community contributions
- **Research Partnerships**: Academic or professional research collaborations
- **Mentoring**: Helping other students and junior developers
- **Consulting**: Technical advice and project guidance

### 💡 **Project Ideas**
Have an interesting project idea? I'm particularly interested in:
- **Aviation & Transportation Analytics**
- **Educational Technology Applications**
- **Data Visualization & Interactive Tools**
- **Scientific Computing & Simulation**

### 📬 **Contact Information**
- **Email**: [michal.m.strzezon@gmail.com](mailto:michal.m.strzezon@gmail.com)
- **GitHub**: [@mstrzezon](https://github.com/mstrzezon)
- **LinkedIn**: [mstrzezon](https://linkedin.com/in/mstrzezon)

---

<div class="projects-footer">
  <p>
    <strong>🔄 Regular Updates</strong><br>
    This portfolio is regularly updated with new projects and enhancements. 
    Check back frequently to see the latest developments!
  </p>
  
  <div class="footer-actions">
    <a href="/" class="btn btn-outline">← Back to Home</a>
    <a href="mailto:michal.m.strzezon@gmail.com" class="btn btn-primary">Get in Touch</a>
  </div>
</div>

<style>
.projects-showcase {
  margin: 2rem 0;
}

.projects-showcase h3 {
  color: #2c3e50;
  margin-bottom: 0.5rem;
}

.projects-showcase h3 a {
  text-decoration: none;
  color: inherit;
}

.projects-showcase h3 a:hover {
  color: #667eea;
}

.tech-categories {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.tech-categories h3 {
  color: #495057;
  font-size: 1.1rem;
  margin-bottom: 1rem;
  padding-bottom: 0.5rem;
  border-bottom: 2px solid #667eea;
}

.tech-categories ul {
  list-style: none;
  padding: 0;
}

.tech-categories li {
  padding: 0.5rem 0;
  border-bottom: 1px solid #e9ecef;
}

.tech-categories li:last-child {
  border-bottom: none;
}

.tech-categories strong {
  color: #2c3e50;
}

.projects-footer {
  background: #f8f9fa;
  padding: 2rem;
  border-radius: 8px;
  text-align: center;
  margin: 3rem 0;
  border-left: 4px solid #667eea;
}

.footer-actions {
  margin-top: 1.5rem;
  display: flex;
  gap: 1rem;
  justify-content: center;
  flex-wrap: wrap;
}

.btn {
  display: inline-block;
  padding: 10px 20px;
  border-radius: 6px;
  text-decoration: none;
  font-weight: 500;
  transition: all 0.3s ease;
}

.btn-primary {
  background: #667eea;
  color: white;
}

.btn-primary:hover {
  background: #5a6fd8;
  transform: translateY(-2px);
  text-decoration: none;
  color: white;
}

.btn-outline {
  background: transparent;
  color: #667eea;
  border: 2px solid #667eea;
}

.btn-outline:hover {
  background: #667eea;
  color: white;
  transform: translateY(-2px);
  text-decoration: none;
}

@media (max-width: 768px) {
  .footer-actions {
    flex-direction: column;
    align-items: center;
  }
  
  .tech-categories {
    grid-template-columns: 1fr;
  }
}
</style>