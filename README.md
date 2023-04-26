# San Francisco Neighborhood Analysis

This Jupyter notebook contains an analysis of San Francisco neighborhoods using real estate data. The goal is to provide insights on the potential one-click, buy-and-rent strategy for an investment company.

## Getting Started

### Dependencies

- Python 3.x
- Jupyter Lab
- pandas
- hvplot
- geoviews

### Data

The data used in this analysis comes from a DataFrame named `sfo_data_df`. The DataFrame contains information about San Francisco neighborhoods, including sales prices per square foot, housing units, and gross rent.

## Analysis

The analysis consists of the following steps:

1. **Data Cleaning and Preparation**: Create a DataFrame named `neighborhood_locations_df` that contains latitude and longitude coordinates for each neighborhood. Then, create a DataFrame named `all_neighborhood_info_df` that groups the data by neighborhood and calculates the mean values for each group.

2. **Data Concatenation**: Create a DataFrame named `all_neighborhoods_df` by concatenating `neighborhood_locations_df` and `all_neighborhood_info_df`. Clean the data and set the "Neighborhood" column.

3. **Geospatial Visualization**: Create a points plot for the `all_neighborhoods_df` DataFrame using hvPlot with GeoViews enabled. Set parameters such as `geo`, `size`, `color`, `frame_width`, `frame_height`, and `title` to create a comprehensive visualization.


## Results

Based on the visualizations, the following insights can be shared:

- There is a general positive relationship between rental income growth and sales prices in San Francisco neighborhoods. However, this pattern is not consistent across every neighborhood.
- The one-click, buy-and-rent strategy has the potential to be successful, but its effectiveness will depend on choosing the right neighborhoods.
- It's essential to find areas that strike a good balance between rental income growth and sales prices. Neighborhoods with higher rental income growth and lower sales prices might offer better return on investment opportunities. Conversely, areas with high sales prices and low rental growth may not be the best fit for a buy-and-rent strategy.

## Conclusion

Understanding the unique market dynamics and features of each San Francisco neighborhood is crucial for a successful one-click, buy-and-rent strategy. By analyzing the trends in rental income growth and sales prices, investment companies can make informed decisions about which neighborhoods to target for their strategy.

## Contributors

This was an effort made possible by the teachings of the wonderful instructor Firas, along with contributions by James White.

## License

You may use this source code as you need to.

