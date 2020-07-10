# Clustering Geolocation Data
## Data
Taxi rank location data (latitude, longitude) from Johannesburg, South Africa, is used to form clusters to determine viable locations for taxi servicing stations in Johannesburg.

## Project.ipynb
K-Means clustering is first used to get an idea of cluster formation, these clusters are displayed on an interactive map created using Folium (a Python library). Outliers are detected using DBSCAN and HDBSCAN, to include these in the nearest cluster a hybrid clutering method is used.

Each taxi rank is displayed in a different colour in the map. The number displayed when a circle is clicked represents the cluster/rank that circle belongs to.

## HTML docs
ProjectOutcome.html shows you the outcome of the project and what the final map with Geolocation clusters will look like. Each interactive map generated while executing the code will be automatically saved on your system in .html format, i.e., kmeans_70.html and hybrid.html.
