# IL_TBD_Risk

Code and supporting materials for the study:

**Mapping county-level tick-borne disease risk in Illinois by integrating vector abundance, pathogen prevalence, and phenology**

## Overview

This repository contains the R code used to develop species-specific county-level tick-borne disease risk scores for Illinois.

The analysis integrates:

- predicted tick abundance
- tick-borne pathogen prevalence
- reported tick-bite encounters
- human tick-borne disease cases
- seasonal phenology
- temperature and precipitation

The study evaluates three medically important tick species across all 102 Illinois counties:

- *Amblyomma americanum*
- *Dermacentor variabilis*
- *Ixodes scapularis*

Primary ecological risk scores were constructed by combining scaled predicted tick abundance and pathogen prevalence. Sensitivity analyses evaluated alternative abundance-prevalence weighting schemes and the influence of reported tick-bite incidence. Risk scores were validated against human tick-borne disease case counts using negative binomial regression. Monthly phenology was then integrated with county-level ecological risk to generate seasonal risk estimates.


R Shiny application
Interactive monthly tick-borne disease risk maps are available at:
https://abrarhussain.shinyapps.io/interactive_maps

Data availability

Some datasets used in this analysis originate from external surveillance systems and may be subject to data-use or redistribution restrictions. Raw restricted data are therefore not included in this repository.

Citation

Hussain A, Bhowmick S, Mateus-Pinilla N, Smith RL.
Mapping county-level tick-borne disease risk in Illinois by integrating vector abundance, pathogen prevalence, and phenology.
Citation details will be updated following publication.
Authors
- Abrar Hussain
- Suman Bhowmick
- Nohra Mateus-Pinilla
- Rebecca L. Smith
University of Illinois Urbana-Champaign
