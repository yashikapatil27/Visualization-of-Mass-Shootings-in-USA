# Visualization-of-Mass-Shootings-in-USA
This repository contains an interactive visualization of US mass shootings data (2014–2022) using D3.js, featuring choropleth maps, network graphs, and statistical charts to explore geographic and temporal trends.

## Project Structure
The project is organized into the following directories and files:

- **Heat Map_files**: Files for generating heat map visualizations.
- **Statewise Line Charts**: Python script and HTML files for visualizing victims injured and killed by state over the years.
- **assets**: Images, fonts, and media.
- **css**: Styling files for visualizations.
- **data**: Data files:
  - `counties.json`
  - `counties_choropleth.json`
  - `counties_year.json`
  - `filtered_mass_shootings.csv`
  - `mass_shootings.json`
  - `mass_shootings_2014_2022.csv`
  - `network.json`
  - `us_counties_topo.json`
- **js**: JavaScript file (`visualization.js`) for visualizations using D3.js.
- **libs**: D3.js and TopoJSON libraries.
- **Consolidate_data.ipynb**: Jupyter notebook for cleaning and processing data.
- **Heat Map.html**: HTML for heat map visualizations.
- **Statewise Line Charts.html**: HTML for state-wise line chart visualizations.
- **`__init__.py`**: Initialization file for Python scripts.
- **choropleth.html**: Choropleth map visualization HTML.
- **index.html**: Main HTML file for visualizations.
- **index_injured_network_vis.html**: Network visualization for injured victims.
- **index_killed_network_vis.html**: Network visualization for killed victims.
- **network_data.gml**: Data file for network visualization.

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
