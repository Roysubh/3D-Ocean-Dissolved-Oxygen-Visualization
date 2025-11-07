🌊 3D Ocean Dissolved Oxygen Visualization

📄 Overview:
This project visualizes the mean dissolved oxygen concentration in the world’s oceans using the NOAA World Ocean Atlas 2023 (WOA23) dataset. An interactive 3D globe is generated with Python, Xarray, and Plotly, allowing users to explore oxygen levels at multiple depths. Land areas are highlighted for geographic context, and a background image enhances realism.

📊 Project Specifications:
| Attribute          | Details                                                                |
| ------------------ | ---------------------------------------------------------------------- |
| **Title**          | 3D Ocean Dissolved Oxygen Visualization                                |
| **Study Area**     | Global Oceans (0–1500 m depth)                                         |
| **Data Sources**   | NOAA WOA23 – Dissolved Oxygen (O₂), NetCDF format                      |
| **Period**         | 1965–2022 (all-data climatology)                                       |
| **Platform**       | Python (Xarray, Plotly, NumPy)                                         |
| **Spatial Scale**  | 1° × 1° global grid                                                    |
| **Analysis**       | 3D surface visualization, depth exploration, color-coded oxygen levels |
| **Output Formats** | Interactive HTML, PNG screenshots                                      |
| **Dependencies**   | Install required packages: `pip install xarray numpy plotly pillow`    |

📦 Package Breakdown:
    xarray → Handle NetCDF multidimensional data.
    numpy → Array calculations and meshgrid creation.
    plotly → Interactive 3D visualization, animation, sliders, colorbars.
    Pillow → Load and handle background images.
    Other packages → Standard Python libraries (os, math) included by default.

🚀 Workflow:
A[🎯 Define Objective] → B[📂 Load WOA23 NetCDF Data] → C[🌐 Convert Lat/Lon to 3D Coordinates] → D[🎨 Generate Surface Colors by Oxygen] → E[📊 Build Frames for Each Depth Layer] → F[⏯️ Add Slider & Play/Pause Animation] → G[🖼️ Add Land Overlay & Background Image] → H[📤 Export Interactive HTML]

📌 Key Parameters:
| Parameter            | Value              | Description                           |
| -------------------- | ------------------ | ------------------------------------- |
| **Projection**       | EPSG:4326          | Geographic CRS                        |
| **Visualization**    | 3D globe           | X/Y/Z coordinates from lat/lon        |
| **Surface Coloring** | `icefire` colormap | Shows oxygen concentration (µmol/kg)  |
| **Missing Data**     | 0 (masked)         | NaNs replaced for rendering           |
| **Depth Slider**     | Interactive        | Explore layers from surface to 1500 m |
| **Land Overlay**     | Green              | Highlights continents                 |
| **Background Image** | Custom PNG         | Enhances Earth realism                |

📦 Outputs:
| Output Type        | Format       | Description                                   |
| ------------------ | ------------ | --------------------------------------------- |
| Interactive Globe  | HTML         | 3D surface with depth slider and animation    |
| Screenshot Preview | PNG          | Static image of globe with color-coded oxygen |
| Code               | Python (.py) | Full script to reproduce visualization        |

⚡ Highlights:
    ✅ Interactive 3D globe for ocean oxygen
    ✅ Depth-wise exploration using sliders and animation
    ✅ Realistic land and background imagery
    ✅ Hover tooltips for latitude, longitude, and oxygen values
    ✅ Color-coded oxygen concentrations with icefire colormap
    ✅ Reproducible Python workflow

📍 Data Source: NOAA WOA23 – Dissolved Oxygen (O₂) NetCDF: https://www.ncei.noaa.gov/access/world-ocean-atlas-2023/

✍️ Author: Subham Roy
    📧 Email: subhamofficwork@gmail.com
    🔗 GitHub: https://github.com/Roysubh
    🔬 ResearchGate: https://www.researchgate.net/profile/Subham-Roy-14
    📚 Google Scholar: https://scholar.google.com/citations?user=bTxDrQgAAAAJ&hl=en
    💬 Telegram: https://t.me/SubhamGeospatialAI
    🆔 ORCID: https://orcid.org/0009-0007-6704-2781

✅ Conclusion: 
    This project demonstrates a full Python geospatial workflow for visualizing global ocean dissolved oxygen:
        Loaded and processed NetCDF climatological data (1965–2022)
        Converted latitude/longitude into 3D globe coordinates
        Generated interactive depth-wise visualizations with sliders and animation
        Added land overlays and realistic background for better interpretation
        Exported interactive HTML for easy exploration
        This framework can support oceanography research, climate studies, marine ecosystem analysis, and interactive data communication.

This interactive 3D visualization helps explore mean dissolved oxygen in global oceans (1965–2022) across multiple depths. It supports ocean health monitoring, climate research, and marine ecosystem studies by highlighting low-oxygen zones and spatial patterns. The tool is also ideal for education and outreach, making complex oceanographic data accessible. Built with Python, Xarray, and Plotly, it provides a reproducible workflow for analysis and visualization.
