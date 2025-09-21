# PM_SHRI_SCHOOLS_DATA_VISUALIZATION
Interactive map of 836 schools across Bihar, built with Python, Pandas, GeoPandas, and Folium. Features crisp district boundaries, color-coded fills, PM SHRI logo markers, and hover tooltips. Published on the official Ministry of Education – PM SHRI Portal.
# Bihar Schools – Interactive Map (PM SHRI)

An interactive map of 800+ schools in Bihar with district borders, labels, per-district colors, and custom PM SHRI logo markers.

## Live Demo
Once GitHub Pages is enabled (see below), your map will be here:
https://<your-username>.github.io/<your-repo>/output/bihar_schools_filled_districts_labels_legend.html

## Data
- Schools: `data/school_dataset_new.xlsx` (cleaned from raw 836 rows)
- District boundaries: GADM – Global Administrative Areas (https://gadm.org/), field `NAME_2` used for district names.

## How to Run (locally)
```bash
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
# open notebook/bihar_map.ipynb in Jupyter or run your script version
