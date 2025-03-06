# Bicycle Accidents in Great Britain (1979-2018) - Data Analysis

## Project Overview
This repository contains a data analysis project examining bicycle accidents in Great Britain over a 40-year period (1979-2018). Using accident and cyclist data, the analysis identifies key factors affecting accident frequency and severity through statistical analysis and visualization.

## Data Source
The analysis uses the "Bicycle Accidents in Great Britain (1979-2018)" dataset from Kaggle, which includes:
- `Accidents.csv`: Contains details about each accident including location, time, road conditions, and speed limits
- `Bikers.csv`: Contains information about the cyclists involved including age, gender, and injury severity

## Key Research Questions

1. **What are the leading reasons for bicycle accidents?**
   - How does road speed limit affect accident frequency?
   - What impact do road conditions have on accident rates?
   - How do weather conditions influence accident occurrence?

2. **When do bicycle accidents occur most frequently?**
   - Which days of the week have the highest accident rates?
   - Are there specific times of day with elevated risk?
   - What seasonal patterns exist in accident data?

3. **Who is most affected by bicycle accidents?**
   - Which gender is involved in more accidents?
   - What age groups are most at risk?
   - How do severity patterns differ between demographic groups?

4. **What factors influence injury severity?**
   - How does speed limit correlate with injury severity?
   - Are there gender differences in injury outcomes?
   - What combination of factors predict more severe accidents?

## Key Findings

- Speed limit zones between 21-30 mph have the highest accident count
- Dry road conditions account for the majority of bicycle accidents
- Fine weather (no precipitation) is associated with the highest number of accidents
- Weekdays see more accidents than weekends, with peaks on specific days
- Males are involved in significantly more bicycle accidents than females
- Different age groups show varying accident patterns, with 11-15 and 26-35 most represented
- Injury severity varies by gender, with differences in the proportion of slight, serious, and fatal injuries
- There are clear patterns in accident occurrence by time of day

## Visualizations
The analysis includes numerous visualizations:
- Line charts showing accident distribution by speed category
- Pie charts displaying road condition and gender distributions
- Bar charts illustrating weather conditions and day of week patterns
- Heatmaps examining correlations between multiple factors

## Setup and Dependencies
This project requires Python with the following libraries:
```
pandas
numpy
matplotlib
seaborn
scipy
```

Data is loaded from Kaggle using their API (requires Kaggle API key).

## How to Run
1. Install required dependencies:
   ```
   pip install pandas numpy matplotlib seaborn scipy kaggle
   ```

2. Set up your Kaggle API credentials (see code comments for details)

3. Run the notebook to reproduce the analysis

## Future Work
Potential extensions to this analysis:
- Geographical analysis of accident hotspots
- Machine learning model to predict accident severity
- Time series analysis of changing accident patterns over decades
- Correlation with cycling infrastructure developments
