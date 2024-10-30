# 2024_nep.fu.2021_assessment
2024 - Norway lobster (Nephrops norvegicus) in divisions 7.g and 7.h, functional units 20 and 21 (Celtic Sea) - WGCSE(ADGNEPH)

## R packages 

## Mixfish object Output available:
output_01_assessment_summary.html
section 2.2_Reformat_for_WGMIXFISH_Stock_object
fu2021.nep.stock.wgmixfish.csv


The following R packages from CRAN are required to run the assessment:

```{r, eval = FALSE}
library(RODBC)
library(tidyverse)
library(lattice)
library(lubridate)
library(mapplots)
library(sp)
library(sf)
library(reshape2)
library(readxl)
library(knitr)
library(DataCombine)
library(lattice)
library(icesTAF)
library(magrittr)
library(viridis)
library(sessioninfo)
library(stringr)
maps
mapproj
.Last.projection=list(active=F,projection="mean",parameters=NULL,orientation=NULL)
fields
RColorBrewer

```