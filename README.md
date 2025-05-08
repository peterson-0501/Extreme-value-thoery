# Extreme-value-thoery
This project (Msc Project) presents a comprehensive analysis of extreme rainfall events in India using
the Generalized Extreme Value (GEV) framework. The study begins with a rigorous
preprocessing stage, where Mann-Kendall and Augmented Dickey-Fuller (ADF) tests are
applied to assess the presence of trends and stationarity in annual maximum rainfall se-
ries. Based on these results, appropriate covariates—primarily time—are included in the
location or scale parameters of the GEV model to address underlying non-stationarity
or trends while keeping the model parsimonious.Model selection is guided by Likelihood
Ratio Tests (LRT), AIC, and BIC values to balance complexity and interpretability. For
each state, return levels corresponding to 5, 10, 50, and 100 year periods are estimated
using Maximum Likelihood Estimation, with confidence intervals derived under the as-
sumption of asymptotic normality of the parameter estimates. States are then ranked
based on their estimated return levels for multiple future years (e.g., 2025–2027), pro-
viding a temporal and spatial perspective on extreme rainfall risk.To enhance regional
granularity, the study further explores spatial patterns either by zooming into districts
within the most vulnerable state (e.g., Meghalaya). These spatial extensions help identify
high-risk zones and improve localized risk assessment.

Dataset is not uploaded because of large size ( please vist https://www.imdpune.gov.in/cmpg/Griddata/Rainfall_25_NetCDF.html) for the data.

This GitHub repository contains the Python and R scripts used for the analysis, the estimated return levels in CSV format, and other miscellaneous files related to the study.
