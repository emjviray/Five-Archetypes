Five-Archetypes
Five Pitching Archetypes: MLB Stadium Fit Analysis
Overview

This project analyzes how MLB ballpark characteristics impact pitcher performance by combining machine learning, data visualization, and baseball analytics.

The goal is to determine which pitcher archetypes perform best in specific stadium environments by incorporating weather, elevation, and field dimensions into a data-driven framework.

Key Idea

Not all pitchers perform equally across ballparks.

This project answers:
How can we match pitcher styles to stadium environments to optimize performance?

Pitcher Archetypes

Pitchers are grouped into five archetypes:

Power Pitcher – High velocity, high strikeout
Groundball Specialist – Induces weak contact
Finesse Pitcher – Command and pitch mix
Balanced Pitcher – Hybrid skill set
Veteran Pitcher – Experience-driven approach
Stadium Features Used

Each MLB stadium is represented using:

Elevation (ft)
Temperature (°F)
Humidity (%)
Wind speed and direction
Field dimensions (LF, CF, RF)
Wall heights
Methods and Tools
Data Science / Machine Learning
Python
Pandas – Data cleaning and manipulation
NumPy – Numerical computation
Scikit-learn
PCA (dimensionality reduction)
KMeans (clustering)
Pairwise distance metrics for stadium-archetype fit
Visualization
Matplotlib
Seaborn
Heatmaps
Scatter plots
Bar charts
Environment
Jupyter Notebook
Key Analyses
Stadium Archetype Clustering
Reduced stadium features using PCA and clustered stadiums into hitter-friendly, neutral, and pitcher-friendly environments.
Pitcher to Stadium Fit Model
Created archetype profiles and computed distance-based fit scores, where lower distance indicates a better fit.
Home Run Index Analysis (2020–2024)
Compared HR park factors across all MLB stadiums to identify environments that amplify or suppress home runs.
Visualization Outputs
Generated heatmaps, scatter plots, and comparative charts to visualize relationships between pitcher archetypes and stadium environments.
Key Findings
Ballpark context significantly impacts pitcher performance
Certain stadiums consistently favor specific pitching styles
Environmental factors such as wind, temperature, and elevation influence home run outcomes
Stadium structure and dimensions play a major role in shaping offensive production
Applications
MLB roster construction
Pitcher deployment strategy
Free agent evaluation and fit analysis
Game planning and matchup optimization
Repository Structure
├── ALPA.csv
├── Archetype to MLB Fit.csv
├── MLBSC.csv
├── MLBSD.csv
├── MLBSHRA.csv
├── PA5.csv
├── PACO1.csv
├── README.md
├── The Five Pitching Archetypes - A Study on Their Performance...
Author

Emmanuel Viray

Data Analyst - UCSD Tritons Baseball NCAA Division I

Baseball Research Analyst — Triton Ball Sports Analytics

University of California, San Diego
