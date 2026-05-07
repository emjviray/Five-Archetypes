# Five-Archetypes
⚾ Five Pitching Archetypes: MLB Stadium Fit Analysis
📊 Overview

This project analyzes how MLB ballpark characteristics impact pitcher performance by combining machine learning, data visualization, and baseball analytics.

The goal is to determine which pitcher archetypes perform best in specific stadium environments by incorporating weather, elevation, and field dimensions into a data-driven framework.

🧠 Key Idea

Not all pitchers perform equally across ballparks.

This project answers:

How can we match pitcher styles to stadium environments to optimize performance?

🔥 Pitcher Archetypes

Pitchers are grouped into five archetypes:

🔴 Power Pitcher – High velocity, high strikeout
🟢 Groundball Specialist – Induces weak contact
🔵 Finesse Pitcher – Command + pitch mix
🟣 Balanced Pitcher – Hybrid skill set
🟠 Veteran Pitcher – Experience-driven approach
🏟️ Stadium Features Used

Each MLB stadium is represented using:

Elevation (ft)
Temperature (°F)
Humidity (%)
Wind speed & direction
Field dimensions (LF, CF, RF)
Wall heights
⚙️ Methods & Tools
🧮 Data Science / ML
Python
Pandas – Data cleaning & manipulation
NumPy – Numerical computation
Scikit-learn
PCA (dimensionality reduction)
KMeans (clustering)
Pairwise Distance Metrics – Stadium ↔ archetype fit
📈 Visualization
Matplotlib
Seaborn
Heatmaps
Scatter plots
Bar charts
💻 Environment
Jupyter Notebook
📊 Key Analyses
1. Stadium Archetype Clustering
Reduced stadium features using PCA
Clustered stadiums into:
Hitter-Friendly
Neutral
Pitcher-Friendly
2. Pitcher ↔ Stadium Fit Model
Created archetype profiles
Computed distance-based fit scores
Lower distance = better fit
3. Home Run Index Analysis (2020–2024)
Compared HR park factors across all 30 MLB stadiums
Identified:
Extreme hitter parks (e.g., Great American Ballpark, Dodger Stadium)
Extreme pitcher parks (e.g., Oracle Park, Oakland Coliseum)
4. Visualization Outputs
🔥 Heatmaps of archetype-stadium fit
📍 PCA scatter plots of stadium clustering
📊 HR index trends (2020–2024)
📈 Sorted bar charts and distributions
📌 Key Findings
Ballpark context significantly impacts pitcher performance
Oracle Park strongly suppresses HR → favors finesse/groundball pitchers
Dodger Stadium and Great American Ballpark amplify HR → favors power hitters, challenges pitchers
Wrigley Field shows extreme variability due to wind conditions
Chase Field is neutralized by the humidor despite desert conditions
🚀 Applications
MLB roster construction
Pitcher deployment strategy
Free agent fit analysis
Game planning & matchup optimization
📂 Repository Structure
├── ALPA.csv                  # Pitcher archetype data
├── MLBSC.csv / MLBSD.csv     # Stadium characteristics
├── MLBSHRA.csv               # Home run index data
├── Archetype to MLB Fit.csv  # Fit score outputs
├── PA.csv / PACO1.csv        # Processed datasets
├── The Five Pitching Archetypes... (notebook/report)
├── README.md
📝 Author

Emmanuel Viray

Data Analyst for UCSD Tritons Baseball NCAA Division I

Baseball Research Analyst — TritonBall Analytics

UC San Diego | Machine Learning & Data Science

🔗 Future Work
Build a predictive model (regression/NN) for ERA/HR outcomes
Incorporate pitch-level Statcast data
Deploy as an interactive dashboard (Streamlit)
⭐ Final Note

This project bridges machine learning and sports analytics, showing how environmental context can be quantified to improve decision-making in baseball.
