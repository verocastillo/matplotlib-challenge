# matplotlib-challenge
Repository for my fifth homework using Matplotlib, where I report on the findings of a study performed by a pharmaceutical company.

**The case:**
I am working for Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego. It specializes in anti-cancer pharmaceuticals. The most recent study revolves around screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. 
I was tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. 

**The results:**
In my report, I cleaned the data for duplicates and formatted it to be able to be analyzed by pandas and matplotlib.
Using these tools, I created both dataframes and plots with pertinent information, such as generating summary statistics tables, analyze treatment regimes, get mice demographics, compare final tumor volumes and analyze drug efficacy in reducing tumor size. The results are attached in the respective jupyter notebook.

Some observations I got from the study (which are also attached to the notebook), were:
- There are treatment regimes with more or less measurements than others. This is not ideal, as in medical studies, one should be constant in how many measurements (samples) are taken from each group, in order for results to be conclusive.
- Looking at the 'Final Tumor Volume In Mice Across Treatments' plot, it can be seen that Capomulin and Ramicane have smaller final tumor volume measurements than their other two counterparts, which can be further studied in order to conclude that these two are more effective than others. Nevertheless, initial volume should be considered, and the decrease in tumor size should be measured for it to be 100% conclusive.
- In the final part dedicated to Capomulin, the general conclusion when looking at each mouse's tumor volume vs. time, it can be seen that the volume tends to decrease on this drug regimen. Moreover, there is a positive correlation between mouse weight and tumor volume: as the weight increases, the tumor volume tends to increase.