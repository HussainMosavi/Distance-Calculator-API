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
