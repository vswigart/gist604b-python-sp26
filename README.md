# Assignment 3: Python GIS and Containerization

- **Student:** Victoria Swigart
- **Course:** GIST 604B – Open Source GIS
- **Module:** Module 3 – Python GIS and Containerization
- **University of Arizona**

## Project Description

This project develops foundational Python GIS skills using pandas, GeoPandas, and Rasterio within a containerized development environment. The assignment includes working through guided Jupyter Notebooks, implementing functions in Python scripts, validating code with pytest, and completing a full raster analysis workflow. The work emphasizes reproducible GIS analysis, modular Python development, and version‑controlled workflows using GitHub Codespaces.

## Tools and Technologies

- Python (pandas, GeoPandas, Rasterio)
- Jupyter Notebooks
- pytest
- GitHub Codespaces (containerized development environment)

## What I Did

- Forked the assignment repository and worked entirely within a GitHub Codespace
- Completed pandas notebooks and implemented required functions in src/pandas_basics.py
- Completed GeoPandas notebooks and implemented required functions in src/geopandas_basics.py
- Ran pytest to validate pandas and GeoPandas implementations
- Completed a full raster workflow using Rasterio in remote_sensing_workflow.ipynb

## How to View / Run
- Open Jupyter Notebooks:  
Navigate to the notebooks/ directory and open any .ipynb file in Codespaces
- Run Python functions:  
Functions are implemented in src/pandas_basics.py and src/geopandas_basics.py
- Run tests:  
In the Codespaces terminal:
uv run pytest tests/test_pandas_basics.py -v  
uv run pytest tests/test_geopandas_basics.py -v
- View raster workflow:  
Open notebooks/rasterio/remote_sensing_workflow.ipynb and run all cells

## Repository Structure 
```
/
├── notebooks/
│   ├── pandas/
│   │   ├── 01_load_and_explore_data.ipynb
│   │   ├── 02_filter_environmental_data.ipynb
│   │   ├── 03_calculate_station_statistics.ipynb
│   │   └── 04_join_station_data.ipynb
│   ├── geopandas/
│   │   ├── 01_load_spatial_data.ipynb
│   │   ├── 02_explore_geometries.ipynb
│   │   ├── 03_coordinate_systems.ipynb
│   │   ├── 04_function_geometry_operations.ipynb
│   │   ├── 05_function_spatial_relationships.ipynb
│   │   ├── 06_function_spatial_joins.ipynb
│   │   └── 07_function_overlay_and_visualize.ipynb
│   └── rasterio/
│       └── remote_sensing_workflow.ipynb
├── src/
│   ├── pandas_basics.py
│   ├── geopandas_basics.py
│   └── download_real_data.py
├── tests/
│   ├── test_pandas_basics.py
│   ├── test_geopandas_basics.py
├── data/
│   ├── cities/
│   │   └── ne_cities_us.geojson
│   ├── ecoregions/
│   │   └── epa_level3_western_us.geojson
│   ├── protected_areas/
│   │   └── national_parks_major.geojson
│   ├── neighborhood_samples.geojson
│   ├── temperature_readings.csv
│   └── weather_stations.csv
├── .devcontainer/
│   ├── devcontainer.json
│   └── DockerFile
├── .gitignore
├── pyproject.toml
├── uv.lock
└── README.md
```
