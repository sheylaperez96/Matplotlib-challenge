# Pymaceuticals

## Background
Pymaceuticals recently began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer. As a senior data analyst at the company, I've been given acess to their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated with a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

In this repository, you'll find a jupyter notebook [pymaceuticals.ipynb] that contains tables and figures analyzing the study results.

## Observable Trends
- The sex distribution between the mice in the study is pretty even, with 51% males in the study and 49% females.
- Based on the boxplot, Capomulin and Ramicane seem to be the most effective treatments against SCC, as they resulted in the lowest median tumor volume at the end of the regimen. 
- Based on the results for the Capomulin regimen, there is a positive correlation between the weight of the mice and the average volume of their tumor. The correlation coefficient between the two variables is 0.84, which indicates a strong correlation (rvalue > 0.7). 