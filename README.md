------------------------------------------------------------------------

editor_options: markdown: wrap: 72 ---

# Data Visualization and Reproducible Research

> Lauren Bautista.

## Executive Summary

The following is a portfolio of products created during the *"Data Visualization and Reproducible Research"* course. The motivation behind this repository is to demonstrate proficiency in exploratory data analysis, statistical modeling, and data storytelling using R. Across three mini-projects, this portfolio transforms raw datasets into accessible, narrative-driven visualizations.

**Datasets Explored**

- **Project 01:** Daily U.S. births (2000–2014) to track seasonal and holiday trends.

- **Project 02:** Billboard summer hits (1950s–2010s), Florida spatial lake data, and West Roxbury housing market data.

- **Project 03:** Tampa International Airport (TPA) 2022 meteorological data, Florida Poly news articles, and ultimate frisbee player statistics.

## Project 01

In the `project_01/` folder you can find an exploratory data analysis of daily U.S. births from 2000 to 2014 using the following libraries: tidyverse, plotly, viridis, and here. This project investigates temporal birth trends, specifically analyzing how birth rates fluctuate by day of the week, dip significantly during major winter holidays, and vary across meteorological seasons. The analysis reveals how modern maternity care logistics—such as scheduled inductions and C-sections—create distinct bi-modal distributions and predictable drops in weekend and holiday birth volumes.

**Core Requirements Met:**

- **Interactivity:** The HTML report features a `plotly` bar chart of winter births. Hovering over the holiday "valleys" reveals the exact numerical deviation from the period average, allowing the reader to explore specific dates without cluttering the static chart.

- **Accessibility:** Applied colorblind-safe `viridis` palettes to distinguish weekdays from weekends, and included descriptive `fig.alt` text for screen readers.

- **Redesign:** Transformed a poor-quality, manually colored boxplot missing axis labels into an accessible, multilayered violin and boxplot that properly reveals the data's bimodal distribution.

**Sample data visualization:**

*Effect of Holidays on Daily Births: A bar chart illustrating the significant drop in birth rates around Christmas and New Year's compared to the period average.* <img src="https://raw.githubusercontent.com/lbautista1806/dataviz_final_project/main/figures/holiday_births_plot.png" width="80%" height="80%"/>

## Project 02

In this project, I explored In this project, I explored three distinct datasets to demonstrate a variety of advanced visualization techniques and statistical modeling. First, I used plotly to analyze Billboard summer hits, revealing a decadal trend where track energy increased while valence (happiness) decreased from the 1950s to the 2010s. Next, I utilized sf and tigris to create a spatial visualization of Florida's surface water distribution, highlighting heavy lake density in the central region. Finally, I conducted a multiple linear regression analysis on the West Roxbury housing market to predict home values. I used the broom package to tidy the results and built a coefficient plot to visualize the value impact of specific property features. Find the code and report in the `project_02/` folder.

**Core Requirements Met:**

- **Interactivity:** The HTML report features a `plotly` bubble chart mapping mood vs. energy. The interactivity allows the reader to hover over overlapping points to see specific song titles, artists, and years, effectively solving the issue of overplotting.

- **Accessibility:** Utilized the colorblind-friendly Okabe-Ito palette for the modeling and bubble charts, and avoided relying on color alone by adding clear textual annotations and standard baseline markers.

- **Redesign:** Replaced a highly ineffective pie chart (which obscured small data wedges and used inaccessible colors) with a clean, properly labeled, monochromatic bar graph mapping home bedroom counts.

**Sample data visualization:**

*West Roxbury Housing Value Prediction: A coefficient plot visualizing the estimated value impact of various property features based on a multiple linear regression model, highlighting that adding a bathroom increases a home's value by approximately \$27.6k*<img src="https://raw.githubusercontent.com/lbautista1806/dataviz_final_project/main/figures/housing_coefficient_plot.png" width="80%" height="80%"/>

## Project 03

In this project, I explored In this project, I explored exploratory data analysis techniques using meteorological, text, and sports data. First, I utilized ggplot2 and ggridges to analyze 2022 climate data from Tampa International Airport, creating faceted histograms, density plots, and ridgeline plots to visualize seasonal temperature shifts. I also created an interactive lollipop chart using plotly to track daily precipitation. Next, I performed text analysis on Florida Poly news articles using the tidytext package to identify the most frequent terms after filtering out stop words. Finally, I redesigned an ineffective ultimate frisbee visualization, transforming it into an accessible, properly sorted horizontal bar chart using a colorblind-safe viridis palette.

**Core Requirements Met:**

- **Interactivity:** The HTML report includes a `plotly` lollipop chart for daily precipitation. Interactivity allows readers to hover over individual rainfall spikes to view the exact date and measurement (in inches) without needing dense axis labels.

- **Accessibility:** Relied on `viridis` (specifically the continuous `plasma` gradient for temperature) to ensure colorblind safety, and applied detailed `fig.alt` text to describe complex density structures for visually impaired users.

- **Redesign:** Fixed an ugly, truncated ultimate frisbee bar graph by rotating it horizontally for readable text, applying descending rank ordering, and removing distracting chartjunk (like heavy grid lines and non-accessible colors).

**Sample data visualization:**

*Daily Precipitation at TPA (2022): A lollipop chart visualizing the stark contrast between Florida's heavy summer wet season and its drier fall and spring months.*<img src="https://raw.githubusercontent.com/lbautista1806/dataviz_final_project/main/figures/tpa_precip_lollipop.png" width="80%" height="80%"/>

### Moving Forward

Throughout this course, I have become increasingly confident in my data visualization skills, particularly relating to data storytelling. Moving forward, I plan to bridge these techniques with my expertise in applied mathematics to tackle complex challenges in industrial engineering and operations research. I would like to integrate my data analysis skills with optimization methods such as linear programming and simulation to build data-driven solutions to improve decision-making and operational efficiency.
