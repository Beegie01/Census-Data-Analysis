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

### 2. RETIRED
10% of the population (out of 45% who are above 40years old) are already retired, leaving the remaining 35% aging towards retirement. Depending on death rate, attention should be given to healthcare sector to cater for this aging category as they approach retirement.<br>
![image](https://user-images.githubusercontent.com/76821049/174123018-86d0ba8b-1484-4e3d-a1e6-22f7aa772bc1.png)<br><br>

### 3. UNEMPLOYMENT TREND
Overall, only 7% of the population is unemployed, indicative of an outstanding rate of employment and wealth generation. This also suggests that the economy is booming, and a low level of insecurity. Residents are mostly capable of quality healthcare and diet, which may be one of the reasons for the extremely low level of infirmity. However, it was observed that 53% of unemployed residents are between 25 and 44 years old.<br>
![image](https://user-images.githubusercontent.com/76821049/174123144-79c0ee17-a915-499b-99ac-1da0be3718e2.png)<br><br>
10% of the entire Muslim population are unemployed, which means that religion might be a factor for employment. One of the challenges that goes with being Muslim in a predominantly Christian society.<br>
![image](https://user-images.githubusercontent.com/76821049/174123631-75713a49-d01b-4e88-b2df-14c292b19285.png)<br><br>

### 3. RELIGIOUS AFFILIATIONS
![image](https://user-images.githubusercontent.com/76821049/174124279-3ab21c0b-d6a3-4d0f-b470-3b495df40237.png)<br>
Known Christians actually make up 40% of the entire population, while followers of other religions are only 3% of the population. Christianity is clearly the predominant religion in town. Therefore, it is expected that many of the laws and policies in place would be strongly influenced by Christian teachings and values.<br><br>
![image](https://user-images.githubusercontent.com/76821049/174124580-f9c734e4-1e30-41b6-b57a-78f9a2a13919.png)<br>
A significant number of followers of other religions are between the ages of 18 and 34 years, implying a growing population.<br><br>
![image](https://user-images.githubusercontent.com/76821049/174124843-5e229fcb-4532-4677-af56-44be708d5c0f.png)<br>
Among Christians, Catholics are the youngest with some followers above 78 years being outliers. While Methodists are the oldest. Known Catholics (10% of the population) have their own church, but Methodists, Baptists (7% of the population), and other Christian denominations (22% of the population) do not have a church and would have to commute to nearby towns regularly for fellowship. Same goes for all non-Christian worshippers (3% of population). Meaning, 33% of the population have to commute to their places of worship.<br><br>

### 4. MARRIED VS. DIVORCED
Generally, there is numeric balance between the population of wives and husbands.<br>
![image](https://user-images.githubusercontent.com/76821049/174125389-8a967b10-4603-4f42-990c-7799e2e92111.png)<br><br>
The above pyramid shows that husbands tend to get divorced at earlier ages before 45 years (62%) and wives tend to get divorced at 45 years and above (62%).<br>
![image](https://user-images.githubusercontent.com/76821049/174125499-8d81689d-1252-4b34-aced-fa6861994b97.png)<br><br>

### 5. OCCUPANCY LEVEL
![image](https://user-images.githubusercontent.com/76821049/174125836-b965dbeb-e4fe-4fc1-8cff-a7fe47cdfb3e.png)<br>
The occupancy level of the town implies its residents are mostly wealthy or financially comfortable, which is one of the benefits of its low unemployment rate. The town seems to be meant primarily for high class living.<br><br>

### 6. COMMUTERS
Commuters are university students and non-Catholic worshippers who have to travel out of town regularly for fellowship. The table below shows the number and percentage of the population who have to commute frequently for religious purposes. Non-Catholic Christians alone are about 30% of the population. This is 33% of the population.<br>
![image](https://user-images.githubusercontent.com/76821049/174126473-cfa57d3b-0a6e-4dbc-9a25-7f0102227563.png)<br>

### RECOMMENDATION
After detailed analysis, I recommend that a multi-purpose worship hall should be built on the vacant plot of land to serve as worship center for Methodists, Muslims, Sikh, Jews, and other non-Catholic followers. Worship days and time for each of the major religions differ. For instance, worship days for Muslims is primarily Friday, for Methodists and Baptists it’s Sunday (but they can do so at different times), while Jews primarily worship on Saturdays. Proper attention should be given to management and allocation of this important building, to ensure there is fairness and equity. And representatives from each religious parties should form part of this management. This can be an avenue to promote unity and religious tolerance in the town. This should be also boost the economy as more businesses opportunities will spring up in and around the worship center.<br><br>
Given the population is relatively young and healthy, 16% of the population are 60 years or older. And 35% are already above 40 years. Thus, I recommend investing in old-age care, like care homes, exercise centers for the ageing and elderly.
