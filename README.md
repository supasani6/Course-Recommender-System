A Real-time Course Recommender System
=====================================

This project is a web application for course recommender system using R and R Shiny

Link :	https://rts-course-recommender.shinyapps.io/course_recommender_system/

Requirements for running the project through source code:
----------------------------------------------------------

You will need to install the following to run the .r files:

* R Environment(R-3.3.2 for Windows (32/64 bit)) Link :https://cran.r-project.org/bin/windows/base/ 

* RStudio 1.0.44 - Windows Vista/7/8/10 (IDE for R) RStudio 1.0.44 - Mac OS X 10.6+ (64-bit) Link:https://www.rstudio.com/products/rstudio/download3/

* Packages required :

   * arules
   * shiny
   * shinydashboard
   * stringr
   * datasets

These packages can be installed by typing "install.packages("package_name")" in the R Studio console.
Make sure the libraries are included before the program is run!!!

Steps to run the program:
---------------------------

* Place the ui.r, server.r, Login.r files and all database files in a new directory

* Make sure the databases are in the same directory as the .r files (not in a subfolder).

* Set the working directory of Rstudio to this project directory using the command setwd ('path/to/directory')

* Open server.r and click runApp button on the top right of the editor, or type runApp() in the RStudio console.



