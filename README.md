
<!-- README.md is generated from README.Rmd. Please edit that file -->

# The nphys package

The nphys package provides a means to easily analyze and view
electrophysiology data, while also and a tools for managing your
project.

It is geared towards developing robust and portable data management
tools that can easily call on various methods of analysis. Detailed
examples of how to utilize this package will be outlined in vignettes as
they are updated.

<!---
If you are interested in adding a dataset or other contributions to the project contact me at \href{scott@nrsccollective.com}


## Usage
Neurophysiology experiments generally require collectiing many individual data files and keeping track of a large number of methodology variables. Infact, often times methodology variables will go over look during analysis, simply because  and and it can be difficult to  

Performing neurophysiology experiments almost always requires paying close attention to the response while also retaining relevant information for later analysis. Knowing what is relevant comes through practice, and the hands on nature of neurophysiology makes it is easy to potentially loose track of or misrepresent important information.

While many commercial software packages support options for viewing and analyzing evoked responses (i.e.pClamp, Patchmaster), there is often little focus on creating complete project constructs that allow for cross platform development of a0 project, including documentation, data organization, and eventually compiling the work into a single presentable document. 

Running an experiment with the help of R enables us to ensure that consistency is maintained throughout all avenues of the experimental procedure, and that we can easily look back on our data and find new ways to apply the same methods of analysis to each new piece of collected data.
It also allows us to easily re-examine our entire dataset without going back to each individual abf or dat file, by compiling all of the relevant information into one place. 


This package is optimized towards maintaining an organized project data, so you can access and present it on a moments notice during a discussion, similar to how you may show off pictures of your kids at the backyard bbq.  
We want to be able to able to interact with the data, and effeciently incorporate updated analysis into our ongoing project. The goal is to have easily reproducible access to analyzing our complete dataset, while simplifying updating the entire project.  
Too often I see students set their cursors, measure the slope, copy the output into excel, then never look at that data again. 


### The first step: using the nphys package to build a project directory.

Typical project builds are templates for certain types of projects being run, and contents will vary based upon the needs of the project, but the basic components remain the same. We are going to begin by building the project `EXA` (for example) by simply calling the built in function `nphys::build_proj("EXA")`

Projects and project directories are labeled `proj` followed by (generally 3) letter identifiers that are short and easy to reference. `e.g. projEXA`. It is optimal to maintain project directories immediately downstream from where your tilde is assigned `e.g. "~/projEXA`. To find out what directory your tilde is assigned to type `setwd("~")` in your console, followed by `getwd()`. Reassigning your working directory to your project directory will then be as simple as executing `setwd("~/projEXA")`

> Heads up! This will change your working directory and if you do not change it back, you may encounter errors when trying to work within the project. 



%helping to manage large data sets in a way that presents comprehensive summaries that can be rapidly updated and observed from many different angles.


This package is currently geared towards field long-term depression (LTD) experiments and whole-cell patch-clamp experiments, but will continue to be updated as more example datasets and methodologies become available.



Using the nphys packages while running an experiment is simple   

--->

## License

This package is free and open source software.
