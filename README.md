# <ins>Drought Analysis in Mandera County</ins>

This project focuses on analyzing drought conditions in Mandera County, Kenya, using the **Standardized Precipitation Evapotranspiration Index (SPEI)**. The SPEI is a comprehensive drought index that considers both precipitation and potential evapotranspiration (PET), making it more sensitive to climate change impacts than indices relying solely on precipitation.

The notebook outlines the theoretical background of SPEI, including its key features, calculation steps (water balance, accumulation, standardization, and interpretation), and applications in remote sensing, such as drought monitoring, agricultural drought assessment, climate change studies, and early warning systems.

The practical part of the project utilizes the **Google Earth Engine (EE)** platform. It first sets up the EE environment and then subsets the analysis to the Area of Interest (AOI), which is **Mandera County in Kenya**, using **FAO's** administrative boundary data.

The core analysis involves:

1. Time Series Analysis: Calculating and visualizing the median 24-month SPEI over Mandera County for the period of 2021 to 2023. This provides an overview of the drought conditions over time.
   
2. Spatial Mapping: Generating maps of the 12-month SPEI for the years 2021 and 2022 to visualize the spatial distribution of drought severity within Mandera County. A split-panel map is created to facilitate a direct comparison of drought conditions between these two years.

In summary, this project leverages Earth Engine and the SPEI to assess and visualize drought conditions in Mandera County, Kenya, over a recent period, providing insights into the temporal and spatial patterns of drought in the region.
