# A Multidimensional Bayesian Approach to Pothole Occurrence in Toronto (2025–2026)
This repository analyzes road degradation in Toronto by identifying the "Weather Regimes" that trigger structural failure. Instead of just counting complaints, this project utilizes Bayesian Gaussian Mixture Regression (BGMR) to provide a Probabilistic Risk Assessment for January 2026.

This project develops a predictive framework for urban road degradation, moving beyond reactive, complaint-based maintenance toward a data-driven Proactive Risk Assessment. By integrating 311 service request data from the City of Toronto with high-resolution atmospheric variables, the study identifies the "Weather Regimes" that catalyze pavement failure.

## Methodology
The core of the analysis utilizes Bayesian Gaussian Mixture Regression (BGMR) to map the joint distribution of six environmental pillars: Relative Humidity ($RHUM$), Cloud Cover ($CLDC$), Atmospheric Pressure ($PRES$), Precipitation ($PRCP$), Snow Depth ($SNWD$), and seasonality. Unlike traditional deterministic models, the BGMR approach accounts for atmospheric uncertainty, allowing for the calculation of Exceedance Probabilities and the identification of distinct "Infrastructure Stress Clusters.

### Key Innovations
### Normalization: Shifted the metric from raw report volume to Intersection-Day Occurrences, eliminating reporting bias and focusing on unique structural failure events.

### Spatial Accuracy: Developed a custom geocoding pipeline involving automated Python scripts and manual Google Maps verification to ensure precise coordinate mapping for thousands of Toronto intersections.

### Hazard Scoring: Created a 0–5 Risk Score index. For January 2026, the model identified a median risk of 2.37, signaling a 118% increase in failure probability under high-humidity and low-pressure conditions.

## Results and Impact
The findings demonstrate that 20% of analyzed intersections reached a "Critical" risk level in early 2026, primarily driven by the synergy between moisture saturation and atmospheric pressure drops. The results provide a "Decision Support System" for municipal engineers, enabling the allocation of repair crews to high-risk zones 7–10 days before failures occur, ultimately reducing vehicle damage and optimizing city infrastructure budgets.
