# Football_Delphi_Project


AIMS AND OBJECTIVES: 

Upon completion of this lab, each unique team in this dataset should have a record in the MongoDB instance containing the following information:

The name of the team
The total number of goals scored by the team during the 2011 season
The total number of wins the team earned during the 2011 season
A histogram visualization of the team's wins and losses for the 2011 season (store the visualization directly by assigning it to a variable)
The team's win percentage on days where it was raining during games in the 2011 season.
Getting the Weather Data
Refactor your code into functions or classes to make your code more modular, reusable, understandable, and maintainable. 

Dataset used in this project: https://www.kaggle.com/laudanum/footballdelphi


INTRODUCTION

Dataset consisting of historic match data for the German Bundesliga (1st and 2nd Division) as well as the English Premier League reaching back as far as 1993 up to 2016. Besides the mere information concerning goals scored and home/draw/away win the dataset also includes per site (team) data such as transfer value per team (pre-season), the squad strength,

SQL, OOP, API and NoSQL will be used to analyse the dataset, perform EDA, and request weather information during matches played in 2011. The latter will then be imported using NoSQL.


METHODOLOGY 

SQL was used to import the data to the jupyter notebook. the Exploratory data analysis was performed using a combination of SQL and Pandas to succesfully met the project criteria. Matplotlib and seaborn were used to plot the results.   

Information on the weather during the matches were requested from DarkSky using an API key. The information was then imported into the jupyter notebook. firstly, theere was an attempt to imported as a CSV file. However, this method did not seem as efficient as pulling the data straight from the source. 

MongoDB was used to store the findings of this project.


FINDINGS 

The findings in this project comprise the number of goals scored, the wins, draws and loses of each team in the 2011 season. The dataset included matches form the Bundesliga and the English Premier League. 

Ein Frankfurst scores the highest number of golas, whereas Hannover scored the least amount of goals (10). Morevover, Dortmund has the highest number of wins, followed by Bayer Munich. As for losses, FC Koin showed highest numbers. 

Please refer to the workbook for further information. 



CONCLUSION

This project aimed to analyse the dataset consisting of historic match data for the German Bundesliga (1st and 2nd Division) as well as the English Premier League during 2011, using specific progremming skills including APIs, databases, and Object-Oriented Programming to **_Extract, Transform, and Load_** (or **_ETL_**, for short) some data from a SQL database into a MongoDB Database.

SQL, OOP, API and NoSQL will be used to analyse the dataset, perform EDA, and request weather information during matches played in 2011. The latter will then be imported using NoSQL. Findings in this project included the number of goals scored, the wins, draws and loses of each team in the 2011 season. 

There were limitations encountered during the performance of this project. Such limitations included data request for weather, as it had many Null values and very few rainy days, by which to perform the requested analyses of wins and losses, as well as and draws of the teams on rainy days, thus arguably, the findings do not offer an accurate representaion in that regard.

Finally, MongoDB was to export the data analysis and figures. The answers to the first 3 questions were converted into a dictionary format and then into our NoSQL database.
