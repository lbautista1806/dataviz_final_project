------------------------------------------------------------------------

editor_options: markdown: wrap: 72 ---

# Data Visualization and Reproducible Research

> Lauren Bautista.

The following is a sample of products created during the *"Data Visualization and Reproducible Research"* course.

## Project 01

In the `project_01/` folder you can find an exploratory data analysis of daily U.S. births from 2000 to 2014 using the following libraries: tidyverse, plotly, viridis, and here. This project investigates temporal birth trends, specifically analyzing how birth rates fluctuate by day of the week, dip significantly during major winter holidays, and vary across meteorological seasons. The analysis reveals how modern maternity care logistics—such as scheduled inductions and C-sections—create distinct bi-modal distributions and predictable drops in weekend and holiday birth volumes.

**Sample data visualization:**

*Effect of Holidays on Daily Births: A bar chart illustrating the significant drop in birth rates around Christmas and New Year's compared to the period average.* <img src="https://raw.githubusercontent.com/lbautista1806/dataviz_final_project/main/figures/holiday_births_plot.png" width="80%" height="80%"/>

## Project 02

In this project, I explored In this project, I explored three distinct datasets to demonstrate a variety of advanced visualization techniques and statistical modeling. First, I used plotly to analyze Billboard summer hits, revealing a decadal trend where track energy increased while valence (happiness) decreased from the 1950s to the 2010s. Next, I utilized sf and tigris to create a spatial visualization of Florida's surface water distribution, highlighting heavy lake density in the central region. Finally, I conducted a multiple linear regression analysis on the West Roxbury housing market to predict home values. I used the broom package to tidy the results and built a coefficient plot to visualize the value impact of specific property features. Find the code and report in the `project_02/` folder.

**Sample data visualization:**

*West Roxbury Housing Value Prediction: A coefficient plot visualizing the estimated value impact of various property features based on a multiple linear regression model, highlighting that adding a bathroom increases a home's value by approximately \$27.6k*<img src="https://raw.githubusercontent.com/lbautista1806/dataviz_final_project/main/figures/housing_coefficient_plot.png" width="80%" height="80%"/>

## Project 03

In this project, I explored In this project, I explored exploratory data analysis techniques using meteorological, text, and sports data. First, I utilized ggplot2 and ggridges to analyze 2022 climate data from Tampa International Airport, creating faceted histograms, density plots, and ridgeline plots to visualize seasonal temperature shifts. I also created an interactive lollipop chart using plotly to track daily precipitation. Next, I performed text analysis on Florida Poly news articles using the tidytext package to identify the most frequent terms after filtering out stop words. Finally, I redesigned an ineffective ultimate frisbee visualization, transforming it into an accessible, properly sorted horizontal bar chart using a colorblind-safe viridis palette.

**Sample data visualization:**

*Daily Precipitation at TPA (2022): A lollipop chart visualizing the stark contrast between Florida's heavy summer wet season and its drier fall and spring months.*<img src="https://raw.githubusercontent.com/lbautista1806/dataviz_final_project/main/figures/tpa_precip_lollipop.png" width="80%" height="80%"/>

### Moving Forward

Throughout this course, I have become increasingly confident in my data visualization skills, particularly relating to data storytelling. Moving forward, I plan to bridge these techniques with my expertise in applied mathematics to tackle complex challenges in industrial engineering and operations research. I would like to integrate my data analysis skills with optimization methods such as linear programming and simulation to build data-driven solutions to improve decision-making and operational efficiency.
