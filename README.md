![Cool GIF](https://user-content.gitlab-static.net/2de13ca73e55b95a66dfe6913ad7136f26348ef1/68747470733a2f2f6769746875622e636f6d2f416e6d6f6c2d426172616e77616c2f436f6f6c2d474946732d466f722d4769744875622f6173736574732f37343033383139302f38303732383832302d653036622d346639362d396339652d396466343666306363306135)

<br/>

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

<table>
  <tr>
    <td><b>Data & Analysis</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
      <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"/>
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
      <img src="https://img.shields.io/badge/xarray-1F6F8B?style=flat-square" alt="xarray"/>
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
      <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter"/>
    </td>
  </tr>
  <tr>
    <td><b>Geospatial</b></td>
    <td>
      <img src="https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white" alt="QGIS"/>
      <img src="https://img.shields.io/badge/ArcGIS-2C7AC3?style=flat-square" alt="ArcGIS"/>
      <img src="https://img.shields.io/badge/Google%20Earth%20Engine-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Earth Engine"/>
      <img src="https://img.shields.io/badge/PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white" alt="PostGIS"/>
      <img src="https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square" alt="GeoPandas"/>
      <img src="https://img.shields.io/badge/Mapbox-000000?style=flat-square&logo=mapbox&logoColor=white" alt="Mapbox"/>
      <img src="https://img.shields.io/badge/HEC--RAS-555555?style=flat-square" alt="HEC-RAS"/>
    </td>
  </tr>
  <tr>
    <td><b>Web & Apps</b></td>
    <td>
      <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=white" alt="React"/>
      <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"/>
      <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit"/>
    </td>
  </tr>
  <tr>
    <td><b>Data & Content</b></td>
    <td>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
      <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase"/>
      <img src="https://img.shields.io/badge/Sanity-F03E2F?style=flat-square&logo=sanity&logoColor=white" alt="Sanity"/>
    </td>
  </tr>
  <tr>
    <td><b>Cloud & Tooling</b></td>
    <td>
      <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="Google Cloud"/>
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
      <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel"/>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git"/>
    </td>
  </tr>
</table>

---

## Certifications

DataCamp Certified Data Scientist, Data Analyst & Data Engineer, 2025 to 2026 · Femanalytica Scholarship  
CDDT-2, African Drone and Data Academy, 2026 · ArcGIS, Pix4Dmapper, HEC-RAS, BVLOS  
CDDT-1, African Drone and Data Academy, 2025 · EASA A1/A3 Remote Pilot Licence (EU airspace)

---

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jimmy-JayJay&layout=compact&theme=radical" alt="Top Languages"/>
</p>
