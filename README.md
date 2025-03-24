# Physicist --> Data Scientist
Result-oriented Data Scientist with a PhD in Ocean Physics and an MSc in Statistical Physics. Expert in Earth Physical models and Environmental Data Science at Fondazione Centro Euro-Mediterraneo sui Cambiamenti Climatici. Skilled in Data Viz (Seaborn, SQL, PowerBI).



## Education
- Ph.D., Ocean Physics | University of Bologna (_July 2024_)
- M.S., Physics | Sapienza University of Rome (_May 2020_)
- B.S., Physics | Sapienza University of Rome (_March 2017_)

  

## Work Experience
**PostDoc Data Scientist, CMCC Foundation (_February 2024 - February 2025_)**
- Analyzed 1+Tb ocean data, developing risk KPIs, automating data processing and enabling timely stakeholder reporting.
- Applied ML techniques to detect and identify over 90 distinct oil pollutants.
- Validated pollution tracking model, managed deviations and data integrity, implemented corrective actions, produced datasheets.
- Conducted extensive 3D simulations (10000+) of ocean tracers, optimizing key physical and numerical parameters to fit on-site sensors and satellite data from Copernicus Marine Service.


**PhD, CMCC Foundation (_November 2020 - January 2024_)**
- Trained a software engineering team for new ocean pollution tracking model development.
- Engineered Python-based data pipelines for ocean pollution analysis, automating data extraction, aggregation, preprocessing, and model output processing. 
- Effectively communicated complex technical findings to diverse audiences, from academic experts to external stakeholders.


  

## Projects
### Ocean pollution tracking

Developed a two-stage model for **tracking deep oil spills** in the ocean, as from accidental pipelines ruptures and sinking tanks, using **Python**. Key physical processes, such as oil-water entrainment and reaching of a deep neutral buoyancy level, are fully represented with a [near-field](https://github.com/GiuliaGronchi/NearParcels) model. This is coupled to a [far-field](https://github.com/GiuliaGronchi/FarParcels) single-parcels model, where advection-diffusion and size-dependent buoyancy are modeled using **OceanParcels**. Key model parameters are tuned for optimal fit with data from historical oil spill cases.

![Images](/assets/img/deep.png)

See [EGU24](https://meetingorganizer.copernicus.org/EGU24/EGU24-9808.html) and [EGU22](https://meetingorganizer.copernicus.org/EGU22/EGU22-7607.html)



### Active Bacteria 

Developed a new model for a **microscale thermal machine** based upon active particle statistical physics. The model is a complex stochastic process with colored noise that reproduces the persistence of motion of self-propelled particles, such as microswimmer (bacteria etc.) or other active particles. To extract work in a model of this kind we proposed to modulate in time the parameters of the bath, as it happens in a kind of Stirling engine. Physical processes were simulated in **C**. 

![Images](/assets/img/thermal_engine.png)

See [G. Gronchi and A. Puglisi, Optimization of an active heat engine, Physical Review E, DOI:https://doi.org/10.1103/PhysRevE.103.052134, 2021](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.103.052134)


### GenDip dataset 
[GenDip dataset](https://www.gu.se/en/gendip/the-gendip-dataset-on-gender-and-diplomatic-representation)

Used **SQL** querying to get insights from the GenDip Dataset on Gender and Diplomatic Representation from University of Gothenburg.
The GenDip dataset maps the man and woman presence in different kinds of ambassador postings between the years 1968-2021. This [SQL analysis](https://github.com/GiuliaGronchi/SQL-GenDip) identifies
patterns in time and space of gender gaps in diplomacy.

![Images](/assets/img/gender_gap.png)

### LST for suspended particles
[Laser Transmission Spectroscopy](https://ieeexplore.ieee.org/document/9359477)

Laser Transmission Spectroscopy (LTS) is a cutting-edge technique for characterization of **biological nanoparticles**. It is often used to measure dimensions and absolute concentration of exosomes, bacteria, and cells in vivo suspensions and is a promising new method for diagnostics. During [this project](https://github.com/GiuliaGronchi/LTS) at Sapienza University, we designed a new experimental setup with a tunable wavelength laser and developed a **Python** software tool for analyzing the transmitted data.

![Images](/assets/img/laser.png)


