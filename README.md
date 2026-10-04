<h1 align="center">Jimmy Edward Matewere</h1>

<p align="center">
  <b>Climate Data Scientist &nbsp;·&nbsp; Geospatial Engineer &nbsp;·&nbsp; Founding CTO, Ascend Spatial Labs</b>
</p>

<p align="center">
  BSc Meteorology & Climate Science, MUST 2025 &nbsp;·&nbsp; Blantyre, Malawi
</p>

<p align="center">
  <a href="https://jimmy-matewere.vercel.app/">Portfolio</a> &nbsp;·&nbsp;
  <a href="https://linkedin.com/in/jimmy-matewere">LinkedIn</a> &nbsp;·&nbsp;
  <a href="mailto:jimmymatewere@gmail.com">jimmymatewere@gmail.com</a>
</p>

---

I build climate and geospatial data systems end to end: from raw forecasts, station records and field surveys to the pipelines, analysis and decision-support tools people use. My background is meteorology and climate science, and I care about one rule above the rest: a tool should never show a number it did not compute from data it actually received.

**Now**

- **Climate Data Analyst (graduate intern), DCCMS**, Department of Climate Change and Meteorological Services, Engineering & Communication: forecast pipelines and operational meteorological tooling.
- **CCM Data Analyst, Ripple Africa**: data quality, indicator definitions and verification evidence for the Changu Changu Moto cookstove carbon programme.
- **Founding CTO, Ascend Spatial Labs**: geospatial intelligence and climate risk services.

---

## Projects

**Malawi Impact-Based Forecasting Dashboard** *(DCCMS, internal)*
`Next.js · TypeScript · Mapbox GL JS · Docker · WRF`
Turns the DCCMS WRF 4 km forecast into an alert tier (No Action, Be Aware, Be Prepared, Take Action) for each of Malawi's 32 jurisdictions, weighted by population and household vulnerability. National map, district profiles, flood and drought pages and a data portal for forecasters, disaster management and district staff. Designed around one rule: never present a value that was not computed from data actually received, so a missing forecast reads as missing rather than as calm.

**Nimbus Forecast** *(DCCMS, internal)*
`Next.js · TypeScript · PostgreSQL · Neon`
Operational forecast platform for the National Meteorological Centre. Daily forecasts from four global models (YR, ECMWF, GFS, ICON) plus DCCMS's COSMO regional model for 99 stations, with concurrent ingestion guarded by locks and scheduled runs. It replaced a manual routine of up to 99 browser tabs for the weekly rainfall bulletin, became part of the Monday morning NMC workflow, and led to a commission for an institutional platform.

**[Climate Risk Scoring Dashboard, Malawi](https://malawiclimaterisk.vercel.app)**
`Python · Next.js · Mapbox GL JS · IPCC AR5`
District climate risk index for all 28 districts on the IPCC AR5 hazard, exposure and vulnerability framing. Hazard from NASA POWER daily data (2020 to 2024, about 50,000 district-day records): rainfall variability, SPI-based drought frequency, heavy rainfall and heat extremes. Choropleth with 3D terrain and radar profiles. Exposure and vulnerability layers are being upgraded from estimates to district survey data.

**[WasteWatch, Waste Management Decision Support](https://wastewatch-dashboard.vercel.app/)**
`Python · FastAPI · Next.js · DBSCAN · GCP Cloud Run`
Decision support for Blantyre City Council, built by a six-person team (I led the dashboard and backend). 333 surveyed illegal dumpsites scored 0 to 100 across health, environmental and volume factors, and DBSCAN clustering to recommend skip locations. FastAPI backend on Cloud Run, Next.js frontend.

**[Ascend Spatial Labs Platform](https://ascendspatiallabs.vercel.app)**
`Next.js · Mapbox · Clerk · Sanity`
Company site and client portal for a geospatial intelligence startup: Clerk authentication synced to Sanity, webhook handling with retries, soft deletes and project visibility states.

**Evaluating Climate Adaptation Finance in Malawi** *(BSc thesis)*
`Python · Excel · QGIS · MAXQDA`
Structure, allocation and governance of adaptation finance, 2018 to 2023, from the government's climate finance information system. About MWK 16 billion budgeted across the 17 projects in the period, all grant-funded; forestry and agriculture led the technologies funded; 24 of 28 districts had at least one project; only 3 of 48 projects named an implementor, the core transparency finding.

---

## Stack

**Data & Analysis**

<p>
  <a href="https://www.python.org/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" title="Python"/></a>
  <a href="https://numpy.org/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="40" title="NumPy"/></a>
  <a href="https://pandas.pydata.org/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="40" title="Pandas"/></a>
  <a href="https://scikit-learn.org/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/scikitlearn/scikitlearn-original.svg" width="40" title="Scikit-learn"/></a>
  <a href="https://www.postgresql.org/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="40" title="PostgreSQL"/></a>
  <a href="https://jupyter.org/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" width="40" title="Jupyter"/></a>
</p>

**Geospatial**

<p>
  <img src="https://img.shields.io/badge/QGIS-3C7A3A?style=for-the-badge&logo=qgis&logoColor=white" alt="QGIS"/>
  <img src="https://img.shields.io/badge/ArcGIS-2C7AC3?style=for-the-badge&logo=arcgis&logoColor=white" alt="ArcGIS"/>
  <img src="https://img.shields.io/badge/Google%20Earth%20Engine-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="GEE"/>
  <img src="https://img.shields.io/badge/Mapbox-000000?style=for-the-badge&logo=mapbox&logoColor=white" alt="Mapbox"/>
  <img src="https://img.shields.io/badge/HEC--RAS-555555?style=for-the-badge" alt="HEC-RAS"/>
</p>

**Web & Platform**

<p>
  <a href="https://nextjs.org/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" width="40" title="Next.js"/></a>
  <a href="https://www.typescriptlang.org/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" width="40" title="TypeScript"/></a>
  <a href="https://fastapi.tiangolo.com/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" width="40" title="FastAPI"/></a>
  <a href="https://www.docker.com/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40" title="Docker"/></a>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
</p>

**Cloud**

<p>
  <a href="https://cloud.google.com/"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" width="40" title="Google Cloud"/></a>
</p>

---

## Certifications

DataCamp Certified Data Scientist, Data Analyst & Data Engineer, 2025 to 2026 · Femanalytica Scholarship  
CDDT-2, African Drone and Data Academy, 2026 · ArcGIS, Pix4Dmapper, HEC-RAS, BVLOS  
CDDT-1, African Drone and Data Academy, 2025 · EASA A1/A3 Remote Pilot Licence (EU airspace)

---

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jimmy-JayJay&layout=compact&theme=radical" alt="Top Languages"/>
</p>
