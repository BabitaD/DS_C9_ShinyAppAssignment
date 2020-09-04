Reproducible Pitch Assignment
========================================================
author: Babita 
date: 05 Sept 2020
autosize: true

Introduction
========================================================

This presentation is part of the Developing Data Products Coursera.org course project submission.

It is an R Presentation generated with RStudio.

The Shiny application pitched by this presentation is at https://babitad.shinyapps.io/ShinyAppAssignment/

The Shiny app source code is available at https://github.com/BabitaD/DS_C9_ShinyAppAssignment

Application Overview
========================================================
- The application is written in Shiny which is a web application framework for R
- The source code consists of two files: server.R and ui.R
- server.R includes the the server logic of a Shiny web application
- ui.R includes the the user-interface definition, which uses the sidebarLayout template
- The application is hosted on Rstudio's shiny server in the cloud (Shinyapps.io)

How it works? - I | The Application contains: Left Panel
========================================================

- Change the slider on the left to input MPG value
- Select checkboxes to display the model
- Click Submit Button to get changes reflected on the output on right
- Check the predicted value at the bottom of the plot
- Select data options using selectInput and sliderInput


Slide With Code
========================================================


```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Ready to give it a try?
========================================================

Use the Shiny app at https://babitad.shinyapps.io/ShinyAppAssignment/

Get the app source code at https://github.com/BabitaD/DS_C9_ShinyAppAssignment
