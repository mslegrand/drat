# svgR and pointR: Install & Update with drat

Why Drat? Drat provides an easy way to host a R package repository on Github, with seamless install and update capablilites. 
The pointR package is still in flux, hence this makes drat the ideal candiate for distribution.

How to use:
1. Install drat on your local machine:
    + from CRAN via *install.packages("drat")*
    + from github via *install.packages("drat", repos="http://eddelbuettel.github.io/drat")*
2. Add this drat repo  using
    + drat::addRepo("mslegrand")
3. This repository has now been added as additional repository. So to install/update a package pkg simply issue
    + install.packages(pkg) or 
    + update.packages(pkg) 

There are currently only 3 packages here. 

- svgR - a package to generate svg graphics in R
- pointR - a shiny based ide for svgR
- shinyDMDMenu - a dynamic multilevel dropdown menubar for Shiny. 

- enjoy
