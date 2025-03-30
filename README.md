# FuelFinder Houston
![Python](https://img.shields.io/badge/Python-3.8-blue)
![Tableau](https://img.shields.io/badge/Tableau-Public-orange)
![Data Science](https://img.shields.io/badge/Data%20Science-Project-green)

When your car’s fuel drops below 10%, you need a quick way to find nearby gas stations. This project simulates a Houston-based car’s location, clusters gas stations using K-means, calculates distances with Haversine, and recommends the cheapest stations within 10 miles. Built with Jupyter and visualized in Tableau Public, it’s a practical solution inspired by my family’s automotive roots (40 years at Ford, Bosch project management).

## Approach
1. **Data Fetching:** Used Overpass QL to pull Houston gas station data in Jupyter.
2. **Clustering:** Applied K-means (5 clusters) to group stations spatially using Python.
3. **Spatial Analysis:** Calculated distances from the car to stations using Haversine (R=3959 miles).
4. **Recommendations:** Filtered stations within 10 miles of the nearest cluster, sorted by price.
5. **Visualization:** Created an interactive Tableau dashboard with a map (stations, car, centroids, hub-and-spoke paths) and a recommendations table with hover effects.

## Technologies Used
- **Python:** Pandas, Scikit-learn (K-means)
- **Jupyter:** For code development and data processing
- **Tableau Public:** My first exploration using Tableau.

## Results
- **Tableau Hub and Spoke + Clusters:** [Haversine Display](https://public.tableau.com/views/NearestStations-HaversineDistance/Lines?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) [Gas Station Clusters](https://public.tableau.com/views/Visuals_17432687769480/Points?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## How to Run
1. Clone the repo: `git clone [repo-link]`
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook in Jupyter: `fuelfinder_houston.ipynb` (may require debug based on version).
4. Run all cells to generate the data and CSVs.
5. View the Tableau above.

## Personal Story
Inspired by my grandfather’s 40 years as a Ford testing engineer and my father’s work at Bosch, this project reflects my passion for automotive systems and data-driven solutions. 

## Contact
- Portfolio: [Wes Harrison](http://www.wesharrison.info)
- GitHub: [My GitHub Profile](https://github.com/harriswe)
- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/wmharrison42/)
