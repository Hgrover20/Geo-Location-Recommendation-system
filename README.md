# Location-Recommendation-system
This project presents a data-driven framework to identify the most suitable locations for opening new retail stores using **Geographic Information Systems (GIS)** and **Machine Learning**.It integrates spatial data, demographic indicators, and clustering algorithms to support urban planning and business strategy.

## 📌 Objective

To recommend optimal retail store locations in Delhi by analyzing:

- Population density  
- Income levels  
- Existing venue distribution  
- Residential area

## 📊 Methodology

The approach combines:

- 🗺️ **GIS data**: Neighborhoods, Points of Interest (POIs) using Foursquare API  
- 📈 **Demographics**: Population and average monthly expenditures from government sources  
- 🧪 **Clustering algorithms**:  
  - K-Means  
  - Agglomerative Hierarchical Clustering  
  - HDBSCAN  

These models segment Delhi into clusters based on suitability for retail expansion.

## 🔍 Key Features

- Venue classification and one-hot encoding
- Population-to-supermarket ratio analysis
- Residential score-based filtering
- Interactive mapping with Folium
- Multi-model cluster comparison
- Final recommendation table for retail location planning

## 📂 Data Sources

- [Wikipedia](https://en.wikipedia.org) – Neighborhood data  
- [Foursquare API](https://developer.foursquare.com) – Venue data  
- Delhi Government/Census data – Demographics

## 📍 Results

Among all clustering approaches, **HDBSCAN** was found to be most effective due to its adaptability to spatial density variations and noise filtering. The final output highlights neighborhoods in Delhi that are:

- Highly residential  
- Underserved by existing supermarkets  
- Economically viable for retail expansion

## 📈 Potential Applications

- Urban planning  
- Retail market expansion  
- Real estate analytics  
- Smart city development
