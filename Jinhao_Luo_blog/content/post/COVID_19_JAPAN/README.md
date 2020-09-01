# COVID-19 situations of Japan

This post is used for exploring the situations of COVID-19 in Japan. 

## Data source

The data come from the coronavirus package in Github of Rami Krispin. You can browse the related information of coronavirus package by this [link](https://github.com/RamiKrispin/coronavirus).

You have two ways to download the coronavirus package.

### CRAN version

Try the command: 

**install.packages("coronavirus")**

### Github version

Try the command: 

**install.packages("devtools")**

**devtools::install_github("RamiKrispin/coronavirus")**

P.S.  You need to install the devtools package first, if you already have this package, please ignore it.

### Data refresh

To refresh the data, please try:

**library(coronavirus)**

**update_dataset()**

Or you can use the Covid19R project data standard format to pull the data, please try:

**new_object <- refresh_coronavirus_jhu()**

P.S. You can rename the new_object