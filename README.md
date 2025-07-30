# BlablaCar-Study-Case

This repository contains a single Jupyter notebook: **`study_case.ipynb`**. The notebook is well documented and easy to navigate.

## Important Information Before Running the Notebook

1. **Python Version & Required Libraries**  
   The notebook is developed using **Python 3.13.5**.  
   To run it, make sure the following libraries are installed:
   - `pandas`
   - `openrouteservice`
   - `folium`

2. **OpenRouteService API Key**  
   This project uses the **OpenRouteService** free API for routing and geospatial data. You will need a personal API key to run the program.
   - Create a free account at [https://openrouteservice.org/](https://openrouteservice.org/)
   - Insert your **personal API key** into the corresponding cell in the notebook.

3. **API Limitations**  
   Please note that the OpenRouteService API has usage limits:
   - **40 requests per minute**
   - **2,000 requests per day**

   These limits may affect repeated execution of the notebook in a short timeframe, so the code is not "working whatever the number of times we run the program". 
   However, the limitations are reasonable for the scope of this project.

   An alternative approach using the **BlaBlaCar Bus GTFS dataset** was considered, but the required `shapes` table was unfortunately empty, making that option unworkable.
