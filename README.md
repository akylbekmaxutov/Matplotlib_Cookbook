## Part 1

**Level 1: Basic Plotting**

1. **Problem**: Plot a simple line graph of the numbers 1 through 10.
   - **Initial Data**: `x = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]`, `y = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]`
   - **Hint**: Use `plt.plot()`.

2. **Problem**: Create a scatter plot of random data with 100 points.
   - **Initial Data**: Randomly generated x and y values.
   - **Hint**: Use `plt.scatter()`.

**Level 2: Customization**

3. **Problem**: Customize the appearance of the line in the previous line graph.
   - **Initial Data**: The same data as in Problem 1.
   - **Hint**: Experiment with parameters like color, linestyle, and marker.

4. **Problem**: Create a bar chart of the number of apples, bananas, and oranges sold.
   - **Initial Data**: `fruits = ['Apples', 'Bananas', 'Oranges']`, `sales = [25, 32, 18]`
   - **Hint**: Use `plt.bar()`.

**Level 3: Subplots and Multiple Figures**

5. **Problem**: Create two line plots on separate subplots in a single figure.
   - **Initial Data**: Two sets of x and y data.
   - **Hint**: Use `plt.subplot()` or `plt.subplots()`.

6. **Problem**: Create a figure with two side-by-side bar charts showing sales for two different years.
   - **Initial Data**: Data for two years (e.g., sales1 = [25, 32, 18], sales2 = [30, 28, 20]).
   - **Hint**: Use `plt.subplot()` or `plt.subplots()`.

**Level 4: Annotations and Legends**

7. **Problem**: Add labels and a title to a scatter plot.
   - **Initial Data**: Randomly generated data.
   - **Hint**: Use `plt.xlabel()`, `plt.ylabel()`, and `plt.title()`.

8. **Problem**: Create a line graph with two lines and add a legend.
   - **Initial Data**: Two sets of x and y data.
   - **Hint**: Use `plt.legend()`.

**Level 5: Advanced Plot Types**

9. **Problem**: Create a pie chart showing the distribution of sales for different products.
   - **Initial Data**: Product names and their sales percentages.
   - **Hint**: Use `plt.pie()`.

10. **Problem**: Plot a 3D surface plot of a mathematical function.
    - **Initial Data**: A function that depends on two variables, e.g., `z = f(x, y)`.
    - **Hint**: Use `mpl_toolkits.mplot3d` for 3D plots.

**Level 6: Interactive and Real-time Plots**

11. **Problem**: Create an interactive plot with zoom and pan functionality.
    - **Initial Data**: Any data you prefer.
    - **Hint**: Use `mpl_connect()` to connect interactive functions.

12. **Problem**: Create a real-time plot that updates every second with random data points.
    - **Initial Data**: Randomly generated data.
    - **Hint**: Use `FuncAnimation` from the `matplotlib.animation` module.

**Level 7: Customizing Colors and Styles**

13. **Problem**: Create a line graph with a custom color palette.
    - **Initial Data**: Data for the line plot.
    - **Hint**: Customize the color cycle using `plt.gca().set_prop_cycle()`.

14. **Problem**: Create a radar chart (spider plot) to compare multiple variables for different categories.
    - **Initial Data**: Data for different categories and variables.
    - **Hint**: Use `plt.fill()` to create a polygon with vertices.

**Level 8: Geographical Plots**

15. **Problem**: Plot a world map with countries colored based on a data attribute (e.g., population).
    - **Initial Data**: Data associating countries with the attribute of interest.
    - **Hint**: Use libraries like `basemap` or `geopandas`.

16. **Problem**: Create a heatmap of a 2D dataset on a geographical map (e.g., temperature data for cities).
    - **Initial Data**: Data points with latitude, longitude, and values.
    - **Hint**: Use `imshow` and geographic projections.

These problems cover a wide range of matplotlib features and techniques. Depending on your level of expertise, you can pick and choose the ones that are most suitable for your learning needs.

## Part 2

Certainly! Here are 20 more matplotlib problems of varying levels:

**Level 1: Basic Plotting**

1. **Problem**: Plot a histogram of 1000 random data points.
   - **Initial Data**: Randomly generated data.
   - **Hint**: Use `plt.hist()`.

2. **Problem**: Create a line plot of a sine wave (sin(x)) for values of x ranging from 0 to 2π.
   - **Initial Data**: Generate x values in the specified range.
   - **Hint**: Use numpy functions to generate data and `plt.plot()`.

**Level 2: Customization**

3. **Problem**: Customize the appearance of a bar chart, changing the color and edge color of the bars.
   - **Initial Data**: Data for the bar chart.
   - **Hint**: Explore the `color` and `edgecolor` parameters of `plt.bar()`.

4. **Problem**: Create a scatter plot with labeled points (e.g., cities on a map) and tooltips displaying city names.
   - **Initial Data**: Coordinates of cities and city names.
   - **Hint**: Use annotations and interactive tooltips.

**Level 3: Subplots and Multiple Figures**

5. **Problem**: Create a figure with 4 subplots arranged in a 2x2 grid, each showing different data.
   - **Initial Data**: Four sets of data.
   - **Hint**: Use `plt.subplot()` or `plt.subplots()`.

6. **Problem**: Create a set of line plots in a single figure, each with a different linestyle.
   - **Initial Data**: Multiple sets of x and y data.
   - **Hint**: Vary the `linestyle` parameter in `plt.plot()`.

**Level 4: Annotations and Legends**

7. **Problem**: Annotate specific points on a line plot with labels.
   - **Initial Data**: Data for the line plot and the points to annotate.
   - **Hint**: Use `plt.annotate()`.

8. **Problem**: Create a line graph with a legend, and customize the legend location and labels.
   - **Initial Data**: Two sets of x and y data.
   - **Hint**: Use `plt.legend()` with location and labels.

**Level 5: Advanced Plot Types**

9. **Problem**: Plot a violin plot to visualize the distribution of a dataset.
   - **Initial Data**: A dataset to visualize.
   - **Hint**: Use `plt.violinplot()`.

10. **Problem**: Create a 3D scatter plot of random data points in a given range.
    - **Initial Data**: Randomly generated 3D data.
    - **Hint**: Use `Axes3D` for 3D plotting.

**Level 6: Interactive and Real-time Plots**

11. **Problem**: Create a zoomable and pannable image viewer for a large image.
    - **Initial Data**: A large image.
    - **Hint**: Use `imshow()` and add zoom/pan functionality.

12. **Problem**: Build a real-time stock price chart that updates every minute.
    - **Initial Data**: Stock price data with timestamps.
    - **Hint**: Use `FuncAnimation` to update the plot.

**Level 7: Customizing Colors and Styles**

13. **Problem**: Create a stacked bar chart with custom colors for each section of the bars.
    - **Initial Data**: Data for the stacked bars.
    - **Hint**: Use `plt.bar()` with the `bottom` parameter.

14. **Problem**: Generate a polar plot (radar chart) displaying multiple data series on different axes.
    - **Initial Data**: Data for the radar chart.
    - **Hint**: Use `polar` projection and multiple axes.

**Level 8: Geographical Plots**

15. **Problem**: Create a choropleth map of a country or region with color-coded regions based on data values.
    - **Initial Data**: Region data and corresponding values.
    - **Hint**: Utilize geospatial libraries like `geopandas`.

16. **Problem**: Plot a geographic path on a map, showing the route between two or more cities.
    - **Initial Data**: Coordinates of cities and the route.
    - **Hint**: Use `Basemap` or similar libraries for geographic plotting.

These additional problems cover a wide range of matplotlib features and challenges. Choose the ones that align with your learning goals and experience level.
