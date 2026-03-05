# ecological-quality-of-snowmaking-reservoirs

R scripts used for the analysis of snowmaking reservoirs ecology and design in the Alps linked to the published article : https://link.springer.com/article/10.1007/s00027-024-01136-0



This repository contains the scripts and processed datasets used to produce the analyses, tables and figures presented in:



Gerfand et al. (2025).  

\*Ecological quality of snowmaking reservoirs in the Alps and management perspectives\*  

Aquatic Sciences.  

https://link.springer.com/article/10.1007/s00027-024-01136-0



\## Repository structure



The repository is organised into two main folders:



\### Data



Contains the datasets used for the analyses.



Data/

│

├── csv for R/

│   Processed datasets used directly by the R scripts to reproduce the

│   statistical analyses and figures presented in the article.

│

└── Freshwater habitats/

&nbsp;   Additional datasets related to freshwater habitats in the study area,

&nbsp;   including:

&nbsp;   

&nbsp;   • distances between high-altitude reservoirs and nearby water bodies or streams  

&nbsp;   • inventory of water bodies identified by GIS between 1000 and 2700 m

&nbsp;     above sea level within the study area



Note: Raw data are not provided in this repository.



\### Script



This folder contains six R scripts used to reproduce the analyses presented in the article.



Script/

│

├── bg\_1\_table\_reservoirs\_description

├── bg\_2\_analyses\_136 reservoirs description

├── bg\_3\_Fig\_number of reservoirs per year and volume

├── bg\_4\_analyses\_28 reservoirs description

├── bg\_5\_analyses\_28 reservoirs biodiversity surveys

└── bg\_6\_Fig \& analyses\_Lakes \& 28 reservoirs water quality



These scripts generate:



\- descriptive statistics of snowmaking reservoirs

\- analyses of biodiversity occurrence and mortality

\- comparisons of water physicochemistry between snowmaking réservoirs and mountain lakes

\- analyses of reservoir design and uses

\- figures and tables presented in the manuscript



The scripts use the datasets contained in the folder:



Data/csv for R/



\## Reproducibility



All analyses were performed using \*\*R\*\*.



To reproduce the results:



1\. Clone or download this repository

2\. Open the R scripts in the `Script` folder

3\. Ensure the working directory corresponds to the root of the repository

4\. Run the scripts sequentially



The scripts will automatically load the datasets located in: Data/csv for R/



\## Data availability



Only processed datasets necessary to reproduce the analyses are provided here.



Raw datasets are not publicly available.



Additional spatial datasets related to freshwater habitats are provided in the folder: Data/Freshwater habitats/





\## Contact



For questions regarding the data or scripts, please contact the authors of the article.



