🧮 Distance Calculator API

This repository contains the backend service for the Distance Calculator WebGIS App
.
It provides a simple JSON API that calculates the great-circle distance (in kilometers) between two points on Earth, given their latitude and longitude coordinates.
The service is written in Node.js and hosted on Render.

🌐 Live API

Base URL:
👉 https://distancecalc-lgn7.onrender.com

Example request
https://distancecalc-lgn7.onrender.com/?latA=53.921&lonA=9.517&latB=54.323&lonB=10.135

Example response
{
  "distance": 60.17
}

⚙️ Technical Overview
Feature	Description
Language	JavaScript (Node.js)
Framework	None (native http module)
Formula	Spherical law of cosines
Output	JSON (distance in kilometers)
Hosting	Render.com
🗺️ Related Frontend App

The frontend interface (map and form) is built using Leaflet and hosted on GitHub Pages:
👉 Distance Calculator WebGIS App

This app sends requests to the API above and visualizes both locations on an interactive map.

🧩 Project Structure
Distance-Calculator-API/
├── distanceServer.js   # Node.js backend logic
├── package.json        # Dependencies & metadata
└── README.md           # Project documentation (this file)

📈 Future Improvements

Add support for geocoding (enter place names instead of coordinates)

Add travel-time estimation (walking / driving)

Integrate with open geospatial datasets for educational demos

👨‍💻 Author

Sayed Hussain Mosavi
🌍 WebGIS Portfolio

📅 October 2025

✅ This API is part of a growing collection of small, educational WebGIS projects exploring data visualization and geospatial web development.
