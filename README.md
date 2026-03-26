# AgileProject: Hybrid AI Framework for Adaptive Urban Street Lighting

**Agile Methodologies Course**:
AGH University of Science and Technology, Krakow, Poland

**Authors**:
Michał Mazurek
Marcin Basisty
Łukasz Święch
Byeongjun Min

---

## Project Overview
Urban street lighting is a critical pillar of public safety and infrastructure. However, static systems often result in excessive energy consumption and high operational costs. This repository presents a Hybrid Artificial Intelligence framework designed to transform conventional lighting into a context-aware, energy-efficient, and safety-critical system.

The project integrates data-driven predictive modeling with interpretable fuzzy reasoning and multi-objective evolutionary optimization. By simulating a professional workspace environment using Jira-Scrum and GitHub, this repository demonstrates a robust pipeline for smart city infrastructure development.

---

## Repository Structure
```
├── Notebook/
│   └── SmartStreetLighting.ipynb   # Core implementation: regression, fuzzy logic, and optimization.
├── ResearchPaper/
│   ├── assets/                     # Figures, plots, and experimental data visualizations.
│   ├── Main_Report.tex             # Comprehensive technical report (Full Version).
│   ├── Short_Report.tex            # Executive summary/workshop submission (Shortened).
|   └── SmartStreetLighting.pdf     # Compiled report of the shortened version
├── AI-StudentProjects-A.pdf        # Supplemental technical guidelines.
├── AI-StudentProjects-B.pdf        # Supplemental technical guidelines.
├── GECCO-StudentWorkshop2025.pdf   # Award-winning workshop submission (GECCO 2025) used as a guidline.
├── LICENSE                         # MIT License documentation.
└── README.md                       # Project documentation.
```
---

## Technical Methodology

The framework employs a three-layer architecture to ensure both performance and transparency:

1. Predictive Analysis: A data-driven regression model forecasts short-term lighting demand by processing heterogeneous sensor inputs, including ambient light levels, occupancy rates, and traffic density.
2. Interpretable Reasoning: A fuzzy-rule-based expert layer embeds domain-specific safety logic. This ensures reliable illumination under uncertain or extreme environmental conditions where purely data-driven models might fail.
3. Multi-Objective Optimization: Fuzzy membership functions and control thresholds are tuned using a multi-objective evolutionary algorithm. This produces a Pareto-optimal set of solutions that balance energy conservation against predicted safety risks.

---

## Key Performance Indicators (KPIs)

* Energy Efficiency: Achieves substantial reduction in municipal energy consumption compared to static or reactive systems.
* Operational Safety: Maintains high safety standards through rule-based logic that prevents under-illumination in high-traffic or high-risk periods.
* Explainability (XAI): Unlike "black-box" models, the fuzzy reasoning layer provides human-readable decision paths, facilitating municipal trust and regulatory compliance.

---

## Setup and Usage

### Prerequisites
* Python 3.x
* Jupyter Notebook / JupyterLab
* LaTeX Environment (for compiling research papers)

### Installation
1. Clone the repository:
   git clone https://github.com/owoMarciN/AgileProject.git
2. Navigate to the `Notebook/` directory to explore the implementation.
3. Open `SmartStreetLighting.ipynb` to view the data preprocessing, model training, and optimization results.

---

## License
Distributed under the MIT License. See `LICENSE` for more information.

---
© 2026 AgileProject Team - Smart City Infrastructure Division.
