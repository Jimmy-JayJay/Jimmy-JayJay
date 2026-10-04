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

## Web & Client Work

**[Phiri Media](https://www.phirimediagroup.org)**
`Next.js · TypeScript · Tailwind CSS · Sanity · Resend · Framer Motion`
Website for a Malawian marketing and creative agency, built pro bono and live since September 2026. Editorial, design-forward layout with a Sanity-managed blog and portfolio, smooth scrolling and contact email through Resend on the agency's own domain.

**[Pathway Consultancy](https://pathway-consultancy.vercel.app/)**
`Next.js · TypeScript · Tailwind CSS · Framer Motion`
Company website for Pathway Consultancy Ltd.

**[Afrimax Malawi redesign](https://afrimax-rebuild.vercel.app)** *(unofficial concept)*
`Next.js · TypeScript · Tailwind CSS · Sanity · Mapbox GL JS`
A conceptual redesign of an internet provider's website: CMS-driven pricing plans, an interactive coverage map and an accessible, responsive interface.

---

## Stack

<table>
  <tr>
    <td><b>Data & Analysis</b></td>
    <td>
      <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=py%2Csklearn&theme=dark"/><img src="https://skillicons.dev/icons?i=py%2Csklearn&theme=light" height="36" alt="Python, scikit-learn"/></picture>
      <img src="https://img.shields.io/badge/pandas-161B22?style=flat-square&logo=pandas&logoColor=FFFFFF" alt="pandas"/>
      <img src="https://img.shields.io/badge/NumPy-161B22?style=flat-square&logo=numpy&logoColor=4DABCF" alt="NumPy"/>
      <img src="https://img.shields.io/badge/xarray-161B22?style=flat-square" alt="xarray"/>
      <img src="https://img.shields.io/badge/Jupyter-161B22?style=flat-square&logo=jupyter&logoColor=F37626" alt="Jupyter"/>
    </td>
    <td><sub>Forecast pipelines, verification, climate indices</sub></td>
  </tr>
  <tr>
    <td><b>Geospatial</b></td>
    <td>
      <img src="https://img.shields.io/badge/QGIS-161B22?style=flat-square&logo=qgis&logoColor=93B023" alt="QGIS"/>
      <img src="https://img.shields.io/badge/ArcGIS-161B22?style=flat-square" alt="ArcGIS"/>
      <img src="https://img.shields.io/badge/Google%20Earth%20Engine-161B22?style=flat-square&logo=google&logoColor=4285F4" alt="Google Earth Engine"/>
      <img src="https://img.shields.io/badge/PostGIS-161B22?style=flat-square&logo=postgresql&logoColor=5B9BD5" alt="PostGIS"/>
      <img src="https://img.shields.io/badge/GeoPandas-161B22?style=flat-square" alt="GeoPandas"/>
      <img src="https://img.shields.io/badge/Mapbox-161B22?style=flat-square&logo=mapbox&logoColor=FFFFFF" alt="Mapbox"/>
      <img src="https://img.shields.io/badge/HEC--RAS-161B22?style=flat-square" alt="HEC-RAS"/>
    </td>
    <td><sub>Hazard mapping, zonal statistics, drone surveys</sub></td>
  </tr>
  <tr>
    <td><b>Web & Apps</b></td>
    <td>
      <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=nextjs%2Cts%2Creact%2Ctailwind%2Cfastapi&theme=dark"/><img src="https://skillicons.dev/icons?i=nextjs%2Cts%2Creact%2Ctailwind%2Cfastapi&theme=light" height="36" alt="Next.js, TypeScript, React, Tailwind CSS, FastAPI"/></picture>
      <img src="https://img.shields.io/badge/Streamlit-161B22?style=flat-square&logo=streamlit&logoColor=FF4B4B" alt="Streamlit"/>
    </td>
    <td><sub>Decision-support dashboards and client sites</sub></td>
  </tr>
  <tr>
    <td><b>Data & Content</b></td>
    <td>
      <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=postgres%2Csupabase&theme=dark"/><img src="https://skillicons.dev/icons?i=postgres%2Csupabase&theme=light" height="36" alt="PostgreSQL, Supabase"/></picture>
      <img src="https://img.shields.io/badge/Sanity-161B22?style=flat-square&logo=sanity&logoColor=F03E2F" alt="Sanity"/>
    </td>
    <td><sub>Operational data and CMS-managed content</sub></td>
  </tr>
  <tr>
    <td><b>Cloud & Tooling</b></td>
    <td>
      <picture><source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=gcp%2Cdocker%2Cvercel%2Cgit&theme=dark"/><img src="https://skillicons.dev/icons?i=gcp%2Cdocker%2Cvercel%2Cgit&theme=light" height="36" alt="Google Cloud, Docker, Vercel, Git"/></picture>
    </td>
    <td><sub>Deployment, containers, version control</sub></td>
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
