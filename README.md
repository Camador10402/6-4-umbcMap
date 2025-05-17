UMBC GPS Campus Map

An interactive GPS-based web application designed to help new students, faculty, and visitors navigate the UMBC campus. This tool provides real-time pathfinding between campus buildings and allows users to explore building information using an intuitive visual interface.

📌 Project Overview
Traditional campus maps can be outdated and hard to interpret. This project solves that by offering:

Real-time GPS navigation

Interactive building selection

Entrance-aware shortest path routing

Mobile and browser compatibility

Built using open-source libraries like Leaflet.js, Turf.js, and Graphlib, the UMBC GPS Campus Map is fully client-side and does not require external servers for basic operation.

🧠 Features
View campus buildings with pop-up descriptions

Set your start location by clicking on the map

Choose your destination from a dropdown menu

Shortest path is drawn on walkable sidewalks and stairs

Route ETA and distance are calculated

Responsive design for mobile and desktop use

🔗 Live Version (No Setup Required)
To use the live version of the project hosted at UMBC:

👉 https://swe.umbc.edu/~ybedass1/home_page.html

All features are fully functional in the browser. No installation required.

💻 Local Setup Instructions
If you want to run the project locally (e.g., to test changes or work offline), follow these steps:

Clone the Repository

bash
Copy
Edit
git clone https://github.com/Camador10402/6-4-umbcMap

cd umbc-gps-campus-map
Download Required Assets
Ensure the following files are present in the root directory:

umbc_map.jpg — A static image map of the campus

umbc_sidewalks.geojson — Walkable sidewalk paths

umbc_steps.geojson — Stairs or elevation change paths

These files are necessary for the routing engine and map overlays.

Start a Local Python Server
From the project folder, run:
python -m http.server 8000
Then open your browser and go to:
http://localhost:8000/home_page.html

This will launch the main portal to access both:

building_information_map_page.html

realtime.html (GPS routing)

🧱 Built With
Leaflet.js – Map rendering library

Turf.js – Geospatial math and calculations

Graphlib – Routing graph construction

HTML/CSS/JavaScript – Core technologies

📁 Project Structure
/umbc-gps-campus-map  
├── home_page.html  
├── building_information_map_page.html  
├── realtime.html  
├── umbc_map.jpg  
├── umbc_sidewalks.geojson  
├── umbc_steps.geojson  
└── README.md
👥 Team Contributors
Christian Amador

Yafet Bedasso

Daniel Geneti

Project for CMSC 447: Software Design and Development – UMBC, Spring 2025
Customer: Omkar Chougule
