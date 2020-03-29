# Lectures

Lectures are grouped into four parts: 
* __Foundations__ , 
* __Techniques__ , 
* __Advanced__, as well as
* a __guest__ and an __open lecture__.

## Overview

* [Week 1: Course Introduction](#week-1-course-introduction)
* [Week 2: Foundations I: Basic Concepts](#week-2-foundations-i-basic-concepts)
* [Week 3: Visualization Design and Color](#week-3-visualization-design-and-color)
* [Week 4: Tools & Basic Charts](#week-4-tools--basic-charts)
* [Week 5. Techniques: Multidimensional data and Trees & Hierarchies](#week-5-techniques-multidimensional-data-and-trees--hierarchies)
* [Week 6. Techniques: Networks and Geographic Data](#week-6-techniques-networks-and-geographic-data)
* [7. Techniques: Temporal Data](#week-7-techniques-temporal-data)
* [8. Advanced: Storytelling and Communication](#week-8-advanced-storytelling-and-communication)
* [9.] _cancelled due to university shutdown_ 
* [10. Advanced: Interction for Visualization](#week-10-advanced-interction-for-visualization)
* [11. Advanced: Evaluating visualization techniques](#week-11-advanced-evaluating-visualization-techniques)

## Week 1: Course Introduction
Course and assignmeent overview. Introduction into basics of data visualization

__Lecture Slides:__
 * [Slides: DataVis2020_0-Course Overview.pdf](slides/DataVis2020_1-Course-Overview.pdf) 

Just discovering after the lecture that on Jan 7, the BBC wrote an [article](https://www.bbc.com/news/blogs-trending-51020564) about the misleading visualization about Australian bushfires, discussing alternative visualizations. Quote: _"But it is actually artist Anthony Hearsey's visualisation of one month of data of locations where fire was detected, collected by Nasa's Fire Information for Resource Management System. [...] The scale is a little exaggerated due to the render's glow, but it is generally true to the info from the Nasa website. Also note that not all the areas are still burning, and this is a compilation," Mr Hearsey wrote on Instagram in response to criticism by viewers that the image was misleading."_


## Week 2: Foundations I: Basic Concepts
This lecture introduces the basics concepts of data visualizaion: Why are we using data visualization? Why does visualization work?. The lecture includes topics such as _perception_ and _color_ and concepts such as _exploratory data analysis_, _data-driven storytelling_, _visual variables_, _visual mappings_, _visualization pipeline_, _visualization techniques_, _visual representation_, and _visualization literacy_.

__Required Reading:__
  * [Carpendale_Considering_Visual_Variables.pdf](pdfs/Carpendale_Considering_Visual_Variables.pdf)

__Lecture Slides:__
* [DataVis2020_1-Basic-Concepts.pdf](slides/DataVis2020_2-Basic-Concepts.pdf)

__Further Reading__
* Tamara Munzner: Visualization Analysis and Design
  * Chapter 2. What: Data Abstraction
  * Chapter 5. Marks and Channels
* Alberto Cairo: The Functional Art
  * Chapter 1: Why Visulize: From Information to Visdom
  * Chapter 2: Forms and Functions: Visualization as Technology
  * Chapter 3: Visualizing for the Mind
* Andy Kirk: Data Visualization
  * Chapter 1: Defining Data Visualization
* Jaques Bertin: Semiology of Graphics
  * II.C: The retinal variables
* Cleveland & MaGill: Graphical Perception: Theory, Experimentation, and Application to the Development of Graphical Methods, 1984


## Week 3: Visualization Design and Color

### __Foundations: Visualization design__
This lecture talks about effective and ineffective visualization designs. It shows examples of ineffective and deceptive visualizations and describes _visualization guidelines_ that help designing effective visualiztions. The corresponding tutorial will exercise over common problems with visualizations and work towards proposing solutions via _sketching_, a powerful method introduced in the tutorial.
r
__Lecture Slides:__
* [DataVis2020_2-VisualizationDesign.pdf](slides/DataVis2020_2-VisualizationDesign.pdf)

__Required Reading:__
* Albero Cairo: The Functional Art 
  * Chapter 3: The Beauty Paradox: Art and Communication

__Further Reading__
* Kong, Ha-Kyung, Zhicheng Liu, and Karrie Karahalios. "Frames and slants in titles of visualizations on controversial topics." Proceedings of the 2018 CHI Conference on Human Factors in Computing Systems. 2018.
* Edward Tufte. The Visual Display of Quantitative Information, 1983
* Stephen Few: Sometimes we must raise our voices: http://www.perceptualedge.com/articles/visual_business_intelligence/sometimes_we_must_raise_our_voices.pdf
* Nussbaumer Knafflic: Storyelling with data
  * Chapter 2: Choosing an effective visual
  * Chapter 3: Visual clutter is your enemy
  * Chapter 4: Focus on your audiences' attention
* Bateman, Scott, et al. "Useful junk? The effects of visual embellishment on comprehension and memorability of charts." Proceedings of the SIGCHI conference on human factors in computing systems. 2010.
* Borgo, Rita, et al. "An empirical study on using visual embellishments in visualization." IEEE Transactions on Visualization and Computer Graphics 18.12 (2012): 2759-2768.
* Borkin, Michelle A., et al. "What makes a visualization memorable?." IEEE Transactions on Visualization and Computer Graphics 19.12 (2013): 2306-2315.

### __Video Lecture---Foundations: Color for Data Visualization__
This lecture provides a brief introduction and overview over color perception and the use of color scales in data visualization. It also covers color blindness, color across cultures and some simple tools to use color.

* [DataVis2020_2-Basic-Colors.pdf](slides/DataVis2020_3-Color.pdf)
  * [Video lecture: Color-1-Intro.mov](https://drive.google.com/open?id=1pa7e2j159ezb47ybCk4QAuKl4PGbeyl3) (16mimn)
  * [Video lecture: Color-2-Sequential.mov](https://drive.google.com/open?id=1Aie7pJk5t4x4KcetwGZeOdUzOwVPRXsI) (11min)
  * [Video lecture: Color-3-Diverging.mov](https://drive.google.com/open?id=15mxXWC66trJ5GaSpGg1_0GeSvRcVA8lz) (3min)
  * [Video lecture: Color-4-Categorical.mov](https://drive.google.com/open?id=1qzc0UfVimQH_7J7PrlfP7hHLWFxwoVVB) (6min)
  * [Video lecture: Color-5-Rainbow-colormap.pdf](https://drive.google.com/open?id=1bVXO6UG7scpb4o9U_nxfC5WGh0d6nex-) (12min)
  * [Video lecture: Color-6-Colorblindness.pdf](https://drive.google.com/open?id=168A7ZbWJZCh04YBYuGtRiykAPmK5zz25) (7min)
  * [Video lecture: Color-7-Extra.pdf](https://drive.google.com/open?id=1VaM-1Xu7KM3XwiG-k3UfHkr9C0f8LdmB) (4min)

__Further reading__
* Wong, Bang. "Points of view: Color blindness." (2011): 441.
* Tamara Munzner: Visualization Analysis and Design, 2016; Chapter 10: Map Color and Other Channels
* https://www.color-blindness.com/types-of-color-blindness
* Colin Ware: Information Visualization—Perception for Design, 2012

## Week 4: Tools & Basic Charts

### Foundations: Tools for data visualizations
This lecture overviews and introduces common software applications (tools) to help with both: data analysis and the creation of visualizations. We will overview tools for programming environments such as python (e.g., Seaborn) and javascript (e.g., D3), but also tools using common user interfaces (e.g, [Rawgraph](https://rawgraphs.io), [Datawrapper](https://www.datawrapper.de)). The lecture will not teach _how_ to use these tools, but focus on a high-level overview of the many different tools and workflows exist to create data visualizations. 

__Lecture Slides__
* [DataVis2020_4-VisualizationTools.pdf](slides/DataVis2020_4-VisualizationTools.pdf)
* [Online version (with videos)](https://docs.google.com/presentation/d/1iStzcflas6nI16zWF4PaExCFsW1OH4XlsjweAWZPylc/edit?usp=sharing)

__Links__
* [Ben's Visualization Tool Collecton](https://visualinteractivedata.github.io/res-tools.html)
* [Visualization Tool Collecton from Datavisualization.ch](Datavisualization.ch)


### __Video Lecture---Techniques: Basic Charts__
This is the first of a set of lectures on visualization techniques, i.e., charts and visual representations. This lecture gives a brief overview over basic charts often used in scientific reports and news papers. This includes histograms, barcharts, violinplots, boxplot, linecharts, and piecharts. 

* [DataVis2020_4-Basic-Charts.pdf](slides/DataVis2020_4-StatisticalCharts.pdf)
  * [Video lecture: Basic-Charts-1.mov](https://drive.google.com/open?id=1Ys8TZH6niXuUeGi_23XkcKPKw0rs7dym) (13min)
  * [Video lecture: Basic-Charts-2.mov](https://drive.google.com/open?id=1AMkxrJSzYw4sVTAfkAmcWLcb1FBAT-Gv) (19min)
  * [Video lecture: Basic-Charts-3.mov](https://drive.google.com/open?id=1ZYFIcJsoOWDOudpIwTVx7BBFeIvrMIM1) (10min)

__Further reading__
* Wilke, Claus O. Fundamentals of data visualization: a primer on making informative and compelling figures. O'Reilly Media, 2019.
  * [https://serialmentor.com/dataviz/visualizing-proportions.html](https://serialmentor.com/dataviz/visualizing-proportions.html)
  * [https://serialmentor.com/dataviz/histograms-density-plots.html](https://serialmentor.com/dataviz/histograms-density-plots.html)
  * [https://serialmentor.com/dataviz/boxplots-violins.html](https://serialmentor.com/dataviz/boxplots-violins.html)
* Hullman, Jessica, Paul Resnick, and Eytan Adar. "Hypothetical outcome plots outperform error bars and violin plots for inferences about reliability of variable ordering." PloS one 10.11 (2015).
* Skau, Drew, and Robert Kosara. "Arcs, angles, or areas: Individual data encodings in pie and donut charts." Computer Graphics Forum. Vol. 35. No. 3. 2016.
* Cairo, Alberto. The truthful art: data, charts, and maps for communication. New Riders, 2016.
  * Chapter 6: Exploring Data with Simple Charts
  * Chapter 7: Visualizing Distributions


## Week 5. Techniques: Multidimensional data and Trees & Hierarchies

### Techniques: Multidimensional data
As multidimensional data we can describe all sorts of data sets that have a variety of attributes, for example columns in table. Generally speaken, the more columns a dataset has, the more dimensions it has. This lecture talks about visualization techniques for multivariate data such as __scatterplots__, __glyphs__, __Mekko Chart__, __Heatmaps__, __Beeswarm plots__, __Scatterplot matrices__, __Parallel Coordinates Plots__, and __Multi-dimensional scaling__.

__Lecture Slides__
* [DataVis2020_5-MultivariateData](slides/DataVis2020_5-MultivariateData.pdf)

__Further Reading__
* Shneiderman, Ben. "The eyes have it: A task by data type
taxonomy for information visualizations." Proceedings 1996 IEEE
symposium on visual languages. IEEE, 1996.
* Fuchs, Johannes, et al. "A systematic review of experimental
studies on data glyphs." IEEE transactions on visualization and
computer graphics 23.7 (2016): 1863-1879.
* Heinrich, Julian, and Daniel Weiskopf. "State of the Art of
Parallel Coordinates." Eurographics (STARs). 2013.
* [https://visualizationcheatsheets.github.io/pcp.html](https://visualizationcheatsheets.github.io/pcp.html)

### Video Lecture--- Techniques: Trees and Hierarchies

__Lecture Slides__
* [DataVis2020_5-Trees+Hierarchies.pdf](slides/DataVis2020_5-Trees+Hierarchies.pdf)

__Recordings__
* [Video lecture: Trees-1.mov](https://drive.google.com/open?id=121Ew3jwtafBAL-CGU5JJJh2orRfo7hix) (42:05min)
* [Video lecture: Trees-2.mov](https://drive.google.com/open?id=1CxKpDcsSX0wrh0t8cZ6riKUm9sG001u5) (5:41min)

__Further Reading__
* Schulz, Hans-Jorg, Steffen Hadlak, and Heidrun Schumann. "The design space of implicit hierarchy visualization: A survey." IEEE transactions on visualization and computer graphics 17.4 (2010): 393-411.


## Week 6. Techniques: Networks and Geographic Data

### Techniques: Networks

__Required Reading__
* [Task Taxonomy for Graph Visualization](pdfs/lee-beliv06.pdf)
* [A Comparison of the Readability of Graphs Using Node-Link and Matrix-Based Representations ](pdfs/ghoniem2004.pdf)

__Lecture Slides__
* [DataVis2020_6-Networks](pdfs/DataVis2020_6-Networks.pdf)
* [Flowgraph video](https://drive.google.com/open?id=0B4NT53pZkCtnZjd3VklJUDRJbTA)


### Video Lecture---Techniques: Geographic Data


__Lecture Slides__
* [DataVis2020_6-Geographic](slides/DataVis2020_6-Geographic.pdf)

__Videos__
* [Geography-1.m4v: Outline + Tasks (6:36)](https://drive.google.com/open?id=13vFG1dNFdFEKE_fEOtmFyUFbs757S0OC)
* [Geography-2.m4v: Map Projections (21:11)](https://drive.google.com/open?id=1lEt6B-2fNrtVK-ILa0DwjIGdfZ32Xsnu)
* [Geography-3.m4v: Visualizing Area Data (14:06)](https://drive.google.com/open?id=1bLKtlhxy72wLzTO5WvyzcdjSBCtsqiQu)
* [Geography-4.m4v: Visualizing Point Data (5:08)](https://drive.google.com/open?id=1oeI11M-mnBDDZHgeJIusjWqzg8oM8tQd)
* [Geography-5.m4v: Visualizing Trajectories (10:52)](https://drive.google.com/open?id=1cXEpw6QwR3WQHFkoDaU6ynXLDmU5qPW_)
* [Geography-6.m4v: Visualizing Time (3:52)](https://drive.google.com/open?id=1wEm98Qj-_IZ1mdyrAf3dCf-9e2R7CBqh)


__Further Reading__
* Alberto Cairo: The Truthful Art: Chapter 10: Mapping Data
* Bertin, Jacques. Semiology of graphics; diagrams networks maps. No. 04; QA90, B7.. 1983.
* Andrienko, Gennady, et al. "Space, time and visual analytics." International journal of geographical information science 24.10 (2010): 1577-1600.
* Andrienko, Natalia, and Gennady Andrienko. Exploratory analysis of spatial and temporal data: a systematic approach. Springer Science & Business Media, 2006.
* Bach, Benjamin, et al. "A descriptive framework for temporal data visualizations based on generalized space‐time cubes." Computer Graphics Forum. Vol. 36. No. 6. 2017.
* Bach, Benjamin, et al. "Ways of Visualizing Data on Curves." 2018.



## Week 7. Techniques: Temporal Data

__Mandatory Reading__
Glance at this paper. No need to read everything but try to get an idea of the space-time cube metaphor that the paper is talking about and how it's used to describe data visualization.
* Bach et al: A Descriptive Framework for Temporal Data
Visualizations Based on Generalized Space-Time Cubes, Computer Graphics Forum, 2016: [https://hal-enac.archives-ouvertes.fr/hal-01303506/file/Bach2016spacetimecubes.pdf](https://hal-enac.archives-ouvertes.fr/hal-01303506/file/Bach2016spacetimecubes.pdf)

### Techniques: Temporal Data
__Lecture Slides__:
* [DataVis2020_7-TemporalData.pdf](slides/DataVis2020_7-TemporalData.pdf)

__Further reading__
* Alberto Cairo: The Truthful Art: Chapter 8: Revealing Change
* Aigner, Wolfgang, et al. Visualization of time-oriented data. Springer Science & Business Media, 2011.
* Bach, Benjamin, et al. "A descriptive framework for temporal data visualizations based on generalized space‐time cubes." Computer Graphics Forum. Vol. 36. No. 6. 2017.
* Rosenberg, Daniel, and Anthony Grafton. Cartographies of time: A history of the timeline. Princeton Architectural Press, 2013.
* Brehmer, Matthew, et al. "Timelines revisited: A design space and considerations for expressive storytelling." IEEE transactions on visualization and computer graphics 23.9 (2016): 2151-2164.



## Week 8. Advanced: Storytelling and Communication

This lecture focuses on effective presentation techniques when using visualizations in e.g., infographics or presentations. Other presentation media can include videos, posters, and [datacomics](http://datacomics.net). The lecture investigates how presenting and talking with visualizations is different than using visualizations for exploring and analyzing data. Spoiler alert: "It's the audience, stupid!".

__Lecture Slides:__
* [DataVis2020_8-Storytelling](slides/DataVis2020_8-Storytelling.pdf)

__Further Reading:__
* Alberto Cairo: The Functional Art
* Riche, Hurter, Diakololpous, Carpendale: Data-Driven Storytelling
* Bach et al.: [Narrative Patterns for Data-Driven Storytelling](pdfs/Narrative_Design_Patterns__for_Data_Driven_Storytelling.pdf), 2017 [http://napa-cards.net](http://napa-cards.net)
* Chevalier et al: [Using concrete scales: A practical framework for effective visual depiction of complex measures](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.397.9881&rep=rep1&type=pdf), 2013 
* Bach et al.: [The Emerging Genre of Data Comics](https://innovis.cpsc.ucalgary.ca/innovis/uploads/Publications/Publications/carpendale2017emerging.pdf), 2017
* Bach et al.: [Design Patterns for Data Comics](https://www.pure.ed.ac.uk/ws/files/57948259/Bach2018designpatterns.pdf), 2019

## Week 9. Guest Lecture: Renaud Blanch

_cancelled due to University shutdown_

## Week 10. Advanced: Interction for Visualization

This lecture talks about the need for interaction in visualization and will present a range of interaction techniques for specific visualization related tasks: _select, explore, reconfigure, encode, abstract, filter, connect_.


__Lecture Slides:__
* [DataVis2020_10-Interaction](slides/DataVis2020_10-Interaction.pdf)

__Further Reading:__
* Yi, Ji Soo, Youn ah Kang, and John Stasko. "Toward a deeper understanding of the role of interaction in information visualization." IEEE transactions on visualization and computer graphics 13.6 (2007): 1224-1231.
* Amar, Robert, James Eagan, and John Stasko. "Low-level components of analytic activity in information visualization." IEEE Symposium on Information Visualization, 2005. INFOVIS 2005.. IEEE, 2005.
* Tamara Munzner: Manipulate View (Chapter 11)  in Tamara Munzner: Visualization Analysis & Design.
* Tominski, Christian, et al. "Interactive lenses for visualization: An extended survey." Computer Graphics Forum. Vol. 36. No. 6. 2017. 

## Week 11. Advanced: Evaluating visualization techniques
This lecture covers techniques to assess if a given visualization technique (existing or your own creation) is "successful". Successful is a broad term and refers to both effectiveness and efficiency in which a user or audience are supported in their analysis or understanding of the data. The lecture proposes five levels to check for success _Visibility_, _Readability_, _Understandability_, _Appropriateness_, _Truthfulness_. Evaluation methods involve a set of techniques from Human-Computer Interaction (HCI) such as _guidlines_,  _quantitative evaluation_, _qualitative visualization_, _user tracking_, _samples_, and _tasks_, and _statistical analysis_. 

