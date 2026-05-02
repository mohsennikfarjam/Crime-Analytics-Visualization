# Public Safety Analysis: San Francisco Crime Patterns (Summer 2014)

**Author:** Mohsen

## Primary Finding
San Francisco experienced a distinct surge in property crimes during the Summer of 2014, with Larceny and Theft occurring at nearly triple the rate of other major crime categories. These incidents show a consistent daily peak during the evening transition (5 PM - 7 PM), indicating that the end of the workday and early evening social hours are the highest-risk periods for property loss.

## Visualizations and Descriptions

### 1. Distribution of Incidents by Police District
This visualization highlights the spatial distribution of reported crimes. The Southern District accounts for the highest volume of incidents, followed by Mission and Central. This concentration suggests that the city's urban core and commercial centers are the primary focus of criminal activity.

### 2. Temporal Patterns of Major Offenses
By plotting incident frequency by hour, we see a clear cyclical pattern. Crime reaches its lowest point at 5 AM and climbs steadily throughout the day, peaking during the evening hours. Larceny and Theft show the most dramatic hourly variation, emphasizing the time-sensitive nature of these offenses.

### 3. Heatmap of Crime Intensity by Day and Hour
The heatmap analysis identifies specific high-risk windows. While Monday through Thursday show high activity in the evenings, Friday and Saturday demonstrate extended periods of high crime density that last later into the night.

## Conclusion
The analysis of Summer 2014 incident reports reveals that San Francisco's primary crime challenge is property-related and highly predictable in its timing. The peak activity during evening hours and weekend nights suggests that crime patterns are closely tied to the city's social and economic rhythms. Strategic resource allocation during these identified "hot" times could be effective in reducing incident rates.

## Reproducibility
Reproducibility is guaranteed through the provided Jupyter Notebook ([Crime_Analysis_MN.ipynb](./Crime_Analysis_MN.ipynb)). The notebook includes the complete data pipeline from raw CSV ingestion to final visualization, ensuring transparency and ease of verification.

## How to Run
1. Ensure you have Python installed with `pandas`, `matplotlib`, and `seaborn`.
2. Place the `sanfrancisco_incidents_summer_2014.csv` dataset in the same directory as the notebook.
3. Open `Crime_Analysis_MN.ipynb` in Jupyter Notebook or JupyterLab and run all cells.
