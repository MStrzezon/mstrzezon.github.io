---
layout: default
title: Projects
permalink: /projects/
---

# 🚀 My Projects

Welcome to my project portfolio! Here you'll find a collection of applications and tools I've developed, ranging from web applications to AI/ML projects.

---

### ✈️ [Flylytics](./flylytics/)
**ADS-B Trajectory Analysis Platform**

Web application for analyzing aircraft trajectories from ADS-B data, featuring interactive visualizations and comprehensive analytics.

- **Status**: 🚧 In Active Development
- **Tech Stack**: Python, Streamlit, Plotly, Traffic
- **Focus**: Aviation Data Analytics, Geospatial Analysis

[Learn More →](./flylytics/) | [GitHub](https://github.com/mstrzezon/flylytics) | [Live Demo](https://flylytics.streamlit.app)

---

### ⚽ [QuickMatch](https://github.com/TripleM-MMM/QuickMatch)
**Football Match Organizer**

Full-stack web application prototype for organizing football matches with real-time booking system, user management, and interactive match details. 

- **Status**: ✅ Completed
- **Tech Stack**: Django, React, REST API, MySQL
- **Focus**: Web Development, Full-Stack Architecture
- **Collaborators**: [Aleksander Mazur](https://github.com/Aleksander2a), [Marcin Retajczyk](https://github.com/RETAJD)

[GitHub](https://github.com/TripleM-MMM/QuickMatch)

---

### 🃏 [Socket Poker Game](https://github.com/mstrzezon/Poker)
**Multiplayer Card Game**

Multi-player poker game with client-server architecture, socket communication and comprehensive game protocol implementation.

- **Status**: ✅ Completed
- **Tech Stack**: Java, Sockets, Maven, OOP
- **Focus**: Network Programming, Game Development

[GitHub](https://github.com/mstrzezon/Poker)

---

### 📊 [JPK Generator](https://github.com/mstrzezon/generator_jpk)
**File Format Converter**

Java tool for converting Excel/CSV files to JPK XML format required for Polish tax reporting compliance and government submissions.

- **Status**: ✅ Completed
- **Tech Stack**: Java, JAXB, Apache POI, XML
- **Focus**: Data Conversion, Government Compliance

[GitHub](https://github.com/mstrzezon/generator_jpk)

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