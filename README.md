# 5 Immunogenicity Proof of Concepts for Tiered Approach to Assess ADA Positive Samples

ADA three‐tiered testing strategy is deployed here to assess ADA for all 5 POCs.

Sample data are in Sample_Immunogenicity_Data folder. The data are simulated example data sets for deploying the three‐tiered testing strategy. This repository contains 3 data sets in csv format, that are SIMULATED, assuming lognormal distributions. The values in, and structures of the data as well as any potential conclusions or parameter estimates do not correspond to any real experiment. The purpose of the data sets is merely to illustrate possible (or inadequate) data structures and possible application of the various user interfaces and applications for assessing ADA.

Immunogenicity Shiny App:

https://beta.rstudioconnect.com/content/2769/

Immunogenicity website:

https://beta.rstudioconnect.com/content/2770/

Immunogenicity Bookdown Tech Document:

https://beta.rstudioconnect.com/content/2772/

Requires the following packages from CRAN:

```r
install.packages(c("leaflet", "shiny", "shinydashboard", "rmarkdown", "flex_dashboard", "ggplot2", "plotly", "plyr", "reshape2"))
``` 

An up-to-date version of RStudio is also recommended.

R 3.2.5 used for examples.

Links/examples reviewed in the following order:

## **Shiny**

http://shiny.rstudio.com/

    A web application framework for R.

## **R Markdown**

http://rmarkdown.rstudio.com/
  
    R Markdown provides an authoring framework for data science and documents are fully reproducible and support dozens of static and dynamic output formats.

## **HTML Widgets**

http://www.htmlwidgets.org/

    R bindings to JavaScript libraries.
    
## **Applications in Drug Development**

    Live apps, analysis, tools and research.