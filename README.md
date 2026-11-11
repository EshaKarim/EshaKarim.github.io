# Esha Karim — GIS Portfolio & Resume

Welcome to the source repository for [**EshaKarim.github.io**](https://eshakarim.github.io) — the GIS portfolio, resume, and ArcGIS Pro script tool repository of **Esha Karim**.

## Profile

GIS practitioner currently maintaining enterprise geodatabases, running spatial analysis and automating GIS workflows with FME, Python (ArcPy) and ModelBuilder. Completed a GIS practicum building a relational geodatabase and utility corridor analysis for a housing developer, turning the sponsor's business requirements into a database design. Experienced in QA/QC of spatial data from multiple sources, web GIS applications, map production, Esri Field Maps, and CAD-to-GIS coursework, with a prior career in the finance sector that built project leadership, reporting and customer service, business analysis and client communication skills.

## Website Structure

The portfolio (`index.html`) is organised into five clean sections with an adaptive **Auto / Light / Dark** browser theme:

1. [**Overview**](https://eshakarim.github.io/#overview) — Profile summary, core technical skills, and direct links to download the PDF resume and `.atbx` toolbox.
2. [**Experience & Skills**](https://eshakarim.github.io/#experience) — GIS roles at the Department of National Defence (Environment Team) and Renewal Development (Practicum), prior finance and Business Intelligence/MIS roles at TD Canada Trust and Eastern Bank Limited, and technical skills.
3. [**ArcGIS Pro Toolbox**](https://eshakarim.github.io/#toolbox) — Direct download and descriptions for `ArcGIS_Script_Tools.atbx`.
4. [**Education & Coursework**](https://eshakarim.github.io/#education) — Degree credentials and expandable transcript course lists for BCIT (BTech in GIS), Stockholm University (MSc in Management), and the Institute of Business Administration, University of Dhaka (MBA & BBA in Finance).
5. [**Certifications**](https://eshakarim.github.io/#certifications) — Completed Esri MOOCs and Coursera certificates with verification links.

## Included ArcGIS Pro Toolbox (`ArcGIS_Script_Tools.atbx`)

This repository hosts [**`ArcGIS_Script_Tools.atbx`**](./ArcGIS_Script_Tools.atbx), a custom ArcGIS Pro toolbox containing five Python (`arcpy`) script tools:

| Tool Name | Script Folder | Description |
| ----- | ----- | ----- |
| **`StringSearcher`** | `StringSearcher.tool` | Searches one or more text fields in a feature class or table for a substring or regular expression pattern and logs matching ObjectIDs and field values. |
| **`SearchAndExtract`** | `SearchAndExtract.tool` | Queries selected text fields in an input feature layer for a target string and exports matching features to a new geodatabase feature class. |
| **`OSMDownloader`** | `OSMDOwnloader.tool` | Downloads OpenStreetMap vector features for a specified area of interest and converts them into geodatabase feature classes. |
| **`BasemapLoader`** | `BasemapLoader.tool` | Automates loading basemaps and reference layers into an active ArcGIS Pro map project (`arcpy.mp.ArcGISProject`). |
| **`BatchConvertPytToAtbx`** | `BatchConvertPytToAtbx.tool` | Batch-converts Python Toolboxes (`.pyt`) in a workspace directory into ArcGIS Pro (`.atbx`) toolboxes. |

### Quick Installation in ArcGIS Pro

1. Download [**`ArcGIS_Script_Tools.atbx`**](./ArcGIS_Script_Tools.atbx) into your project folder.
2. Open **ArcGIS Pro** → **Catalog Pane** → right-click **Toolboxes** → select **Add Toolbox**.
3. Browse to `ArcGIS_Script_Tools.atbx` and click **OK**.

## Repository Contents

\`\`\`
EshaKarim.github.io/
├── index.html                  # 5-page GIS portfolio & resume website
├── ArcGIS_Script_Tools.atbx    # Custom 5-tool ArcGIS Pro toolbox
├── Esha_Karim_Resume.pdf       # Downloadable 2-page resume (PDF)
└── README.md                   # Repository documentation
\`\`\`

## Contact Esha

* **Name:** Esha Karim
* **Location:** British Columbia, Canada
* **Email:** [ekarim4@my.bcit.ca](mailto:ekarim4@my.bcit.ca)
* **LinkedIn:** [linkedin.com/in/eshakarim](https://www.linkedin.com/in/eshakarim)
* **Portfolio:** <https://eshakarim.github.io>