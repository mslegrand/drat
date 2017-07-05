# svgR and pointR: Install & Update with drat

Why Drat? Drat provides an easy way to host a R package repository on Github, with seamless install and update capablilites. 
The pointR package is still in flux, hence this makes drat the ideal candiate for distribution.

How to use:

1. Install  the [drat](http://eddelbuettel.github.io/drat/) package manager.

```
install.packages("drat", repos="http://cran.rstudio.com")
```
2.  Add one line to your *.Rprofile* file (or to *Rprofile.site*) 

```
drat:::add("mslegrand")
```
If you don't have an *.Rprofile*, you should really consider adding one. It can be quite useful. 

For help on *.Rprofile*, *Rprofile.site* see

- [Customizing Startup](http://www.statmethods.net/interface/customizing.html) 
- [Fun with Rprofile](https://www.r-bloggers.com/fun-with-rprofile-and-customizing-r-startup/)

3. Install or update 

```
install.packages("svgR", "pointR", "shinyDMDMenu")
```

```
update.packages("svgR", "pointR", "shinyDMDMenu")
```

There are currently only 3 packages here. 

- **svgR** - a package to generate svg graphics in R
- **pointR** - a shiny based ide for svgR
- **shinyDMDMenu** - a dynamic multilevel dropdown menubar for Shiny. 

Enjoy!!
