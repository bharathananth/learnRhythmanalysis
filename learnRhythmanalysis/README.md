## learnRhythmanalysis

<!-- badges: start -->
<!-- badges: end -->

This hands-on tutorial will walk you through a few standard approaches to analyze rhythms in your data using R. 

There are many proposed methods for circadian rhythm analysis. Often, it is unclear where to start and what methods to choose? The choice depends on the type of data you have (e.g., high-throughput omics data, continuous time reporter recordings) and the experimental design. The goal of this tutorial is:

1.	to introduce you to some standard approaches
2.  to make you aware of the limitations and caveats of the methods
3.	to enable you to spot basic problems with your data
4.	to direct you to resources to learn more
5.	most importantly, to make you think about these issue BEFORE you design your experiments

### Installation and Running the Tutorial

0. Before you install the package, please set your default browser to Safari/Firefox/Chrome. Internet Explorer does not work properly with shiny apps.

1. Install R on your computer (choosing the appropriate version for Windows, Linux or Mac) from [CRAN](https://cran.r-project.org)

2. Download and Install (the free) [RStudio Desktop](https://www.rstudio.com/products/rstudio/download/#download) for your operating system

3. Install Bioconductor with:
``` r
if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")
BiocManager::install()
```

4. Install required packages with:
```r
install.packages(c("learnr", "devtools"))
BiocManager::install("rain")
```

5. You can install the current version of learnRhythmanalysis from [github](https://github.com/bharathananth) with:

``` r
devtools::install_github("bharathananth/learnRhythmanalysis")
```

6. Run the *interactive* tutorial using:
```r
learnr::run_tutorial("tutorial", package = "learnRhythmanalysis")
```

### EBRS Trainee day attendees.

I will assume you have some basic knowledge of R (although this is not essential to sit through the tutorial, but eventually you will need it to apply the methods).  

Bring your **fully-charged** laptops to the session.  

Preferably, follow steps 0-6 in the installation guide **before** trainee day.  

Come with your data, curiousity and questions.
