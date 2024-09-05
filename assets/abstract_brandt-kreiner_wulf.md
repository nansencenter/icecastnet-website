---
layout: minimal
---

## Arctic sea Ice observations from satellite SAR and PMW data using deep learning
### *Tore Wulf*, Jørgen Buus-Hinkler, Mads Hvid Ribergaard, Till Soya Rasmussen, Suman Singha and *Matilde Brandt Kreiner*, Danish Meteorological Institute (DMI)

The Arctic’s unprecedented transformation due to anthropogenic warming necessitates close monitoring of sea ice to understand and address climate change impacts. 
As the sea ice retreats and becomes thinner, increased human activity in the region emphasizes the urgent need for detailed, near real-time sea ice information as well as improved sea ice forecasts for maritime safety and planning. 
Current methods of Arctic sea ice retrieval relies on passive microwave (PMW) sensors, which offer global coverage but struggle to capture fine-scale features and changes in the sea ice. 

Synthetic Aperture Radar (SAR) imagery, with its high spatial resolution and independence from sunlight and clouds, is pivotal in the year-round mapping of Arctic sea ice conditions that is carried out manually at the national ice services. 
Yet, automating SAR-based sea ice retrieval remains challenging due to inherent ambiguities in the observations. 
Recent advances in deep learning vision methodologies show promise in SAR-based sea ice retrievals. 
A robust pan-Arctic SAR-based sea ice retrieval system can serve maritime sectors, national ice services, and local communities by providing timely, high-resolution sea ice information. 
Furthermore, SAR-based sea ice retrievals can be assimilated in numerical ocean and sea ice models, improving sea ice forecasts crucial for local communities and maritime sectors.

Here we present a comprehensive deep learning approach - we call it ASIP (Automated Sea Ice Products) - we use to retrieve high-resolution sea ice concentration, stage-of-development, floe size information, and calibrated uncertainties from Sentinel-1 SAR and AMSR-2 passive microwave (PMW) observations at a pan-Arctic scale for all seasons. 
The DMI-ASIP processing system outputs level-2 sea ice information products in near-real time from S-1 dual-polarized EW and IW mode imagery acquired over the Arctic and Antarctic. 
A daily Antarctic level-3 sea ice concentration product mosaic based on our methodology is operationally provided through the Copernicus Marine Service portfolio since March 2022 and daily pan-Arctic level-3 and -4 sea ice products (the latter from combination with a OSI SAF sea ice concentration product) will be delivered in Copernicus Marine Service portfolio from November 2024. 
Also for the November release, we will provide daily pan-Arctic reprocessed products for the entire Sentinel-1 era, which began with the launch of Sentinel-1A in 2014.

We will present results for the impact of assimilation DMI-ASIP level-2 SAR-based sea ice concentration, and OSI SAF level-2 PMW-based sea ice concentration, in the DMI HYCOM-CICE coupled ocean-sea-ice forecasting system for the pan-Arctic region.

[back to the Workshop page](https://nansencenter.github.io/superice-nersc/workshop/)
