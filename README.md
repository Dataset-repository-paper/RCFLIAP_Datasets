# Dataset Repository for  
**Reliable Logistics Network Design Joint Robust Optimization Problem Applying Demand Sensitivity to Correlated Disruptions**

This repository provides the datasets and supporting resources used in the computational experiments of our study on designing reliable logistics networks under correlated disruptions and uncertain demand. The proposed model introduces a joint robust optimization framework that accounts for disruption propagation effects and demand sensitivity, with a focus on applications in emergency and disaster response.

To support reproducibility and further research, we provide:

- **Geospatial data** used for map visualizations in the paper, based on real U.S. city locations.
- **Benchmark datasets** derived from established facility location instances, sourced from census-based data.
---

## 📁 Contents

### 1. Cartography Vectors
- **Format:** GeoJSON  
- **Description:** Source file for generating map-based figures in the paper. It contains geospatial data representing the geographic locations of cities used in the study.  
- **Use Case:** Can be visualized using GIS tools or Python libraries such as GeoPandas and Folium.

---

### 2. Benchmark Datasets
Two benchmark datasets are provided based on standard facility location problem instances from:

> *Network and Discrete Location: Models, Algorithms, and Applications*

#### Files:
- `49_nodes_dataset.txt`
- `88_nodes_dataset.txt`

These datasets are widely adopted in location science literature and serve as trusted baselines for facility location models.
#### Column Descriptions:
- **No.:** Number
- **Long.:** Longitudes
- **Lat.:** Latitudes 
- **First Demand:** 1990 city population  
- **Second Demand:** Number of households in the city (1990)  
- **Fixed Cost:** 1990 median home value (used to represent facility fixed cost)
- **City:** Cities are sorted by their 1990 population.  
 
#### Data Source:
All information is extracted from the 1990 Population and Housing Census:
- U.S. Department of Commerce (1990a)
- U.S. Department of Commerce (1990b)  


---

### 3. Notes

In addition to the benchmark datasets, our study also utilized several synthetic instances to evaluate model performance under varied disruption and demand scenarios. The generation process is clearly and systematically described in the manuscript, including all parameter settings, distributions, and randomization procedures.

