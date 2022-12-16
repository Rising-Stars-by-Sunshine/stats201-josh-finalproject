# EXPLORING THE USE OF RANDOM FORESTS AND SUPPORT VECTOR MACHINES FOR COASTAL REAL ESTATE PRICE PREDICTION

## Project Information
* **Author**: Josh Manto, Data Science student from class of 2024, Duke Kunshan University
* **Instructor**: Prof: Luyao Zhang, Duke Kunshan University
* **Disclaimer**: Submissions to the Final Project for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
* **Acknowlegement**: Prof. Luyao Zhang guided the entire project through， Xin Ma (helped with the VM set up)，Yutong Quan for the insigtful peer review.
* **Github page**: [https://github.com/josh-ai2]

## Project Summary

**ABSTRACT: In this study, we explore the use of two popular machine learning algorithms, random forests and support vector machines, for predicting changes in coastline rent prices using sea level as a data source; our machine learning method is supervised. We compare the performance of these algorithms on a dataset of coastline rent prices and sea level data, and evaluate their ability to accurately forecast rent prices. Our results show that both algorithms produce similar predictions, with the random forest algorithm achieving slightly higher accuracy. We discuss the implications of these findings for the use of machine learning in real estate price prediction in one county in Wilmington, North Carolina. 

**RESEARCH QUESTION: How do random forests and support vector machines perform for predicting changes in coastline rent prices using sea level as a data source?

**METHODOLOGY: Compare the performance of the random forest and support vector machine algorithms, and discuss the implications of the results for the use of machine learning in predicting changes in coastline rent prices. Develop algorithm that will consistently make predictions according to up-to-date coastline data. 

**WHY IS MY RESEARCH IMPORTANT? ![image](https://github.com/Rising-Stars-by-Sunshine/stats201-josh-finalproject/blob/main/spotlight/figures/research_importance.png)

**CONTRIBUTION TO LITERATURE ![image](https://github.com/Rising-Stars-by-Sunshine/stats201-josh-finalproject/blob/main/spotlight/figures/Contribution_literature.png)

## Table of contents
* Data
* Code
* Spotlight
* More on the Author
* Reference


## Code
| Tables        | URL                                                |
| ------------- |:-------------:                                     |
| Process Data     | https://github.com/Rising-Stars-by-Sunshine/stats201-josh-finalproject/blob/main/code/Process_Data_ipynb_josh.ipynb |
| Analyze Data | https://github.com/Rising-Stars-by-Sunshine/stats201-josh-finalproject/blob/main/code/Prediction_Analyze_Data_Machine_Learning.ipynb |   



## Spotlight
#### Research Sumary Poster
![image](https://github.com/Rising-Stars-by-Sunshine/stats201-josh-finalproject/blob/main/spotlight/figures/FINAL%20PROJECT%20STATS%20201.png)
Generated using Canva

#### For Machine Learning Algorithms


![image](https://github.com/Rising-Stars-by-Sunshine/stats201-josh-finalproject/blob/main/spotlight/figures/ypred_main.png)
Linear regression

![image](https://github.com/Rising-Stars-by-Sunshine/stats201-josh-finalproject/blob/main/spotlight/figures/ypred2.png)
Random Forest Regression


         
## More about the Author

![image](https://media.licdn.com/dms/image/D4E03AQHj-zTr5p1BLA/profile-displayphoto-shrink_400_400/0/1669607219741?e=1676505600&v=beta&t=y7YIzZF6Vv_VIENiBKBA58pRupwZuXazTt_FMO0mWkM)

## Self-introduction

I am a co2024 data science student in Duke University and Duke Kunshan university. I have previous research interests in blockchain development, while my current research interet is on TinyML and IoT development. 

## Final-reflection

As I look back on my research work in machine learning, I am particularly proud of the progress I have made in the area of random forest algorithms.

Random forests are a popular method for supervised learning, and I have spent a significant amount of time studying and implementing them in various projects. One of the things that I find most interesting about random forests is their ability to handle large, complex datasets and make accurate predictions despite having a large number of features. The data that I used dated all the way back to 1984 for Wilmington's price index, same goes for SL (sea level) data in NC state , which dated back till 1975. I was able to clean through all this data to produce a [single databse] (https://github.com/Rising-Stars-by-Sunshine/stats201-josh-finalproject/blob/main/data/Queried_Data/final_processed_data.csv) where my Y variable is the price index for Wilmington and my X variable is the sea level rise. 

Overall, my research in the area of random forest algorithms has been very rewarding, and I am excited to continue exploring and pushing the boundaries of what is possible with these powerful machine learning techniques.


## References

U.S. Federal Housing Finance Agency. “All-Transactions House Price Index for Wilmington, NC (MSA).” FRED, Federal Reserve Bank of St. Louis. FRED, Federal Reserve Bank of St. Louis, July 1, 1984. https://fred.stlouisfed.org/series/ATNHPIUS48900Q.

“Sea Level Trends - NOAA Tides & Currents.” Accessed December 12, 2022. https://tidesandcurrents.noaa.gov/sltrends/sltrends_station.shtml?id=8658120.
