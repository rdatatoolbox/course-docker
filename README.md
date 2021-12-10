## :mortar_board: Docker for R users

[![License: CC
BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgreen.svg)](https://choosealicense.com/licenses/cc-by-4.0/)


Code used to create the online presentation **Docker for R Users**. This course
is part of the workshop :mortar_board: 
**_Data Toolbox for Reproducible Research in Ecology_** co-organized by the 
[FRB-CESAB](https://www.fondationbiodiversite.fr/en/about-the-foundation/le-cesab/) 
and the 
[GdR EcoStat](https://sites.google.com/site/gdrecostat/).


### Usage

First install required R packages listed in the 
[`DESCRIPTION`](https://github.com/rdatatoolbox/course-docker/blob/main/DESCRIPTION)
file.

```r
## Install 'remotes' package (if necessary) ----
install.packages("remotes")

## Install required packages ----
remotes::install_deps()
```

To contribute, edit the 
[`index.Rmd`](https://github.com/rdatatoolbox/course-docker/blob/main/index.Rmd) 
file. To update the `html` presentation, run: 

```r
## Convert Rmd to html ----
rmarkdown::render("index.Rmd")
```


### Citation

> Casajus N, Dray S, Gimenez O, Guéry L, Guilhaumon F & Schiettekatte NMD (2021) *Workshop FRB-CESAB & GdR EcoStat: Data Toolbox for Reproducible Research in Computational Ecology*. Zenodo. <http://doi.org/10.5281/zenodo.4262978>.
