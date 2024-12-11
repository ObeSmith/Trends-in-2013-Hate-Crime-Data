# Trends-in-2013-Hate-Crime-Data
This repository includes analysis performed on 2013 hate crime data. The dataset was retrieved from this Github page: https://github.com/emorisse/FBI-Hate-Crime-Statistics/blob/master/2013/README.md. 

The dataset on the above Github page was cleaned in the following ways: 
- Data subset created which included only information from the "Cities" agency type.
- A 'Region' column created which filtered the states into eight regions based on the Bureau of Economic Development’s Region division. 
New England
Mideast
Great Lakes
Plains 
Southeast
Southwest 
Rocky Mountains 
Far West
- A 'City Size' column created organizing the population of different cities into different categories of city size. 
Very Small Towns: Population < 2,500
Small Towns: 2,500 – 9,999
Small Cities: 10,000 – 49,999
Mid-Sized Cities: 50,000 – 249,999
Large Cities: 250,000 – 999,999
Metropolitan Areas: 1,000,000+
- Furthermore, to answer the third research question, the data subset was pivoted into long version condensing all hate crimes into one column and all the quarters into one column.

Please note the distinction between the files in this repository: 
- "HateCrimeData.GitHub.Rmd" -> This file is the entire RMD file that the data cleaning and analysis was performed on.
- "HateCrimeDataAnalysisandResearchQuestions" -> This file hides the data cleaning section to increase easy viewing on GitHub of the research question/analysis section.
- "HateCrimeSubset.xlsx" -> This file is the subset created according to the metrics above.
- "PivotedLongerHateCrimeSubset.xlsx" -> This file is the pivoted longer subset used in Research Question 2 and described above.
- "Trendsin2013HateCrimeDataCleaning" -> This file hides the data analysis section and includes only the data cleaning portion for ease of accessibility. 

