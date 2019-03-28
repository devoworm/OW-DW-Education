# Developmental Data Science  
### Sponsored by  
[DevoWorm Group](https://devoworm.weebly.com/) and [OpenWorm Foundation](http://openworm.org/). 

### Contributors/Instructors  
Dr. Bradly Alicea [web](https://bradly-alicea.weebly.com/), TBA

### Duration  
This course is self-paced, but overall should involve around 20-30 hours of engagement (about 40% in-class time for a 3-credit University course).  

### Discussion Board
Link to [discussion board](https://eliademy.com/app/a/courses/bdb7b0a934/discussions). Here you will discuss assignments, presentations, and readings.

### What will you receive
1) an understanding of how developmental biology can be approached using the tools and principles of data science.  

2) a crash-course in developmental biology.  

3) the ability to make a substantial contribution to the OpenWorm/DevoWorm community.  

### Summary 
This course is intended to provide collaborators and students with basic background in how to conduct data science research with particular relevance to the area of developmental biology. It also approaches developmental biology from a data scientific perspective, highlighting ways to analyze data extracted from developmental processes. Taken together with the other short courses, tutorials, and microcredentials in the OW/DW curriculum, this course should offer new OW/DW contributors and interested learners in the global community an indispensible educational resource.

### Evaluation  
Each section will have assignments, which the learner will complete to earn each part of the course. Assignments will be pushed to an appropriate folder in the [Push Assignments Here](https://github.com/devoworm/OW-DW-Education/tree/master/Developmental%20Data%20Science/Push%20Assignments%20Here) subdirectory.


### License  
All content is licensed under Creative Content license ([CC-BY-SA-4.0](https://github.com/devoworm/Licensing-DRM/blob/master/CC-BY-SA-4.0%20License.md)).  

## Introduction and Community Standards  
Flash talk: DevoWorm group Introduction   [talk](https://www.youtube.com/watch?v=7jpksJcYK6E)  

Basic _C. elegans_ biology references   [link](https://github.com/devoworm/devoworm.github.io/blob/master/Basic-C.%20elegans-Biology-References.md)  

Standards for Open Data Analysis   [link](https://github.com/devoworm/devoworm.github.io/blob/master/Creating-Open-Datasets.md)  

Visualizing Human Embryos   [link](https://embryo.asu.edu/pages/visualizing-human-embryos-1999-bradley-richard-smith)  

Glossary of terms -- Molecular Cell Biology (NCBI)   [link](https://www.ncbi.nlm.nih.gov/books/NBK21607/)  

## Topics  

**Introduction) abstraction, data sources, and storage formats**   
&nbsp;&nbsp;&nbsp;&nbsp;a) How to build a digital embryo: [Object-Oriented Thinking for Biological Systems lecture](https://drive.google.com/file/d/1kS8gUHAvTaAXQpJNZ548sRLq0uVP3tt2/view), [WormBrowser -- Blender Model of Adult _Caenorhabditis elegans_](http://browser.openworm.org/)

&nbsp;&nbsp;&nbsp;&nbsp;b) Image/literature mining and repositories: [Literature Mining I badge (working with papers)](https://www.badgelist.com/Orthogonal-Research/Literature-Mining-I-working-with-papers), [Literature Mining II badge (working with secondary data)](https://www.badgelist.com/Orthogonal-Research/Literature-Mining-II-working-with-secondary-data)    

&nbsp;&nbsp;&nbsp;&nbsp;c) Data Frameworks: [CSV](https://en.wikipedia.org/wiki/Comma-separated_values), [XML](https://www.w3schools.com/xml/default.asp), [JSON](https://www.w3schools.com/js/js_json_intro.asp), [PyOpenWorm](https://pypi.org/project/PyOpenWorm/)   

**Assignments** 
1) enroll for and earn both Literature Mining badges [1](https://www.badgelist.com/Orthogonal-Research/Literature-Mining-I-working-with-papers),[2](https://www.badgelist.com/Orthogonal-Research/Literature-Mining-II-working-with-secondary-data) on Badgelist (Instructors will award).   

2) using [these tabular data](https://github.com/devoworm/OW-DW-Education/blob/master/Data%20Repo/sampledata.csv), reformat into either XML or JSON format and submit a pull request to [this repo](https://github.com/devoworm/OW-DW-Education/tree/master/Data%20Repo) consisting of a file labeled FirstName_LastName.foo


**1) Data Types**   
a) point data: a single object or event. **Example:** a cell centroid.

b) processes: multiple units of point data that are linked through a set of causal relationships. **Example:** growth of a cell cluster.

c) comparative: analogies between multiple processes. **Example:** growth in a slime mold versus growth in a bacterial colony.

d) longitudinal: point data, processes, or comparisons that occur over time. **Example:** different phases of growth, from early to late in the process.

**Assignments**
1) download [this Slideshow]() about each data type and answer [these questions]()


**2) From Cells to Pixels**  
a) image segmentation: read the [Wikipedia stub](https://en.wikipedia.org/wiki/Image_segmentation) on this topic.

* segment [this image](https://github.com/devoworm/Drosophila-imaginal-disc-segmentation/blob/master/Wolff-Gordon-Gordon-drawing.TIF) of the _Drosophila_ third instar eye imaginal disc using [ImageJ](https://imagej.nih.gov/ij/) or [OpenCV](https://opencv.org/).

b) feature selection: read the [Wikipedia stub](https://en.wikipedia.org/wiki/Image_segmentation) on this topic.

* review the [feature selection examples here](https://github.com/devoworm/Drosophila-imaginal-disc-segmentation/tree/master/Areal%20Size%20Distributions), and using the image [presented in step a](https://github.com/devoworm/Drosophila-imaginal-disc-segmentation/blob/master/Wolff-Gordon-Gordon-drawing.TIF), run your own feature selection analysis using [ImageJ](https://imagej.nih.gov/ij/) or [OpenCV](https://opencv.org/).

c) categorization and annotation: read these Wikipedia stubs ([categorization](https://en.wikipedia.org/wiki/Categorization), [annotation](https://en.wikipedia.org/wiki/Annotation)) on the topics.

* review these data tables ([1](), [2]()) and produce two plots: one showing the number of neurons present at different time periods, and the other showing changes in the number of cells present by cell family over time.

**Assignments**
1) download and read the paper "[Morphogenetic processes as data: Quantitative structure in the Drosophila eye imaginal disc](https://www.biorxiv.org/content/10.1101/395640v1)".

2) identify each analysis in the accompanying [open data repo](https://github.com/devoworm/Drosophila-imaginal-disc-segmentation)

3) review the activities for this section and push images representing "image segmentation", "feature selection", and "categorization and annotation" to the [Push Assignments Here repo](https://github.com/devoworm/OW-DW-Education/tree/master/Developmental%20Data%20Science/Push%20Assignments%20Here) for this section.


**3) Data Structures**    
&nbsp;&nbsp;&nbsp;&nbsp;a) lineage and differentiation trees:  

&nbsp;&nbsp;&nbsp;&nbsp;b) embryo networks:  

&nbsp;&nbsp;&nbsp;&nbsp;c) time-series:  

&nbsp;&nbsp;&nbsp;&nbsp;d) topological maps:  

**Assignments**  


**4) Artificial Life**  
&nbsp;&nbsp;&nbsp;&nbsp;a) representational models:  

&nbsp;&nbsp;&nbsp;&nbsp;b) discrete spatial simulation and data:  

&nbsp;&nbsp;&nbsp;&nbsp;c) generative methods:   

**Assignments**  




## Local (DevoWorm) Resources  
Imaginal Disc of _Drosophila melanogaster_     [link](https://github.com/devoworm/Drosophila-imaginal-disc-segmentation)  

Metadata for early _Ciona intestinalis_ embryogenesis   [link](https://github.com/devoworm/DevoWorm/tree/master/Ascidian%20Embryogenesis%20Data)

Processed data for _Caenorhabditis elegans_ embryogenesis   [cell position](https://github.com/devoworm/DevoWorm/tree/master/Positional%20Info), [cell lineage tree](https://github.com/devoworm/DevoWorm/tree/master/Lineage%20Tree%20DB), [cell birth/death times](https://github.com/devoworm/DevoWorm/tree/master/Cell%20Birth%20and%20Death%20Timing%20Data)


## Additional Resources   
DevoWorm: DevoZoo   [link](https://devoworm.github.io/)  

RIKEN: Systems Science of Biological Dynamics (SSBD) database   [link](http://ssbd.qbic.riken.jp/)  

OpenWorm: PyOpenWorm   [link](https://pypi.org/project/PyOpenWorm/)  

OpenWorm: Community Data Science   [link](https://github.com/devoworm/Data-Science)  

Developmental Biology Interactive   [link](http://www.devbio.biology.gatech.edu/)   


## Computational Concepts   
Generative Model   [link](https://en.wikipedia.org/wiki/Generative_model)  

Agent-Based Model   [link](https://en.wikipedia.org/wiki/Agent-based_model)  

Mathematical Model   [link](https://en.wikipedia.org/wiki/Mathematical_model)  

Phenomenological Model   [link](https://en.wikipedia.org/wiki/Phenomenological_model)  

Conway's Game of Life   [link](http://www.conwaylife.com/wiki/Conway%27s_Game_of_Life)  

Complexity Explorables   [link](http://www.complexity-explorables.org/)
