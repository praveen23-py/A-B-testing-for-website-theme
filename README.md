# A/B Testing for Website Theme
This project demonstrates the application of A/B testing to optimize website user engagement by comparing two different website themes. The analysis was conducted using Python, focusing on metrics such as user session duration, bounce rates, and conversion rates.

##  Project Overview
Many websites face the challenge of identifying which design elements resonate best with users. A/B testing offers a data-driven approach to solving this by comparing different versions of a design and analyzing user behavior.

##  Key Features
* Hypothesis Testing: Formulated and tested the impact of website themes (light vs dark) on user engagement.
* Traffic Split: Randomly assigned users to either the control group (Light Theme) or the experimental group (Dark Theme).
* Data Collection & Analysis: Collected and analyzed user behavior data such as session times and bounce rates using pandas and scipy.
* Statistical Testing: Conducted a z-test for proportions to determine the statistical significance of the results.
* Visualization: Visualized the data using plotly to clearly show differences in user engagement between the two themes.
  Data Collection
## Data was gathered from real-time website traffic split between the two themes over a two-week period. Metrics collected included:

* Session time
* Bounce rate
* Conversion rate
  ## Analysis
* The analysis was conducted using Python, employing the following libraries:
* pandas for data manipulation
* plotly for interactive visualizations
* scipy and statsmodels for statistical analysis
   ## Key Steps:
* Formulate Hypothesis: "The Dark Theme will lead to higher user engagement."
* Data Cleaning: Ensured no missing or inconsistent data points.
* Statistical Test: A z-test for proportions was conducted to compare the performance of the two themes.
* Visualization: Graphical insights were created to visualize the comparison between the control and variation.
# Results
The statistical analysis revealed that the Dark Theme significantly outperformed the Light Theme in user session duration and reduced the bounce rate by 12%. The results were visualized for better communication with stakeholders.
