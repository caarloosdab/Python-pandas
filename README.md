# Overview

The goal of this software project was to enhance my skills as a software engineer by analyzing real-world data using the Pandas library in Python. 

This project specifically focused on real estate data, where I aimed to extract valuable insights by answering two key questions: (1) What is the average housing price in each region? (2) How do the price, number of bedrooms, and area of homes correlate?

By filtering and manipulating the dataset, I was able to organize the data in a structured way for further analysis and to generate insights that answer these questions.

The dataset used in this project represents real estate data, including housing prices across various regions, details on the area (in square feet), and the number of bedrooms for each house.

The purpose of writing this software was to gain experience in data analysis by focusing on the relationship between house prices, the number of bedrooms, and the area of homes across different regions. Additionally, I aimed to visualize the data and provide meaningful insights into how these variables influence housing prices.

[Software Demo Video](https://ooo.mmhmm.app/watch/z_6TwYRlMx7BPePEnYFBhy)

# Data Analysis Results

1. What is the average housing price in each region, and how do the regions compare in terms of average price?
South: The South region has the highest average housing price, exceeding 700,000.
Central: The Central region has slightly lower average prices than the South, around 650,000.
North: The North region follows closely, with an average price near 600,000.
West: The West region is similar to the North, with prices also nearing 600,000.
East: The East region has the lowest average price, just over 500,000.

2. How does the price of homes with 2 to 4 bedrooms vary with the size (in square feet) of the house, and how does  the number of bedrooms influence this relationship?
Price increases with area: As the house area increases, the price rises, showing a positive linear trend.
Impact of bedrooms on price: For any given area, homes with more bedrooms (4 bedrooms) tend to be priced higher than those with fewer bedrooms (2 or 3 bedrooms).
Clear price groupings: Homes are grouped in distinct price ranges based on the number of bedrooms, with 4-bedroom homes being the most expensive, followed by 3-bedroom and then 2-bedroom homes.



# Development Environment

Tools:
    1. Jupyter Notebook (or a similar Python-based environment): This tool was used for interactive    programming, allowing step-by-step execution of code, easy data manipulation, and  visualization. It also facilitated easy use of Python libraries for data analysis.

    2. CSV Handling: A CSV file was used for input and output of data, representing housing prices,    area, and number of bedrooms. CSV is a standard format for tabular data, easily manipulated    with Python.

    3. Python: The primary programming language used for the Data Analysis. I chose it due to it's simplicity, readability, and rich ecosystem of libraries. It is highly efficient for tasks involving data manipulation, analysis, and visualization

Libraries:

Pandas:

    A powerful library for data manipulation and analysis.
    Used to load, clean, and transform the housing dataset.
    Dataframes (2D tabular structures) were used to perform calculations like average prices, grouping by number of bedrooms, and generating the CSV output.
    Example usage: df.groupby() to aggregate housing prices by region and number of bedrooms.

Matplotlib:

    A plotting library for creating static, animated, and interactive visualizations.
    Used to generate the graphs, such as bar plots and scatter plots, that visually represent relationships between price, area, and bedrooms.
    Example usage: plt.barh() for bar plots and plt.scatter() for scatter plots.

NumPy:

    A library for efficient numerical computations.
    Used indirectly through Pandas for handling arrays and performing mathematical operations on the data.
    Example usage: NumPy arrays were used for calculating statistics like mean or sum.


# Useful Websites

* [Jupiter Lab Documentation](https://jupyterlab.readthedocs.io/en/stable/user/interface.html)
* [10 minutes to pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html)
* [how to use PANDAS in Python in 15 minutes](https://www.youtube.com/watch?v=mkYBJwX_dMs&t=60s)

# Future Work

*  Incorporating geospatial analysis (using libraries like GeoPandas) to map home prices could enhance the visual understanding of regional trends.
* Including more detailed features such as crime rates, school quality, proximity to amenities, or neighborhood ratings could provide a deeper analysis of housing market factors.
* Allowing users to input custom parameters, such as the maximum budget, desired number of bedrooms, or square footage range, would provide tailored recommendations. 