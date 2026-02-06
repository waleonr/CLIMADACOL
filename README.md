# CLIMADA - SDGNN 2025 - WALR
 
**Climate Risk Assessment for Colombia using CLIMADA**

## Overview
**CLIMADACOL** is a research-oriented repository that implements a **CLIMADA-based workflow** for assessing **climate-related hazards, exposure, vulnerability, and resilience** in Colombia, with a primary focus on **rural basins and territorial systems**.  

The project is developed within the framework of the **SDG Nexus (climate–land–development)** and supports **reproducible, spatially explicit risk analysis**.

The repository consolidates **data extraction, preprocessing, hazard construction, and exposure modeling** using custom Python code fully compatible with **CLIMADA**.

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/b4ddb6c0-fc44-4865-b91d-865a8a1ec718" />

---

## Objectives
- Implement a **standardized CLIMADA workflow** for climate risk assessment in Colombia  
- Analyze **spatial heterogeneity and multiscale climate variability**  
- Integrate **land-use and territorial exposure** into climate risk models  

---

## Methodological Framework
The project follows the **CLIMADA gold-standard workflow**:


### Key Features
- Climate data ingestion from **raster and NetCDF formats**  
- **Event-based hazard** construction  
- **Spatially explicit exposure** modeling  
- **Modular and reproducible** Python code  

---

## Technologies and Tools
- **Python 3.x**  
- **CLIMADA**  
- xarray, rasterio, geopandas  
- numpy, pandas  
- Jupyter Notebook  

---

## Current Status
- ✔ Data extraction and consolidation  
- ✔ Hazard and exposure construction in CLIMADA  
- ✔ Multiscale spatial analysis  
- 🔄 Ongoing optimization and validation  

---

## Results (2025)

From **August 2025**, the project was structured with the objective of developing a **methodological framework for assessing climate vulnerability and resilience in rural basins of Colombia**, using **CLIMADA as the core analytical framework**. During this initial phase, the study area was delimited (Meta River sub-basin), the SDG Nexus conceptual approach was reviewed, and the technical workflow required by CLIMADA was formally defined, establishing the sequence **Raster/NetCDF → Hazard → Exposures → Impact** as the standard operational pipeline.

Between **September and October 2025**, activities focused on the **extraction, cleaning, and consolidation of climatic and territorial data**, including raster and NetCDF climate variables, as well as spatial layers related to land use and territorial exposure. In parallel, **custom Python code** was developed for data standardization, centroid generation, and event construction, ensuring full compatibility with CLIMADA’s **Hazard** and **Exposures** modules and enabling consistent handling of information across different spatial scales.

During **November 2025**, the work progressed toward the **operational implementation of the CLIMADA workflow**, integrating previously processed inputs into risk objects and evaluating their spatial behavior. At this stage, patterns of **climatic heterogeneity** and their relationship with land-use configurations were analyzed, highlighting the relevance of **multiscale approaches** for adequately representing spatial variability in vulnerability. Iterative refinements to the codebase were carried out to improve **computational performance, transparency, and result traceability**.

Finally, in **December 2025**, the workflow was fully consolidated, establishing a **reproducible CLIMADA-based risk assessment pipeline**. The results demonstrate the potential of CLIMADA to combine **physically grounded hazard modeling with spatial exposure analysis** to generate initial quantitative insights into climate risk, vulnerability, and resilience. This consolidated framework provides robust technical foundations for future extensions, while already delivering relevant inputs for **territorial planning and SDG Nexus–aligned decision-making**.

---

## Use Cases
- Climate risk and vulnerability assessment  
- Territorial and rural planning  
- SDG Nexus–oriented policy support  
- Research and academic applications  

---

## Author
**William Alfonso Leon Rueda**  
Universidad Nacional de Colombia  
*SDG Nexus network – Climate Risk and Spatial Modeling*

---

## License
This project is released under the **MIT License** (or update if different).
