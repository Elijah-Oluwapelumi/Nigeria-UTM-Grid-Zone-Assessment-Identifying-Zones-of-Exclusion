# Nigeria UTM Grid Zone Assessment: Identifying Zones of Exclusion

![GIS](https://img.shields.io/badge/Field-GIS-blue)
![Spatial Analysis](https://img.shields.io/badge/Skill-Spatial%20Analysis-green)
![ArcGIS Pro](https://img.shields.io/badge/Tool-ArcGIS%20Pro-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Focus](https://img.shields.io/badge/Focus-Spatial%20Referencing-red)

---

## Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Study Area](#study-area)
- [Data Sources](#data-sources)
- [Tools and Technologies](#tools-and-technologies)
- [Methodology](#methodology)
- [Results and Insights](#results-and-insights)
- [Spatial Analysis](#spatial-analysis)
- [Interpretation](#interpretation)
- [Conclusion](#conclusion)
- [Recommendations](#recommendations)

---

## Project Overview

GIS is widely misunderstood as a tool only for land mapping or simple location estimation. In reality, GIS answers far more than just **"Where?"**

GIS answers:
- **Where** — spatial location and general awareness
- **When** — temporal change and dynamics
- **How** — the drivers and processes behind spatial patterns
- **What if** — prediction, simulation, and spatial modeling

This project challenges a long-held assumption in Nigeria's spatial referencing system — the belief that:

- The Southwest lies entirely in **UTM Zone 31**
- The East lies entirely in **UTM Zone 32**
- The North lies entirely in **UTM Zone 33**

Rather than accepting this narrative, a spatial assessment was carried out using official shapefiles and UTM grid overlays to test whether Nigerian states fall neatly within single UTM zones — or whether the reality is more complex.

---

## Objectives

- Challenge the simplified UTM zone assumptions applied to Nigerian states
- Identify states that span across two UTM zones using spatial analysis
- Introduce the concept of **Grid Zones of Exclusion** in Nigeria's spatial referencing context
- Demonstrate the real-world implications of grid zone overlap across key sectors

---

## Study Area

Nigeria — Federal Republic of Nigeria, West Africa

- 36 states and the Federal Capital Territory (FCT)
- Spans UTM Zones 31, 32, and 33
- Several states cross UTM zone boundaries, creating areas of dual-zone coverage

<!-- DRAG YOUR UTM GRID ZONE MAP HERE -->

---

## Data Sources

| Data | Source | Purpose |
|------|--------|---------|
| Nigeria Administrative Boundary Shapefile | Official Shapefiles | State boundary delineation |
| UTM Grid Zone Overlay | ArcGIS / Esri | Grid zone identification and overlap analysis |

---

## Tools and Technologies

- ArcGIS Pro (Esri)
- Shapefile Analysis
- UTM Grid Overlay
- Spatial Referencing Techniques

---

## Methodology

### 1. Data Preprocessing
- Loaded official Nigeria administrative boundary shapefiles into ArcGIS Pro
- Imported UTM grid zone polygons covering West Africa
- Ensured all datasets shared a consistent geographic coordinate system

---

### 2. UTM Grid Overlay Analysis

**Aim:**
- To spatially intersect state boundaries with UTM zone polygons across Nigeria.

**Objective:**
- To determine which states fall entirely within one UTM zone and which states overlap across two zones.

---

### 3. Grid Zone of Exclusion Identification

**Aim:**
- To identify and classify states that span across UTM zone boundaries.

**Objective:**
- To map dual-zone states and introduce the concept of Grid Zones of Exclusion — areas where conventional single-zone assumptions break down.

---

### 4. Sector Implication Analysis

**Aim:**
- To assess the practical consequences of ignoring UTM zone overlaps.

**Objective:**
- To connect the spatial findings to real-world implications across defense, governance, engineering, and disaster management sectors.

---

## Results and Insights

### Key Finding — Grid Zones of Exclusion

The spatial assessment revealed that several Nigerian states do not fall neatly into a single UTM zone. These states span across:

| Zone Overlap | Affected Region |
|-------------|----------------|
| Zones 31 & 32 | Western Nigeria |
| Zones 32 & 33 | Central / Northern Nigeria |

What began as a shapefile analysis became **spatial intelligence** — revealing that the simplified zonal narrative widely used in Nigeria is cartographically incomplete.

<!-- DRAG YOUR NIGERIA UTM GRID ZONE ASSESSMENT MAP HERE -->

---

## Spatial Analysis

- **Single-zone states** — Fall cleanly within one UTM zone; standard projection applies
- **Dual-zone states (Zones 31 & 32)** — Straddle the western grid boundary
- **Dual-zone states (Zones 32 & 33)** — Straddle the central-northern grid boundary

The map reveals that grid zone overlap is not an exception — it is a spatial reality affecting multiple states across Nigeria.

---

## Interpretation

The discovery of Grid Zones of Exclusion has serious implications if ignored across several sectors:

**Defense and Security**
- Accurate grid-zone awareness improves navigation, operational coordination, targeting accuracy, and inter-unit communication — especially in cross-zone operations

**Resource Allocation and Governance**
- Proper spatial referencing supports better budgeting, infrastructure planning, boundary coordination, and inter-agency data integration

**Surveying, Engineering and Construction**
- Prevents projection errors, misalignment, and costly mistakes in large-scale projects that cross grid boundaries

**Disaster Management and Emergency Response**
- Enhances accuracy during flood response, humanitarian operations, and security deployments that span multiple zones

---

## Conclusion

This study demonstrates that GIS goes far beyond simple mapping. By applying spatial overlay analysis to Nigeria's UTM grid system, the project exposed a gap between widely accepted assumptions and geographic reality.

The identification of Grid Zones of Exclusion shows that:

- Spatial referencing errors have real consequences across multiple sectors
- Official shapefiles and grid overlays can be used to challenge and correct long-held assumptions
- GIS, when applied rigorously, functions as a tool for **spatial intelligence** — not just spatial display

---

## Recommendations

- Adopt dual-zone awareness in all large-scale mapping and surveying projects that cross state boundaries
- Update spatial referencing guidelines used in Nigerian defense, engineering, and governance operations
- Promote GIS literacy that goes beyond "Where" to encompass temporal, causal, and predictive spatial thinking
- Integrate UTM zone overlap data into national geospatial databases for standardized referencing
