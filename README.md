# Visualization-of-Mass-Shootings-in-USA
This repository contains an interactive visualization of US mass shootings data (2014–2022) using D3.js, featuring choropleth maps, network graphs, and statistical charts to explore geographic and temporal trends.

## Project Structure

- **`Heat Map_files`**: Contains files for generating heat maps.
- **`Statewise Line Charts`**: Python script and HTML files to visualize the number of victims injured and killed across states over the years.
- **`assets`**: Folder for images, fonts, and other media.
- **`css`**: Contains styling files for the visualizations.
- **`data`**: Contains the following data files:
  - `counties.json`: JSON file containing data about US counties.
  - `counties_choropleth.json`: Data used for choropleth map visualizations of counties.
  - `counties_year.json`: Data for year-wise analysis of counties.
  - `filtered_mass_shootings.csv`: CSV file with mass shootings data (filtered).
  - `mass_shootings.json`: JSON file with mass shootings data.
  - `mass_shootings_2014_2022.csv`: Main dataset of mass shootings in the US between 2014 and 2022.
  - `network.json`: Data used for network visualizations.
  - `us_counties_topo.json`: TopoJSON file for rendering US counties in interactive maps.
- **`js`**: JavaScript file for visualizations using D3.js.
- **`libs`**: Includes the D3.js and TopoJSON libraries for rendering interactive maps.
- **`Consolidate_data.ipynb`**: Jupyter notebook for cleaning and processing the dataset.
- **`Heat Map.html`**: HTML file for heat map visualization.
- **`Statewise Line Charts.html`**: HTML file for the state-wise line chart visualizations.
- **`__init__.py`**: Initialization file for Python-related scripts.
- **`choropleth.html`**: HTML for choropleth map visualizations.
- **`index.html`**: Main entry point for interactive visualizations.
- **`index_injured_network_vis.html`**: Network visualization for injured victims.
- **`index_killed_network_vis.html`**: Network visualization for killed victims.
- **`network_data.gml`**: Data file for network visualization.

## Technologies Used

- **D3.js**: Used for creating interactive data visualizations such as choropleth maps and network visualizations.
- **Plotly**: Used to generate interactive line charts and heat maps.
- **Python (Pandas, Plotly)**: Python scripts for data processing and visualization creation.
- **HTML/CSS**: For structuring and styling the web-based visualizations.

## Data Sources

The data for this project is sourced from the [Gun Violence Archive](https://www.gunviolencearchive.org/), which tracks mass shootings and other gun-related incidents across the United States.

## Getting Started

1. Clone this repository to your local machine.
2. Install the required dependencies:
   - For Python visualizations, ensure you have `pandas` and `plotly` installed.
   - For web visualizations, make sure you have a web browser to view the HTML files.
3. Open `index.html` to view the interactive visualizations.

## Contribution
Feel free to fork this repository, make changes, and submit pull requests. If you encounter any issues, please raise them in the issues section.
