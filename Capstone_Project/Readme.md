
<p align="center">
  <img src="https://www.clipartmax.com/png/middle/334-3342031_iit-guwahati-logo.png" alt="IIT Guwahati Logo" height="80"/>
  <img src="https://static.businessworld.in/TQ%20Ventures_20241204114750_original_image_38.webp" alt="Pathways Logo" height="80"/>
</p>

# Dynamic Parking Pricing Capstone Project

<p align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExOGI4M3V3Ym45OWRpNHNqZW4zNHozaTdwdjVlc3JuMmsxYmwxNXh4NyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/3ohjVcBvoTRNhAK0HC/giphy.gif" alt="Project Animation" height="120"/>
</p>

<p align="center">
  <b>Indian Institute of Technology Guwahati</b>  
  <b>Pathways Program</b>
</p>

---

## 🚗 Project Overview

This project presents a dynamic parking pricing system leveraging machine learning and data analytics to optimize parking space utilization and maximize revenue. The solution integrates real-time data, predictive modeling, and interactive dashboards for actionable insights and automated pricing adjustments.

---

## 🛠️ Tech Stack

- **Python** (Pandas, NumPy, Scikit-learn, CatBoost, LightGBM, Bokeh)
- **Jupyter Notebook**
- **Visualization:** Bokeh, Matplotlib
- **Data:** Custom datasets, CSV
- **Documentation:** Markdown, Mermaid, PNG, GIF

---

## 🏗️ System Architecture

<p align="center">
  <img src="./High-Level%20System%20Architecture.png" alt="System Architecture" width="600"/>
</p>

```mermaid
flowchart TD
    A[User/Vehicle Entry] --> B[Data Collection Layer]
    B --> C[Data Processing & Feature Engineering]
    C --> D[ML Model Prediction]
    D --> E[Dynamic Pricing Engine]
    E --> F[Dashboard & Alerts]
    F --> G[Admin/Operator]
```

---

## 🔄 Data Flow Diagram

<p align="center">
  <img src="./Detailed%20Data%20Flow%20&%20Model%20Logic.png" alt="Data Flow Diagram" width="600"/>
</p>

```mermaid
flowchart LR
    A[Raw Parking Data] --> B[Preprocessing]
    B --> C[Feature Engineering]
    C --> D[Model Training]
    D --> E[Prediction]
    E --> F[Pricing Decision]
    F --> G[Visualization & Reporting]
```

---

## ⚙️ Workflow with Technologies

<p align="center">
  <img src="./Workflow%20with%20Technologies.png" alt="Workflow Diagram" width="600"/>
</p>

---

## ✨ Features

- Three dynamic pricing models for parking:
  - **Model 1:** Linear price adjustment based on occupancy.
  - **Model 2:** Multi-factor demand-based pricing (occupancy, queue, traffic, special events, vehicle type).
  - **Model 3:** Competitive pricing using geospatial analysis of nearby lots.
- Real-time simulation and streaming with Pathway.
- Interactive Bokeh dashboard for real-time price visualization.
- Advanced historical pattern recognition and temporal demand features.
- Intelligent rerouting system for overloaded lots.
- Comprehensive business intelligence and executive reporting.
- All code, data processing, and visualizations in a single, reproducible notebook.

---

## 📁 Project Structure

```text
Capstone_Project/
│   IIT.ipynb                # Main notebook (code, models, visualizations)
│   Readme.md                # Project documentation
│   High-Level System Architecture.png
│   Detailed Data Flow & Model Logic.png
│   Workflow with Technologies.png
│   ...
```

---

## 🚀 Getting Started

1. **Clone the repository**
2. Open `IIT.ipynb` in Jupyter Notebook
3. Install dependencies from `requirements.txt`
4. Run all cells to reproduce results and visualizations

---

## 📊 Resources & References

- Project dataset: 14 urban parking lots, 73 days, 18,000+ records.
- Libraries: pandas, numpy, matplotlib, seaborn, geopy, pathway, bokeh, scipy.
- [Pathway documentation](https://pathway.com/)
- [Bokeh documentation](https://docs.bokeh.org/en/latest/)
- [Geopy documentation](https://geopy.readthedocs.io/)
- [IIT Guwahati](https://www.iitg.ac.in/)
- [Summer Analytics 2025 - Consulting & Analytics Club × Pathway]

---

## 👤 Author & Contact

**T Mohamed Yaser**  
Email: [1ammar.yaser@gmail.com](mailto:1ammar.yaser@gmail.com)  
LinkedIn: [mohamedyaser08](https://www.linkedin.com/in/mohamedyaser08/)  
Website: [mohdyaser.vercel.app](https://mohdyaser.vercel.app/)

<p align="center">
  <img src="Profile.png" alt="Branding" height="400"/>
</p>

---

<p align="center">
  <i>Capstone Project &copy; 2025 | IIT Guwahati | Pathways</i>
</p>
