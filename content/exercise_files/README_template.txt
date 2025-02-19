
# Soil Adsorption Curves and Environmental Soil Data

Code and data for our *Biogeosciences* paper:

**"Evaluating adsorption isotherm models for determining the partitioning of ammonium between soil and soil pore water in environmental soil samples"**

By [Matthew Davis](https://sites.chem.utoronto.ca/murphygroup/content/matthew-davis) (University of Toronto), [Kevin Yan](https://sites.chem.utoronto.ca/murphygroup/content/kevin-yan) (University of Toronto), and [Jennifer Murphy](https://sites.chem.utoronto.ca/murphygroup/pi) (University of Toronto) 

For the latest paper: https://bg.copernicus.org/articles/21/5381/2024/

For link to talk: can add link here

For link to poster: can add link here 

All experimental results can be reproduced using the code and data in this repository. Feel free to contact Jennifer Murphy (corresponding author) by [jen.murphy@utoronto.ca](jen.murphy@utoronto.ca) if you have any questions about our work. 

**Abstract**

Ammonium in soil pore water is thought to participate in bidirectional exchange with the atmosphere; however, common soil nutrient analysis methods determine the bulk quantity of ammonium associated with the soil particles rather than determining the aqueous ammonium concentration. Previous works have applied the Langmuir and Freundlich isotherm equations to ammonium-enriched soils to estimate partitioning, but this may not be representative of conditions in natural, unmanaged soils. In this work, environmental soil samples were collected from green spaces in Toronto and used to evaluate several commonly used adsorption isotherm equations, including the Langmuir, Freundlich, Temkin and Toth equations, to determine their applicability in lightly managed and non-fertilized soils. We then compare ammonia emission potentials (a quantity predicting the propensity of ammonia to volatilize from a liquid reservoir) determined using a conventional high-salt extraction procedure to determine the soil ammonium content to that modelled using the Temkin and Langmuir equations and demonstrate that conventional approaches may overestimate emission potentials from soils by a factor of 5–20.

**Directory**

* `src/` contains source code for the adsorption curves and enviromental soils analysis. This contains Rmd files to generate the models and plots in the paper.
* `data/` contains all the data used in this project. This subdirectory contains a data dictionary. 

**Requirments** 

* R version 4.4.2
* tidyverse, openair, leaflet, openxlsx

**Citation** 

If you find this work helpful, consider citing out paper. 

Davis, M. G., Yan, K., and Murphy, J. G.: Evaluating adsorption isotherm models for determining the partitioning of ammonium between soil and soil pore water in environmental soil samples, Biogeosciences, 21, 5381–5392, https://doi.org/10.5194/bg-21-5381-2024, 2024.

**Acknowledgements**

We thank our colleagues Myrna Simpson and Jenny Oh (University of Toronto) for their helpful discussions. We also thank the University of Toronto ANALEST facility staff for their technical assistance.

This research has been supported by the Natural Science and Engineering Research Council (NSERC) Discovery grant (grant no. RGPIN-2022-05241) and a grants and contributions agreement GCXE19S016 with Environment and Climate Change Canada held by Jennifer Murphy. Matthew Davis held a Walter C. Sumner Memorial Fellowship while conducting this research. An undergraduate summer research award from NSERC supported Kevin Yan during this work.
