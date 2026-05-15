# annual_seismic_energy_timeseries_of_the_indian_tectonic_plate

## Overview

This project presents a complete seismological workflow for:

- Spatial seismicity visualization
- Seismic energy estimation
- Annual seismic energy release analysis
- Indian tectonic plate seismicity assessment
- Scientific geospatial earthquake mapping

The workflow integrates empirical seismological equations with geospatial visualization techniques to analyze earthquake activity over the Indian tectonic plate region.

The methodology is based on:

- Hanks and Kanamori (1979)
- Choy and Boatwright (1995)

Applications include:

- Seismic hazard assessment
- Seismotectonic investigations
- Earthquake energy analysis
- Machine learning-based seismic forecasting
- Regional tectonic studies

---

# Project Workflow

## Step 1 — Load Earthquake Catalogue

The earthquake catalogue is imported using Pandas for preprocessing and analysis.

## Step 2 — Spatial Seismicity Mapping

Earthquake epicenters are visualized over the Indian tectonic plate region using Basemap.

Features include:

- Coastlines
- Country boundaries
- Latitude/longitude grids
- Magnitude-based marker scaling
- Publication-quality visualization

## Step 3 — Seismic Energy Estimation

Seismic moment and seismic energy are estimated using empirical equations.

### Equation 1 — Seismic Moment

\[
\log_{10}(M_0) = 1.5(M_w + 6.0)
\]

### Equation 2 — Seismic Energy

\[
E_s = 1.6 \times 10^{-5}(M_0)
\]

Where:

- \(M_0\) = Seismic Moment
- \(M_w\) = Moment Magnitude
- \(E_s\) = Seismic Energy

## Step 4 — Annual Seismic Energy Analysis

Annual seismic energy release is computed and visualized using logarithmic scaling.

---

# Spatial Seismicity Visualization

<img width="6157" height="6128" alt="indian_plate_seismicity_map" src="https://github.com/user-attachments/assets/0c7013d1-a0df-4e31-a95f-f98cb82010cf" />


*Spatial distribution of earthquake epicenters over the Indian tectonic plate region.*

---

# Annual Seismic Energy Release

<img width="6086" height="2717" alt="Seismic_Energy_Graph" src="https://github.com/user-attachments/assets/7478d655-1e62-44e4-b6c5-339ce286d23e" />


*Annual seismic energy release estimated from earthquake magnitude data.*

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Basemap
- Jupyter Notebook

---

# Applications

This workflow can be applied in:

- Earthquake forecasting
- Seismic hazard analysis
- Seismotectonic studies
- Spatial seismicity investigations
- Machine learning applications in seismology
- Earthquake energy release assessment

---

# Research Publications Using Similar Methodology

1. Yarramsetty, B. B., & Baladhandapani, K. (2026). *Machine Learning Models for Seismic Energy Forecasting and Spatial Correlation Analysis for the Himalayan and Indo-Burmese Regions*. Natural Hazards Review, 27(3). https://doi.org/10.1061/NHREFO.NHENG-2647

2. Yarramsetty, B. B., & Baladhandapani, K. (2026). *Data-driven prediction of global annual seismic energy using machine learning models*. Journal of Earth System Science, 135(2), 60. https://doi.org/10.1007/s12040-026-02788-2

3. Bala Balaji, Y., Hema Sundara, R. V., & Kavitha, B. (2025). *Spatial Variation of Seismic Energy Release of Himachal Pradesh*. Disaster Advances, 3(19), 15. https://doi.org/10.25303/193da15023

4. Yarramsetty, B. B., & Kavitha, B. (2025). *Statistical Study on Seismicity of the Indian Tectonic Plate Interactions*. Disaster Advances, 10(18), 12. https://doi.org/10.25303/1810da012021

---

# References

1. Hanks, T. C., & Kanamori, H. (1979). *A moment magnitude scale*. Journal of Geophysical Research, 84(B5), 2348–2350.

2. Choy, G. L., & Boatwright, J. (1995). *Global patterns of radiated seismic energy and apparent stress*. Journal of Geophysical Research, 100(B9), 18205–18228.

---

# Future Improvements

Potential future extensions include:

- Deep learning-based seismic forecasting
- Spatiotemporal seismic clustering
- GIS shapefile integration
- Interactive seismicity visualization
- Real-time earthquake monitoring pipelines
- Seismic energy heatmap generation

---

# Author

**Bala Balaji Yarramsetty**  
Department of Civil Engineering  
National Institute of Technology Warangal  
India
