### Page View Time Series Visualizer

For this project you will visualize time series data using a line chart, bar chart, and box plots. You will use Pandas, Matplotlib, and Seaborn to visualize a dataset containing the number of page views each day on the freeCodeCamp.org forum from 2016-05-09 to 2019-12-03. The data visualizations will help you understand the patterns in visits and identify yearly and monthly growth.

- Use Pandas to import the data from "fcc-forum-pageviews.csv". Set the index to the "date" column.
- Clean the data by filtering out days when the page views were in the top 2.5% of the dataset or bottom 2.5% of the dataset.
- Create a draw_line_plot function that uses Matplotlib to draw a line chart similar to _Figure_1.png_
![Figure_1 (2)](https://user-images.githubusercontent.com/91197950/154693953-95fe888c-9094-451c-b7f5-09d11bb9998c.png)

The title should be "Daily freeCodeCamp Forum Page Views 5/2016-12/2019". The label on the x axis should be "Date" and the label on the y axis should be "Page Views".

- Create a draw_bar_plot function that draws a bar chart similar to _Figure_2.png_
![Figure_2 (1)](https://user-images.githubusercontent.com/91197950/154694177-28fe7bad-58c7-410e-b258-b1290b4cd9dd.png)
It should show average daily page views for each month grouped by year. The legend should show month labels and have a title of "Months". On the chart, the label on the x axis should be "Years" and the label on the y axis should be "Average Page Views".
- Create a draw_box_plot function that uses Seaborn to draw two adjacent box plots similar to _Figure_3.png_
![Figure_3](https://user-images.githubusercontent.com/91197950/154694286-97210b2e-7d34-4c34-b668-3fcf45fe85dd.png)
These box plots should show how the values are distributed within a given year or month and how it compares over time. The title of the first chart should be "Year-wise Box Plot (Trend)" and the title of the second chart should be "Month-wise Box Plot (Seasonality)". Make sure the month labels on bottom start at "Jan" and the x and x axis are labeled correctly. The boilerplate includes commands to prepare the data.

Original soure: [Page View Time Series Visualizer](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/page-view-time-series-visualizer)
