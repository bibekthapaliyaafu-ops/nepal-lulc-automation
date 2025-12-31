# Automated LULC Mapping for Nepal Districts

This repository provides an automated Python workflow to generate **print-ready Land Use / Land Cover (LULC) maps** for **any district in Nepal** using:

- ESA WorldCover (10 m resolution)
- SRTM DEM hillshade
- geoBoundaries administrative boundaries
- Google Earth Engine
- Python (GeoPandas, Matplotlib)

The workflow avoids manual GIS steps and is designed for **reproducible research**.

---

## Features

- One-line control to change district name
- Fully automated data access and processing
- Publication-quality map output (300 DPI)
- Reusable for multiple districts
- Suitable for thesis and research projects

---

## Example Output

![Example LULC Map](outputs/example_kailali_lulc.png)

---

## Installation

```bash
pip install -r requirements.txt
