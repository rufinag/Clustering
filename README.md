# Clustering Geolocation Data
Taxi rank location data (latitude, longitude) from Johannesburg, South Africa, is used to form clusters to determine viable locations for taxi servicing stations in Johannesburg.
K-Means clustering is first used to get an idea of cluster formation, these clusters are displayed on an interactive map created using Folium (a Python library). Outliers are detected using DBSCAN and HDBSCAN, to include these in the nearest cluster a hybrid clutering method is used.
Each interactive map generated while executing the code will be automatically saved on your system in .html format.
