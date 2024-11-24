# Visualization-of-Mass-Shootings-in-USA
This repository contains an interactive visualization of US mass shootings data (2014–2022) using D3.js, featuring choropleth maps, network graphs, and statistical charts to explore geographic and temporal trends.

## Project Structure

The project is organized into the following directories and files:

### 1. **Visualization Files**
- **`Heat Map_files/`**: Contains files for generating heat maps.
- **`Statewise Line Charts/`**: Includes Python scripts and HTML files for visualizing the number of victims injured and killed across states over the years.
- **`js/`**: JavaScript file for creating visualizations using D3.js.
- **`libs/`**: Libraries like D3.js and TopoJSON for rendering interactive maps.
- **`css/`**: Styling files used in the visualizations.

### 2. **Data Files**
- **`data/`**: Contains all data-related files:
  - `counties.json`: Data about US counties.
  - `counties_choropleth.json`: Data for choropleth map visualizations of counties.
  - `counties_year.json`: Year-wise analysis data for counties.
  - `filtered_mass_shootings.csv`: Filtered mass shootings data (CSV format).
  - `mass_shootings.json`: JSON file with mass shootings data.
  - `mass_shootings_2014_2022.csv`: Main dataset for mass shootings in the US (2014-2022).
  - `network.json`: Data for network visualizations.
  - `us_counties_topo.json`: TopoJSON file for rendering US counties on maps.

### 3. **HTML Files**
- **`Heat Map.html`**: Displays heat map visualizations.
- **`Statewise Line Charts.html`**: Displays state-wise line chart visualizations for victims injured and killed.
- **`choropleth.html`**: Displays choropleth map visualizations.
- **`index.html`**: Main entry point for the interactive visualizations.
- **`index_injured_network_vis.html`**: Network visualization for injured victims.
- **`index_killed_network_vis.html`**: Network visualization for killed victims.

### 4. **Python Scripts and Notebooks**
- **`Consolidate_data.ipynb`**: Jupyter notebook used for cleaning and processing the mass shootings dataset.
- **`__init__.py`**: Initialization file for Python-related scripts.

### 5. **Miscellaneous Files**
- **`network_data.gml`**: Data file for network visualizations.


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
