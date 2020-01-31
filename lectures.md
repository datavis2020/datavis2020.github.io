# Lectures

Lectures are grouped into four parts: 
* __Foundations__ (I-III), 
* __Techniques__ (I-III), 
* __Advanced__ (I-II), as well as
* a __guest__ and an __open lecture__.


## Week 1: Course introducion
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

__Optional Reading__
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


## Week 3: Foundations II: Visualization design
This lecture talks about effective and ineffective visualization designs. It shows examples of ineffective and deceptive visualizations and describes _visualization guidelines_ that help designing effective visualiztions. The corresponding tutorial will exercise over common problems with visualizations and work towards proposing solutions via _sketching_, a powerful method introduced in the tutorial.

__[Slides]__
* [DataVis2020_2-VisualizationDesign.pdf](slides/DataVis2020_3-VisualizationDesign.pdf)
* [DataVis2020_2-Basic-Colors.pdf](slides/DataVis2020_3-Color.pdf)
  * [Video lecture: Color-1-Intro.mov](https://drive.google.com/open?id=1pa7e2j159ezb47ybCk4QAuKl4PGbeyl3)
  * [Video lecture: Color-2-Sequential.mov](https://drive.google.com/open?id=1Aie7pJk5t4x4KcetwGZeOdUzOwVPRXsI)
  * [Video lecture: Color-3-Diverging.mov](https://drive.google.com/open?id=15mxXWC66trJ5GaSpGg1_0GeSvRcVA8lz)
  * [Video lecture: Color-4-Categorical.mov](https://drive.google.com/open?id=1qzc0UfVimQH_7J7PrlfP7hHLWFxwoVVB)
  * [Video lecture: Color-5-Rainbow-colormap.pdf](https://drive.google.com/open?id=1bVXO6UG7scpb4o9U_nxfC5WGh0d6nex-)
  * [Video lecture: Color-6-Colorblindness.pdf](https://drive.google.com/open?id=168A7ZbWJZCh04YBYuGtRiykAPmK5zz25)
  * [Video lecture: Color-7-Extra.pdf](https://drive.google.com/open?id=1VaM-1Xu7KM3XwiG-k3UfHkr9C0f8LdmB)


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

<!--
## 3. Foundations III: Tools for data visualizations
This lecture overviews and introduces common software applications (tools) to help with both: data analysis and the creation of visualizations. We will overview tools for programming environments such as python (e.g., Seaborn) and javascript (e.g., D3), but also tools using common user interfaces (e.g, [Rawgraph](https://rawgraphs.io)], [Datawrapper](https://www.datawrapper.de)). The lecture will not teach _how_ to use these tools, but focus on a high-level overview of the many different tools and workflows exist to create data visualizations. 
-->

## Week 4. Techniques I: Statistical and Multivariate Data
_Techniques_ are fundamental to data visualizations and refer to specific visual representions (both terms are often used synonymously but 'technique' can include and heavy rely on _user interaction_). Knowing a wide range of techniques, their advantages and disadvantages will help finding appropriate techniques for a given problem as well as improving existing techniques and design novel techinques that solve some current problems. Some of the techniques discussed in Techniques I-III will seem familar to some of you, others will be entire unfamilar, yet. If a technique looks familar to you, it is worth looking twice, there might be things you did not know about this technique or assumed wrongly.

This first lecture will discuss techniques for statistical and multivariate data (distributions, data with many dimensions/attributes): _boxplots_, _error bars_, _histograms_, _starglyphs_, parallel coordinates plots_, and many more.

## 5. Techniques II: Trees, Networks, and Sets

This lecture covers visualizations techniques for data with relations: trees (hiearchies), networks (graphs), and sets. Techniques include _nodelink diagram_, _adjacency matrix_, _arc diagram_, _pivot graph_, _treemap_, and _up-set_.

## 6. Techniques III: Geographic and Temporal

This lecture covers visualizations techniques for geographical and temporal data. Techniques include _coropleth maps_, _chernoff faces_, _small multiples_, _space-time cubes_, and _animation_ techniques.

## 7. Advanced I: Storytelling and Communication

This lecture focuses on effective presentation techniques when using visualizations in e.g., infographics or presentations. Other presentation media can include videos, posters, and [datacomics](http://datacomics.net). The lecture investigates how presenting and talking with visualizations is different than using visualizations for exploring and analyzing data. Spoiler alert: "It's the audience, stupid!".

## 8. Advanced II: Evaluating visualization techniques
This lecture covers techniques to assess if a given visualization technique (existing or your own creation) is "successful". Successful is a broad term and refers to both effectiveness and efficiency in which a user or audience are supported in their analysis or understanding of the data. The lecture proposes five levels to check for success _Visibility_, _Readability_, _Understandability_, _Appropriateness_, _Truthfulness_. Evaluation methods involve a set of techniques from Human-Computer Interaction (HCI) such as _guidlines_,  _quantitative evaluation_, _qualitative visualization_, _user tracking_, _samples_, and _tasks_, and _statistical analysis_. 

## 9. Guest Lecture: TDB

## 10. Projcect consultation
This lecture slot is reserved to discuss you projects and any open question and topics you may have. During the course, I will keep a [document](https://docs.google.com/document/d/1aIW7J3aJc3nD1q1aBh_ejXzfFTz0TX2NrW-DMJiaLQQ/edit?usp=sharing) to collect suggesions of topics you would like to know more. I will prepare a lecture to talk about some selected topics). Use the document to anonymously suggest topics or pose questions and up-vote those of your fellows.

## 11. Project presentations
In order to give anyone an overview of the many greats works on Assignment 1, this lecture slot asks each group to present their work for about ~3min (depending on numbers of groups). Presentations and presentation quality will not be graded and this is a rather informal event to show and share your work with your fellows. Don't hestiate to offer suggestions for improvement for the final hand-in of [Assignment 2] and how your colleagues have done a specific visualization.
