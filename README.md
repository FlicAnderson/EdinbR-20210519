# EdinbR-20210519

## EdinbR Talk: 

# *Putting the 'viz' back into 'riboviz':* connecting Rmarkdown, Shiny and Nextflow

Presentation \& Materials for EdinbR Talk 19th May 2021 on Riboviz (Event details: https://www.meetup.com/EdinbR/events/278094996/)

Available to view on EdinbR YouTube channel: **[watch the talk on YouTube](https://youtu.be/2C_WpraLznc?t=1596)**

### Talk Abstract:  

'riboviz' is an open source software package for processing and analysing ribosome profiling (RNA sequence) data.

This talk will briefly cover the implementation of an Rmarkdown HTML output report and Shiny app for data visualisation of ribosome profiling datasets, added as part of development efforts to make riboviz more user-friendly and effective.  

Flic will describe the initial approach and pitfalls encountered while developing the new visualisation features, and discuss integrating the visualisation side of riboviz with the recently implemented workflow management system (Nextflow) riboviz has moved to.  

Including a short primer on what Workflow Management Systems such as Nextflow 'do' and why they're useful for complex data pipelines, and details on how to get Rmarkdown HTML reports to play nicely as part of a Nextflow workflow. 

### Speaker Bio: 

Flic Anderson is a Research Assistant in Bioinformatics in the Wallace Lab (within the Institute for Cell Biology) at the University of Edinburgh. The Wallace Lab works to understand how translation works within cells (particularly of fungi) and what factors control and regulate protein synthesis. 

Flic is part of the development team for the 'riboviz' open source software package for processing and analysis of ribosome profiling data, working with colleagues from EPCC (University of Edinburgh) to make the codebase more robust & sustainable.   

With a background in Ecology and Botany (previously a Research Assistant at the Royal Botanic Garden Edinburgh), Flic has worked with a wide range of types of biological data using different software tools and programming languages (particularly R) for the last 8 years, and found herself drawn towards bioinformatics and research software engineering. 

Flic is a member of the Edinburgh Carpentries and a certified Carpentries instructor in foundational coding and data science skills for researchers. 


### Viewing Presentation Material 

You can download the .html slides file `LabTalk-riboviz_slides.html` and open this in a browser to view as a slideshow.  You can type 'f' to view fullscreen, or use browser's zoom functions to zoom in or out with the browser bars staying visible. 

You can also re-knit the .Rmd file `LabTalk-riboviz_slides.Rmd` in RStudio to re-generate the .html file, or by running `rmarkdown::render("LabTalk-riboviz_slides.Rmd")` in R. 


### How to (Re-)Use This Material

This is a `.html` presentation created in `R Markdown` with `ioslides`. 

(It's been written in a [.Rmd](http://rmarkdown.rstudio.com) file, and I generated .html slides by 'knitting' it in Rstudio.)

You can check out the code used to make these slides at the [Talk repo](https://github.com/FlicAnderson/LabTalk-riboviz-20210510) on Github, and adapt it for your own presentations if you like - there's a MIT Licence on the repo, which means: 

*"Basically, you can do whatever you want as long as you include the original copyright and license notice in any copy of the software/source."*

Source: [tl;drLegal](https://tldrlegal.com/license/mit-license)  

Presentation based on a slide template for [this material](https://github.com/FlicAnderson/20201127-gitflow-workshop/blob/main/workshop_slides.Rmd) 'branched'/adapted from last commit 370f633 from this repo - [FlicAnderson/20201127](https://github.com/FlicAnderson/20201127-gitflow-workshop) - which I initially put together for a Wallace Lab Git Workshop.
