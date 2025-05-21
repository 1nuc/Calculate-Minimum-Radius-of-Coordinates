# Minimum Radius Calculator for Geographical Coordinates

This tool calculates the **minimum radius** that can encompass **all given geographical coordinates** provided by the user in a CSV file.

## 🔍 Overview

The application is designed to find the **smallest possible circle** that contains all points (latitude and longitude pairs) on a map. It’s useful for:
- Estimating the spatial footprint of a dataset
- Determining geofencing boundaries
- Visualizing coverage zones

## 📥 Input Format

The tool expects a CSV file with **explicitly named columns**:
Latitude, Longitude

Each row must represent a valid geographical coordinate:
- `Latitude` in decimal degrees (e.g., `34.0522`)
- `Longitude` in decimal degrees (e.g., `-118.2437`)

Example:

```csv
Latitude,Longitude
34.0522,-118.2437
36.7783,-119.4179
37.7749,-122.4194
```
## Future Enhancements
- Handle files where latitude and longitude columns use different or unexpected names (e.g., lat, lng, geo_lat).
- Interactive 3D Map Visualization
- Enable drag-and-drop CSV upload through a web interface with instant feedback.
- Accept more geographic data formats beyond CSV.

