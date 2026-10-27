# Lina María Quintero Fonseca

**Geographer · MSc student in Geomatics, Universidad Nacional de Colombia**
Earth Observation · GeoAI · reproducible geospatial workflows

I work where Earth observation meets land management. For the past three years I have built cartographic and spatial-data products inside Colombia's public sector, at the Instituto Geográfico Agustín Codazzi and the Agencia Nacional de Tierras: thematic map automation, cadastral analysis, geodatabase validation, and the technical documentation that holds all of it together.

In parallel, as an MSc student in Geomatics at the Universidad Nacional de Colombia, I study mangrove and coastal-wetland dynamics with Sentinel-1/2, L-band SAR (NISAR, ALOS-2) and foundation-model embeddings, always under spatial cross-validation.

What I care about most is whether a result holds up. Geospatial work tends to break quietly, so most of what I publish here is about making a workflow reproducible enough that someone else can check it.

---

## What I am working on

**Coastal ecosystem digital twin (MSc thesis).** A GeoAI-based digital twin of the Ciénaga Grande de Santa Marta, a Ramsar site on the Colombian Caribbean: an analysis-ready optical-SAR data cube (Sentinel-1/2, NISAR, ALOS-2) feeding Random Forest and SAM-based segmentation for mangrove extent and flooding dynamics over a 2,042 km² study area, validated against an interpreted 2025 reference sample with spatial block cross-validation.

## Recent

**Foundation models for land cover in the Colombian Orinoquía (WEFE Nexus · AI4LUCA, 2026).** Five foundation-model pipelines (fine-tuned Prithvi-EO-2.0, TerraMind and TerraFM; frozen TESSERA and AlphaEarth embeddings with Random Forest) compared over a common evaluation footprint across 258,000 km² of seasonally flooded savannas, with pre-specified rules, spatial blocks and a held-out test.

---

## Featured

| Project | What it is |
|---|---|
| [**cgsm-mangrove-monitoring**](https://github.com/linaq11/cgsm-mangrove-monitoring) | Multi-language Python/R/Julia pipeline for spatiotemporal mangrove monitoring in the CGSM, 2013–2025. NetCDF datacubes, SamGeo segmentation, bfast change detection, fragmentation metrics, and an [interactive dashboard](https://linaq11.github.io/cgsm-mangrove-monitoring/dashboard.html). |
| [**cgsm-alphaearth-vs-espectral**](https://github.com/linaq11/cgsm-alphaearth-vs-espectral) | AlphaEarth embeddings vs. Sentinel-2 spectral features for mangrove land-cover mapping, with spatial block cross-validation, paired tests and preregistered controls. |
| [**cgsm-radar-banda-L**](https://github.com/linaq11/cgsm-radar-banda-L) | L-band SAR (NISAR, ALOS-2) vs. Sentinel-1 C-band for flooding under mangrove canopy, including dual-pol polarimetry (H/alpha, DpRVI). |

---

## Toolbox

**Earth Observation** Google Earth Engine · Sentinel-1 · Sentinel-2 · Landsat 8/9 · SAR · optical-SAR fusion
**Languages** Python · R · Julia · SQL
**Geospatial** ArcGIS Pro · QGIS · xarray · SamGeo · reproducible pipelines in Docker
**Analysis** Random Forest · spatial statistics (Moran's I, GWR) · time-series and change detection · model evaluation and spatial validation

---

## Reach me

linaq112008@gmail.com
