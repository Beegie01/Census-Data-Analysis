# Census-Data-Analysis

### OBJECTIVES
• Discover relevant insights through data analysis.<br>
• Reach a data-driven decision based on the derived insights.<br>
• Recommend to the local government the most beneficial way to invest the available public
resources (vacant plot of land, and funds).<br><br>

### NOTE
**Full version of this project report can be found [here](https://github.com/Beegie01/Census-Data-Analysis/blob/main/CENSUS%20PROJECT%20REPORT.pdf)**<br><br>

### DATA MUNGING
The original census dataset is a CSV (comma separated values) file containing 7,581 records and 11 
features. Each of its feature had a string datatype. Also, missing values, blank text, inconsistent values, 
and multiplicity of the same categorical values were noticed in some features. Steps taken to clean 
the data set (feature-by-feature) can be found in a [Jupyter Notebook file](https://github.com/Beegie01/Census-Data-Analysis/blob/main/Census_data_cleaning.ipynb) solely dedicated to data 
cleaning.<br><br>

### STATISTICAL OVERVIEW OF THE DATASET
**DESCRIPTIVE STATISTICS<br>**
![image](https://user-images.githubusercontent.com/76821049/174120259-fd23ac49-c952-4f51-86f2-5036ef32a73a.png)
The table above tells us:<br>
a. Street with the most houses is Wharf Wells (105 houses).<br>
b. House with the highest number of occupants is 27, Brightwater Drive (22 occupants).<br>
c. Single is the most common marital status (2,596). <br>
d. Females (3,946 of them) are more than males.<br>
e. Population is generally healthy (99.5%).<br>
f. Christianity is the major religion, practiced by 3,015 residents (40%).<br><br>

### ANALYSIS OF RESULTS
**1. AGE DISTRIBUTION**<br>
Average age of the population is 37 years (37 years for males, and 38 years for females). The [diagram](https://user-images.githubusercontent.com/76821049/174121262-44011dea-859a-4179-9a7b-1395160011a5.png) illustrates that this is a young population with over 70% still under 50 years. Over half the population (55.13%) are under 40 years old, which suggests an active and growing population to contribute economically to the town’s development.<br><br>
The population pyramid below illustrates, on the overall, a higher number of females than males. 15 to 19 years is the age bracket that has the highest male population, and ages 40 to 44 years has the highest female population. It can be said that the male population is younger than the females.<br>
![image](https://user-images.githubusercontent.com/76821049/174121673-ffdf2b79-d63a-4c0d-b70d-26a2e99bebdc.png)<br><br>
The illustration below reveals that from age 0 to 19 years, males are more than females. While from ages 20 to 59 years, females are visibly more. This could mean that females tend to live longer than males in this town, or that males tend to move to another town (emigration) as they grow older maybe for greener pastures. This should guide us when making gender-based decisions across age groups.<br>
![image](https://user-images.githubusercontent.com/76821049/174122024-4cbeda94-6592-42cc-b691-d037af391783.png)<br><br>


