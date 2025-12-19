#  NYC Taxi Network Analysis using Network Science

This project applies network science techniques to New York City’s taxi and for-hire vehicle (FHV) trip data to uncover hidden patterns in urban mobility. By modeling trip flows as a directed, weighted graph, we identify high-demand zones, analyze spatiotemporal connectivity, and extract actionable insights to improve transportation systems.

---

##  Project Structure

- `EDA.ipynb` – Initial exploratory data analysis (trip volume, distribution, zone activity)
- `Preprocessing.ipynb` – Data cleaning, feature engineering, zone ID mapping, outlier handling
- `Naming_zones_with_locid.ipynb` – Mapping NYC location IDs to zone names and boroughs
- `year_by_year_clean.ipynb` – Year-wise cleaned data prep for scalable network construction
- `Network_Analysis.ipynb` – (Coming Soon) Graph construction, centrality measures, clustering, visualization

---

##  Objectives

- Construct a **directed weighted network graph** with zones as nodes and trip flows as edges
- Analyze **centrality measures** to identify major hubs and critical transit links
- Apply **community detection** to uncover natural groupings in the taxi flow network
- Visualize the network geospatially and extract insights to improve urban transportation planning

---

##  Key Features

- Pickup/Drop-off zone mapping
- Trip counts, durations, and fare aggregation
- Zone-level temporal slicing (e.g., hourly, weekly)
- Centrality & community structure analysis
- Interactive map-based network visualizations

---

##  Dataset

- **Size**: ~60 GB (NYC Yellow/Green Taxi + FHV Data)
- **Source**: NYC Taxi & Limousine Commission (TLC) public trip data  
  [https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

---

##  Tech Stack

- **Python**: pandas, numpy, matplotlib, seaborn
- **Network Science**: networkx, igraph
- **Geospatial**: geopandas, folium, plotly
- **Data Processing**: Jupyter, Dask (optional for scale), Parquet/Feather

---

##  Challenges

- Handling massive datasets efficiently (~60GB)
- Dealing with missing or inconsistent trip and zone data
- Managing time-based variability and seasonality in trip flows
- Visualizing dense networks without clutter

---

##  Outcomes (In Progress)

- Visual identification of NYC’s busiest transit corridors
- Zone-level centrality rankings and hub classification
- Community clusters showing localized mobility zones
- Temporal insights for peak-time routing and resource allocation

---

##  Future Work

- Add weather and event data overlays
- Temporal network graphs (e.g., dynamic networks by day/hour)
- Extend to other cities for comparison
- Integrate with optimization models for routing and dispatch

---

##  Contact

**Hariprakash Karthikeyan**  
Master's in Data Science, University of Rochester  
📫 [LinkedIn](https://www.linkedin.com/in/hariprakash-karthikeyan/) | 📧 hariprakashkarthikeyan@gmail.com

---

