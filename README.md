# DaYu-GCP
DaYu-GCP: All-day Global Cloud Physical Properties Dataset with 0.07° Resolution Retrieved from Geostationary Satellite Imagers (2000-2022)

## Citation
The paper was published in Earth System Science Data.

DOI: https://doi.org/10.5194/essd-18-1813-2026

GB/T 7714 Format Citation: 

Zhao L, Zhang F, Zhao Z, et al. All-day global cloud physical properties products with 0.07° resolution retrieved from geostationary satellite imagers covering the period from 2000 to 2022 [J]. Earth System Science Data, 2026, 18(3): 1813-1832.

## Short summary
The DaYu-GCP is retrieved using infrared brightness temperatures at 6.7 µm and 11 µm. It provides a long-term, all-day global cloud physical properties product with a spatial resolution of 0.07° and a temporal resolution of 3 hours, spanning from 2000 to 2022. The dataset covers the region from -70° to 70° in latitude and from -180° to 180° in longitude. The dataset include four variables: cloud phase (CLP), cloud top height (CTH), cloud optical thickness (COT), and cloud effective radius (CER).

## Detailed information:

3h temporal resolution is UTC time 0, 3, 6, 9, 12, 15, 18, and 21 hours daily.

CLP: 0 clear, 1 liquid, 2 ice; missing: NaN.

CTH: CTH in km; missing: NaN; range [0, 18].

COT: COT in unitless; missing: NaN; range [0, 150].

CER: CER in µm; missing: NaN; range [0, 60].
 
## Data storage structure
The file names and directory structure are organized in the following format:

```

{year}.nc/{year}{month}{day}{hour}.nc

```

 

## change list:
V1: init commit.

V2: rename DaYu-GCP.

V3: add citation information.
