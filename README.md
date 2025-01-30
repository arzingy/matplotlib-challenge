# Matplotlib Assignment
Here are the screenshots of the results of different stages of my work on this challenge.

## DataFrame with merged data (first 5 rows)
<figure>
  <img
  src="/Pymaceuticals/screenshots/merged_data.png">
</figure>

## Data of mouse with duplicate timepoints (Mouse ID g989)
<figure>
  <img
  src="/Pymaceuticals/screenshots/duplicate_mouse_data.png">
</figure>

## Clean DataFrame (first 5 rows) and the number of mice in it
<figure>
  <img
  src="/Pymaceuticals/screenshots/clean_data.png">
</figure>

## Statistics of tumor volumes grouped by different drug regimens
<figure>
  <img
  src="/Pymaceuticals/screenshots/drug_volume_stats.png">
</figure>

## Bar chart showing the total number of timepoints for all mice tested for each drug regimen
<figure>
  <img
  src="/Pymaceuticals/screenshots/bar_chart.png">
</figure>

## Pie chart showing the distribution of unique female versus male mice
<figure>
  <img
  src="/Pymaceuticals/screenshots/pie_chart.png">
</figure>

## DataFrame with the last timepoint for each mouse ID
As I explained in the comments for that section in the .ipynb file, I got this DataFrame by sorting rows (Timepoint desc) in clean data and then removing
duplicates with same Mouse ID. This way, the tumor volumes are not affected. But, since it is asked in requirements for this assignment to create this DataFrame
using groupby, I also created it in a ceparate cell. In that cell I also got Series with max timepoint for each mouse ID (more info in .ipynb file).
<figure>
  <img
  src="/Pymaceuticals/screenshots/latest_timepoints.png">
</figure>

## The outliers for each treatment group
<figure>
  <img
  src="/Pymaceuticals/screenshots/potential_outliers.png">
</figure>

## Box plot showing the distribution of the final tumor volume for all the mice in each treatment group
<figure>
  <img
  src="/Pymaceuticals/screenshots/boxplot.png">
</figure>

## Line plot showing the tumor volume vs. time point for one mouse treated with Capomulin
<figure>
  <img
  src="/Pymaceuticals/screenshots/line_chart_capomulin.png">
</figure>

## Scatter plot showing average tumor volume vs. mouse weight for the Capomulin regimen
<figure>
  <img
  src="/Pymaceuticals/screenshots/scatter_chart_capomulin.png">
</figure>

## The correlation coefficient and linear regression model for mouse weight and average tumor volume for the Capomulin regimen
<figure>
  <img
  src="/Pymaceuticals/screenshots/correlation_linear_regression.png">
</figure>
