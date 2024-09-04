# Traffic Accident Data Analysis

## Overview
This project focuses on analyzing traffic accident data to identify patterns related to road conditions, weather, and time of day. The analysis primarily investigates the impact of various road conditions on the number of accidents, injuries, and fatalities. The findings are visualized using Tableau to provide clear insights into traffic safety.

## Project Structure
The repository contains the following files:

- **Traffic_Accident_Data_Analysis.ipynb**: The Jupyter notebook containing the data analysis code, including preprocessing, handling missing values, and generating visualizations.
- **Traffic Accident Data Analysis.twbx**: The Tableau workbook containing the visualizations and dashboards created as part of the analysis.
- **Data/**: Folder containing the dataset files used for analysis.
- **README.md**: This file, providing an overview of the project, tools used, and instructions for replication.
  
## Dataset
The dataset used for this analysis contains information on traffic accidents categorized by different road conditions, such as slippery roads, surfaced roads, and the presence of speed breakers. The data spans multiple years and includes variables such as the number of accidents, injuries, and fatalities.

### Key Columns:
- **Road_Condition**: Indicates the type of road surface (e.g., Slippery, Surfaced, Speed Breaker).
- **Year**: The year the data was recorded.
- **Accidents**: The total number of accidents under each road condition.
- **Injured**: The total number of people injured.
- **Killed**: The total number of fatalities.

## Installation
To replicate this analysis, you'll need to have the following tools installed:

### Python Libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `tableau-api-lib`

Install the necessary Python packages using:
```bash
pip install pandas numpy matplotlib seaborn tableau-api-lib
```

### Tableau:
Ensure you have Tableau Desktop installed to open the `.twbx` file.

## Analysis and Visualization
The analysis was performed using Python, focusing on preprocessing and understanding the dataset. Tableau was used to create interactive visualizations, including:

**Using Python**

- **Stacked Bar Charts**: To compare the number of accidents, injuries, and fatalities stacked on top of each other for each state/UT.
- **Heatmaps**: To identify the states/UTs with higher numbers of accidents, injuries, and fatalities due to speed breakers.
- **Pie Chart**: To show the proportion of accidents, injuries, and fatalities caused by speed breakers in 2016 for each state.

**Using Tableau**

- **Dust Storm vs Cloud**: Compared accident rates during dust storms and cloudy weather in 2016, revealing significant patterns across different states.
- **Muddy Road Impacts**: Analyzed the effects of muddy road conditions in 2014, focusing on the number of accidents, injuries, and fatalities.
- **Snowfall vs Mist/Fog**: Visualized the impact of snowfall compared to mist/fog, highlighting regions with the highest accident rates.
- **Speed Breakers**: Explored the paradox of speed breakers leading to significant fatalities, with visual data from various states.
- **Good Surface Roads**: Investigated accidents on good surface roads, identifying states with unexpected high fatality rates.

## Key Findings
- **Good Surface Roads**: Inspite of proper maintenance of roads,good surface roads Showed a higher number of accidents(killed), particularly in 2014.
- **Speed Breakers**: Despite reducing speed, areas with speed breakers still witnessed a significant number of accidents.

## Usage
Feel free to explore the Jupyter notebook and Tableau workbook to understand the analysis. You can modify the code and visualizations as needed to suit your own data analysis projects.

## Contributing
Contributions are welcome! If you have any improvements or suggestions, please submit a pull request.

## License
This project is licensed under the MIT License.
