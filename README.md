# Geocoding with Docker-Nominatim and Python

![Geocoding Workflow](Geocoding/pic.jpg)  

### 🚀 A parallelized geocoding workflow leveraging **Docker - Nominatim** and **Micromamba**, also applying libraries like **GeoPy** and **GeoPandas**, to convert textual addresses into geographic coordinates (lat, lon). Developed remotely on the CCAD-UNC High-Performance Computing Cluster via SSH connection.  
-----------------------------------------------------------------------------------------------------------------------------------------------
### You may be able to adjust and replicate this code for your own pourposes. You can use it to assign geometry points (lat, lon) to a series of different written addresses.
-----------------------------------------------------------------------------------------------------------------------------------------------

## ⚙️ Usage

- Docker
- Python 3.8+ (`geopandas`, `geopy`, `jupyter notebooks`)
- Nominatim Docker image (e.g., [`mediagis/nominatim`](https://github.com/mediagis/nominatim-docker))
- Follow the instructions from ssh_docker.txt
