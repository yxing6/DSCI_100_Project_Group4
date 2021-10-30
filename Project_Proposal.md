## Project Proposal 


###   To:	  DSCI 100 Instructor: Trevor Campbell
### From:	  DSCI 100 Group 4: Naijide Anwaer, Maggie Ruan, Yun Xing 
### Date: 	November 05, 2021
###   Re:	  Project Proposal for rock properties analysis and rock type categorical prediction 


### Introduction

The purpose of this project proposal is to provide an overview of the rock petrophysical data process project. This proposal provides an introduction to the rock properties database, illustrates the preliminary exploratory data analysis, explains the methodology, and discusses the expected outcome of this project. This proposal aims to seek permission from the instruction team in order to carry the project into the next development stage. 

### Background 

•	Provide some relevant background information on the topic so that someone unfamiliar with it will be prepared to understand the rest of your proposal
•	Clearly state the question you will try to answer with your project
•	Identify and describe the dataset that will be used to answer the question


The Canadian Rock Physical Property Database (CRPPD) includes rock petrophysical measurements on over 20,000 observations collected during the last 40 years. Geographically ranging from the Canadian Precambrian Shield to the east coast to the Athabasca Sedimentary Basin towards west, this database contains nearly all types of rocks to be found across Canada. First released in 2018, this database is publicly accessible and can be reproduced for non-commercial purposes. 
The rock petrophysical properties available in this database are grain density, dry bulk density, saturated bulk density, porosity, magnetic susceptibility, natural remanent magnetization, Koenigsberger ratio (the proportion of remanent magnetization relative to induced magnetization), electric resistivity and induced polarization chargeability. In sample type, observations are categorized into outcrop, subcrop, hand sample, and borehole sample. In rock type, observations are categorized into the three fundamental rock types: igneous, sedimentary, and metamorphic, then sub-categorized into basalt, diorite, granite, sandstone, etc. 
The group intends to study the relationship between the rock petrophysical measurements and three fundamental rock types, and to answer a classification problem. With certain kinds of physical properties data, whether the rock will be igneous, sedimentary, or metamorphic. The classifier model will be useful in the situation where the physical properties data are available while the rock type is unclassified. The example of this will be in diamond drillholes and not all the rock core beneath the ground is recovered and brought up to the surface. As a result, the group decided to perform the data analysis with the focus on data categorized under sample type borehole. 



### Preliminary Analysis
•	Demonstrate that the dataset can be read from the web into R 
•	Clean and wrangle your data into a tidy format
•	Using only training data, summarize the data in at least one table (this is exploratory data analysis). An example of a useful table could be one that reports the number of observations in each class, the means of the predictor variables you plan to use in your analysis and how many rows have missing data. 
•	Using only training data, visualize the data with at least one plot relevant to the analysis you plan to do (this is exploratory data analysis). An example of a useful visualization could be one that compares the distributions of each of the predictor variables you plan to use in your analysis.


### Methodology
•	Explain how you will conduct either your data analysis and which variables/columns you will use. Note - you do not need to use all variables/columns that exist in the raw data set. In fact, that's often not a good idea. For each variable think: is this a useful variable for prediction?
•	Describe at least one way that you will visualize the results


### Result 

•	Expected outcomes and significance:
o	What do you expect to find?
o	What impact could such findings have?
o	What future questions could this lead to?

### Conclusion


### References

Enkin, R.J., 2018. Canadian rock physical property database: first public release; Geological Survey of Canada, Open File 8460, 1 .zip file. https://doi.org/10.4095/313389




### Appendix A Time Tracking 

October 19:
Initial group meeting - 1hr 
October 26: 
group meeting to discuss dataset – 1 hr 
October 29: 
Yun Xing - initial commit on project proposal and gathered background info for team members - 1.5 hrs.
October 30: 
Meeting: Yun and Maggie, discuss tasks to do. 
Yun Xing: proposal introduction – 2hr. 
Maggie Ruan: try downloading zip file on web, unzip and being it to R – 2hr


