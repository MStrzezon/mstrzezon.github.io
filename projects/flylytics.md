---
layout: default
title: Flylytics - ADS-B Trajectory Analysis
permalink: /projects/flylytics/
---

<div class="project-hero">
  <h1>✈️ Flylytics</h1>
  <p class="project-subtitle">Advanced ADS-B Trajectory Analysis Platform</p>
  <div class="project-status-badge">🚧 In Active Development</div>
</div>

---

## 🎯 Overview

Flylytics is a web application designed for analyzing aircraft trajectories from ADS-B (Automatic Dependent Surveillance-Broadcast) data. Built with Streamlit, it provides aviation enthusiasts, researchers, and professionals with powerful tools for flight data visualization and analysis.

### Data Management

Users can upload their own ADS-B data files in CSV, JSON, or Parquet formats that are traffic object from the library [traffic](https://github.com/xoolive/traffic)
![Flylytics Screenshot](/assets/images/upload_data.png)

### Analytics Dashboard

Users can explore various analytics features, including:
- **Trajectories Filtering**: Filter flights by date, time, weekday, airline, aircraft type, and more.
![Flylytics Screenshot](/assets/images/analytics_dashboard_filters.png)
- **Statistical Visualizations**: View histograms of flight dates distribution, aircraft types, airlines, and other key metrics.
![Flylytics Screenshot](/assets/images/analytics_dashboard_stats.png)

### Trajectory Analysis

Users can analyze trajectories of loaded traffic:
- **2D Visualization**: Interactive 2D maps displaying flight paths. Trajectories can be colored by hour of the day, altitude, speed, callsign, weekday, or aircraft type.
![Flylytics Screenshot](/assets/images/trajectory_analysis_2d.png)
- **Flight parameters plots**: Plots of altitude, speed, and vertical rate over time.
![Flylytics Screenshot](/assets/images/trajectory_analysis_params.png)
- **Comparison of multiple trajectories parameters**: Compare altitude, speed, and vertical rate of multiple flights on the same plot.
![Flylytics Screenshot](/assets/images/trajectory_analysis_compare.png)
- **Individual flight details**: View detailed information about individual flights.
![Flylytics Screenshot](/assets/images/trajectory_analysis_flight_details.png)

## Status

Flylytics is currently in active development and code is not published yet. New features and improvements are being added regularly. Feedback and contributions from the community are welcome!


<style>
.project-hero {
  text-align: center;
  padding: 3rem 0;
  background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
  color: white;
  border-radius: 12px;
  margin-bottom: 2rem;
}

.project-subtitle {
  font-size: 1.3rem;
  opacity: 0.9;
  margin: 1rem 0;
}

.project-status-badge {
  display: inline-block;
  background: rgba(255, 255, 255, 0.2);
  padding: 8px 16px;
  border-radius: 20px;
  font-size: 0.9rem;
  margin-top: 1rem;
}
</style>