# Esha Mohammad Mohaiminul Karim — Academic CV & GIS Portfolio

[![Live Website](https://img.shields.io/badge/Website-EshaKarim.github.io-0F766E?style=flat-square)](https://eshakarim.github.io)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-eshakarim-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/eshakarim)
[![ArcGIS Pro](https://img.shields.io/badge/ArcGIS_Pro-3.x_Toolbox_(.atbx)-1E3A8A?style=flat-square)](./ArcGIS_Script_Tools.atbx)

Welcome to the source repository for **[EshaKarim.github.io](https://eshakarim.github.io)** — the academic curriculum vitae, spatial research portfolio, and open-source geoprocessing tool hub of **Esha Mohammad Mohaiminul Karim**.

---

## About

I am a GIS Specialist and spatial researcher based in British Columbia, Canada, combining technical training in **Geographic Information Systems (BTech, British Columbia Institute of Technology)** with graduate degrees in **Operations Management and Control (MSc, Stockholm University)** and **Finance (MBA & BBA, Institute of Business Administration, University of Dhaka)**.

Currently, I serve with the **Environment Team at the Department of National Defence (CFB Suffield Detachment, Chilliwack, BC)** maintaining enterprise geodatabases, running multi-criteria spatial analysis to delineate Species at Risk (SAR) critical habitat, and building automated Python data pipelines (**AddaxAI**, **Perch 2.0**) for ecological field surveys. Previously, I completed a GIS and planning practicum with **Renewal Development** designing a centralised relational geodatabase and a multi-criteria parcel suitability and land relocation routing model.

---

## Website Structure

The portfolio (`index.html`) is organised into five uncluttered sections with an adaptive **Auto / Light / Dark** browser theme and a dedicated print stylesheet for exporting the formal Academic CV to PDF:

1. **[Overview](https://eshakarim.github.io/#overview)** — Academic profile, core research pillars, and featured thesis/project highlights.
2. **[Academic CV](https://eshakarim.github.io/#cv)** — Full curriculum vitae covering education, graduate theses, work in progress, talks, scholarships, research & industry experience, software, and academic references.
3. **[Theses & Research](https://eshakarim.github.io/#research)** — Abstracts and methodologies for my DND bioacoustic/SAR pipelines, BCIT/Renewal Development MCDA practicum, MBA econometric credit risk thesis, and MSc supply chain governance dissertation.
4. **[ArcGIS Pro Toolbox](https://eshakarim.github.io/#toolbox)** — Direct download and parameter documentation for `ArcGIS_Script_Tools.atbx`.
5. **[Transcripts & Credentials](https://eshakarim.github.io/#credentials)** — Official course-by-course records across 4 university degrees alongside verified Esri MOOCs and Coursera professional certificates.

---

## Included ArcGIS Pro Toolbox (`ArcGIS_Script_Tools.atbx`)

This repository hosts **[`ArcGIS_Script_Tools.atbx`](./ArcGIS_Script_Tools.atbx)**, a custom ArcGIS Pro 3.x toolbox written in Python (`arcpy`) containing five script tools with custom `ToolValidator` classes:

| Tool Name | Script Folder | Description |
| :--- | :--- | :--- |
| **`StringSearcher`** | `StringSearcher.tool` | Scans multiple text attributes across feature classes or tables using case-insensitive substring or regular expression (`re`) matching via `arcpy.da.SearchCursor` for attribute QA/QC auditing. |
| **`SearchAndExtract`** | `SearchAndExtract.tool` | Builds DBMS-agnostic SQL `WHERE` clauses (`arcpy.AddFieldDelimiters`) across selected string fields and exports matching records to a new geodatabase feature class (`arcpy.conversion.ExportFeatures`). |
| **`OSMDownloader`** | `OSMDOwnloader.tool` | Downloads OpenStreetMap vector features (highways, buildings, landuse, waterways, amenities) within a study area extent or polygon layer and reprojects them into a target coordinate reference system. |
| **`BasemapLoader`** | `BasemapLoader.tool` | Automates cartographic setup in ArcGIS Pro (`arcpy.mp.ArcGISProject`) by loading standard provincial/federal reference layers (DataBC, GeoBC, CanVec) and synchronising map frame spatial references. |
| **`BatchConvertPytToAtbx`** | `BatchConvertPytToAtbx.tool` | Batch-migrates legacy Python Toolboxes (`.pyt`) in a workspace directory into modern ArcGIS Pro `.atbx` toolboxes while preserving execution and validation scripts. |

### Quick Installation in ArcGIS Pro
1. Download **[`ArcGIS_Script_Tools.atbx`](./ArcGIS_Script_Tools.atbx)** into your project folder.
2. Open **ArcGIS Pro** → **Catalog Pane** → right-click **Toolboxes** → select **Add Toolbox**.
3. Browse to `ArcGIS_Script_Tools.atbx` and click **OK** to run any of the five script tools in the Geoprocessing pane or ModelBuilder.

---

## Repository Contents

```text
EshaKarim.github.io/
├── index.html                  # 5-page academic portfolio & printable Academic CV
├── ArcGIS_Script_Tools.atbx    # Custom 5-tool ArcGIS Pro geoprocessing toolbox
├── Esha_Karim_Resume.pdf       # Downloadable 2-page industry resume (PDF)
└── README.md                   # Repository documentation
```

---

## Contact

* **Name:** Esha Mohammad Mohaiminul Karim
* **Location:** Maple Ridge, British Columbia, Canada
* **Email:** [ekarim4@my.bcit.ca](mailto:ekarim4@my.bcit.ca)
* **LinkedIn:** [linkedin.com/in/eshakarim](https://www.linkedin.com/in/eshakarim)
* **Portfolio:** [https://eshakarim.github.io](https://eshakarim.github.io)