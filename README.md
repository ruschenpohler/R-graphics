![](/visuals/iris_compound.jpg)

# R Graphics

This workshop will provide an introduction to graphics in R with ggplot2. Participants will learn how to construct, customize, and export a variety of plot types in order to visualize relationships in data. We will also explore the basic grammar of graphics, including the aesthetics and geometry layers, adding statistics, transforming scales, and coloring or panelling by groups. You will learn how to make histograms, boxplots, scatterplots, lineplots, heatmaps, and geographic maps using the Google Maps API. You will also learn how to facet plots and create compound figures. 

**Prior experience with R is assumed such as R-Fundamentals Parts 1 through 4 or equivalent knowledge.**

### Setup

1. [Download R](https://cloud.r-project.org/)  
2. [Download RStudio Desktop Open Source License FREE](https://rstudio.com/products/rstudio/download/#download)  
3. [Download the workshop materials](https://github.com/dlab-berkeley/R-graphics)  

**How to download the workshop materials**

* Click the green “Clone or download” button  
* Click “Download Zip”  
* Extract the files some place convenient (i.e., Desktop)  
  * if you are a Git user, simply clone this repository  

4. Install the necessary packages by running the below code: 

```
install.packages(c("ggplot2", "cowplot", "dplyr", "ggmap"))

library(ggplot2)
library(cowplot)
library(dplyr)
library(ggmap)
```

### Getting started

- Open "R-graphics-tutorial.Rmd" to work through the example code  
- Open "challenges-ggmap.Rmd" to view the challenge problems and ggmap examples  
- .html files can be found in the "html" folder  
- Visualizations are in the "visuals" folder  

Credit: Thanks to [Software Carpentry](http://software-carpentry.org/workshops/), Chris Paciorek, Rochelle Terman, Josh Quan, and the [R-bootcamp](https://dlab.berkeley.edu/training/r-bootcamp-3) for inspiration.

### Next Steps

The ggplot2 package can also be used to make great maps! Check out the file `challenges-ggmap.Rmd` (and its solutions file) to see how to make maps such as the one displayed below.

Then, if you wish to get further into advanced mapping in R,
check out our [Geospatial-Fundamentals-in-R-with-sf](https://github.com/dlab-berkeley/Geospatial-Fundamentals-in-R-with-sf.git) workshop!

![](/visuals/netherlands_facet.jpg)
