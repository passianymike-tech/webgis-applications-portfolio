# Web GIS & Desktop Application Development Portfolio

A portfolio of **10 GIS applications** (5 web-based + 5 desktop) demonstrating expertise in full-stack geospatial application development using the ArcGIS ecosystem and open-source tools.

---

## Web GIS Applications (5)

### WEB-01: Eastern Mau Forest LULC Change Web Map
**Live**: [papayai.droneverse.pro/webmap/](https://papayai.droneverse.pro/webmap/) | **Code**: [GitHub](https://github.com/Papsmyk/Eastern-Mau-Forest-Reserve-Land-Cover-and-Land-Use-Change-Web-Map)

Interactive web map for visualizing 40 years of land cover changes in the Eastern Mau Forest Reserve.

**Features:**
- Temporal slider for 6 epochs (1984–2024)
- Three layer groups: Classified Maps, Density Slices, Thematic Change Analysis
- Legend with color-coded land cover classes
- Basemap toggle (OpenStreetMap, satellite)
- Responsive design for mobile/desktop

**Tech Stack**: Leaflet.js, JavaScript, Node.js, GeoTIFF.js, HTML/CSS

---

### WEB-02: Kenya Drone No-Fly Zone Platform
**Live**: [papayai.droneverse.pro/drone-no-flyzone/](https://papayai.droneverse.pro/drone-no-flyzone/) | **Code**: [GitHub](https://github.com/Papsmyk/webmap-termpaper)

Real-time compliance platform for drone operators in Kenya showing restricted airspace zones.

**Features:**
- KCAA restricted zone overlays (airports, military, national parks)
- Buffer zone visualization with distance calculations
- Shapefile data loaded as GeoJSON layers
- Search functionality for location-based zone checking
- Password-protected admin area management

**Tech Stack**: Leaflet.js, JavaScript, Node.js, Shapefiles/GeoJSON

---

### WEB-03: GIS-Based Livelihood Analysis Portal
Web application for spatial analysis of livelihood patterns and community resource mapping.

**Features:**
- Thematic maps of livelihood indicators by region
- Interactive charts linked to map selections
- Multi-criteria analysis visualization
- Data download in CSV and GeoJSON formats
- Stakeholder comment/feedback system

**Tech Stack**: Leaflet.js, JavaScript, Python (Flask), PostgreSQL/PostGIS

---

### WEB-04: Smart Agriculture Platform
Web-based precision agriculture monitoring system integrating drone, satellite, and IoT sensor data.

**Features:**
- Real-time NDVI health maps from Sentinel-2
- Drone survey orthophoto overlay
- Weather data integration
- Crop health alert system
- Field boundary management

**Tech Stack**: React, ArcGIS API for JavaScript, Node.js, PostgreSQL/PostGIS

---

### WEB-05: Community Resource Mapping Application
Participatory GIS web application for community-driven resource mapping and planning.

**Features:**
- Public contribution portal for mapping community assets
- Admin dashboard for data validation and approval
- Multi-layer thematic mapping (health, education, water, roads)
- Statistical dashboard with auto-generated reports
- Offline-capable with service worker

**Tech Stack**: Vue.js, Leaflet.js, Node.js, MongoDB

---

## Desktop GIS Applications (5)

### DESK-01: ArcGIS Pro LULC Classification Toolkit
Automated supervised classification pipeline built in ArcGIS Pro with ArcPy scripting.

**Features:**
- Batch processing of multi-temporal satellite imagery
- Automated training sample management
- Maximum Likelihood / Random Forest classification
- Accuracy assessment with confusion matrix generation
- Map template-based batch export (PDF, PNG at 300 DPI)
- Change detection between consecutive epochs

**Tech Stack**: ArcGIS Pro 3.2, ArcPy, Python, Spatial Analyst

---

### DESK-02: Hydrological Analysis & Watershed Delineation Tool
**Code**: [GitHub](https://github.com/Papsmyk/Hydrological-Analysis---Whitbox-Tools)

Automated watershed analysis tool using WhiteboxTools in Python.

**Features:**
- DEM preprocessing (fill sinks, flow direction, flow accumulation)
- Automated stream network extraction
- Watershed boundary delineation
- Drainage basin area and flow statistics
- Export to shapefile and GeoJSON

**Tech Stack**: Python, WhiteboxTools, QGIS, Jupyter Notebook

---

### DESK-03: Network Analysis & Transport Routing System
Spatial network analysis tool for optimal route computation and service area analysis.

**Features:**
- Dijkstra shortest path computation
- Service area / isochrone generation
- Origin-Destination cost matrix
- Vehicle routing optimization
- Integration with OpenStreetMap road networks

**Tech Stack**: QGIS, Python, pgRouting, PostGIS, OSM data

---

### DESK-04: Cadastral Land Information Management System (LIMS)
Desktop GIS application for land parcel management and cadastral operations.

**Features:**
- Parcel geometry creation, editing, and splitting
- Ownership record management linked to spatial data
- Automated area and perimeter calculations
- Survey plan generation from coordinates
- Export to shapefiles and enterprise geodatabase

**Tech Stack**: ArcGIS Pro, ArcPy, Python, PostgreSQL/PostGIS, File Geodatabase

---

### DESK-05: Environmental Impact Assessment (EIA) Mapping Tool
Desktop tool for systematic EIA spatial data analysis and map production.

**Features:**
- Buffer analysis around proposed development sites
- Sensitive receptor identification (schools, hospitals, water bodies)
- Noise and air quality dispersion modeling visualization
- Before/after land cover comparison
- Standardized EIA map template with automated layout

**Tech Stack**: ArcGIS Pro, QGIS, Python, Spatial Analyst

---

## Technologies Summary

| Category | Technologies |
|----------|-------------|
| **Web Mapping** | Leaflet.js, ArcGIS API for JavaScript, OpenLayers |
| **Frontend** | React, Vue.js, Angular, HTML5/CSS3 |
| **Backend** | Node.js, Python (Flask/Django), REST APIs |
| **Desktop GIS** | ArcGIS Pro, QGIS, ENVI |
| **Database** | PostgreSQL/PostGIS, MongoDB, File Geodatabase |
| **Languages** | JavaScript, Python, SQL, R |
| **DevOps** | Git, GitHub, npm, Docker |

## Author
**Mike Papayai Passiany**
MSc Geographic Information Systems — University of Nairobi
[LinkedIn](https://www.linkedin.com/in/59b641a2/) | [Portfolio](https://papayai.droneverse.pro/)
