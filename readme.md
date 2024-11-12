# US Disaster Damage Map

## Project Overview
This project visualizes disaster damage costs across the United States using GeoJSON data in a Leaflet map. Each point on the map represents a state or area in the US with data on disaster damage measured in millions of dollars. The map allows users to explore and analyze areas with the highest and lowest disaster-related economic impacts.

## Data
The data used in this project is sourced from various disaster records, with each point representing a specific state or region in the United States. The data includes:
- `id`: State or region abbreviation
- `lat` and `long`: Latitude and longitude of the region
- `total damage (million$)`: Total damage cost in millions of dollars for that region

## Features
- **Interactive map with point markers**: Each point on the map displays the total damage cost when clicked.
- **GeoJSON data**: Data is organized in GeoJSON format for ease of use with Leaflet.
- **Color-coded markers**: Each marker is colored based on the magnitude of the disaster damage for quick visual reference.

## Technologies Used
- **Leaflet.js**: For interactive mapping and visualization
- **GeoJSON**: For data representation
- **GitHub Pages**: To host the map publicly

## Getting Started

### Prerequisites
- Basic knowledge of HTML, JavaScript, and Git
- Leaflet.js library (included via CDN)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/ameliabarwick/US-Disaster-Damage-Map.git
