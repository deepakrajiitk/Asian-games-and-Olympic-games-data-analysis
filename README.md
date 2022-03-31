# Asian-games-and-Olympic-games-data-analysis
## Abstract
Asian games and Olympic games are very similar to each other in terms of sport events. But
only Asian athletes are common in both. There are various insights that can be drawn from these
historic sports data. Our work intends to extract this historic data using web scraping technique using
Beautiful Soup python package. After data extraction, this work intends to extract various insights
from this historic data using data mining techniques. Finally, our work takes an intersection of both
Asian games data and Olympic games data and carries out a comparative analysis on this dataset.
Visual insights created after data mining process are deployed on a web app for better user interface

## Files Included
- CSV files are in Datasets folder
- 15 ipynb notebooks are in Jupyter Notebooks folder
- main.py and helper.py are in Streamlit Files folder
- report(pdf) is in Project Report folder
- presentation(ppt) is in Presentation folder
- Web Scraping folder contains the jupyter notebooks in which we have written code to scrape the data

## Libraries Used
- [Numpy] - For performing arithmetic operations
- [Pandas] - For Datasets handling
- [Matplotlib] - For plotting graphs and visualizations
- [Seaborn] - For plotting graphs and visualizations
- [Streamlit] - We have used this library to make website for better analysis and visualization of our project.

## Datasets
| File Name | Description |
| ------ | ------ |
| Medal_List_Asian.csv | This file contains info about the number of medals won country wise and sports wise in Asian Games. |
| Medal_List_Olympics.csv | This file contains info about the number of medals won country wise and sports wise in Olympics Games. |
| Player_Medal_List_Asian | This file contains info about players that won medals sports wise in Asian games. |
| Player_Medal_List_Olympics | This file contains info about players that won medals sports wise in Olympics games. |

## Code Files
| File Name | Description |
| ------ | ------ |
| main.py |This file contains the code that we have written inorder to design the frontend of our website and also in this file we have imported the helper.py. |
| helper.py | This file contains the different functions that we have implemented in our project.|
|Q1.ipynb |Code that performs the analysis of medal counts of different countries and different years. |
|Q2.ipynb |Code that performs the analysis of percentage medals won by different countries in different years and overall. |
|Q3.ipynb |Code that performs the analysis of number of medals won by countries sports wise and overall. |
|Q4.ipynb |Code that performs the analysis of number of medals won by countries as host and non-host countries. |
|Q5.ipynb |Code that determines the top athletes in terms of number of medals won for each country. |
|Q6.ipynb |Code that determines the top athlete sports wise for each country. |
|Q7.ipynb |Code that performs the gender wise analysis of number of medals won by countries in each year and overall. |
|Q8.ipynb |Code that performs the analysis of number of medals won by countries in team sports vs individual sports. |
|Q9.ipynb |Code that performs the analysis of the athletes that won medal in asian games and also in immediate next olympic games. |
|Q10.ipynb |Code that performs the detailed analysis of countries and players who never won a medal(Gold,silver or bronze) and also analysis of players who won in Asian but not in Olympics and vice versa.  |
|Q11.ipynb |Code that performs the detailed analysis of India in both Asian and Olympic games. |
|Q12.ipynb |Code that determines the players who won medals in both Asian and Olympic games. |
|Q13.ipynb | Code that finds the countries that have won atleast one medal in every sport in a particular year.|
|Q14.ipynb |Code that finds Recession year for a country(i.e. Country that perform better initially but after some time its performance drops). |
|Q15.ipynb |Code that finds year or sport in which country won minimum(maximum) medals(gold,silver,bronze separately). |

We have used Streamlit to build a website and have also deployed our code. 
Here is the link to our website :- https://share.streamlit.io/divyansh009/dmprojectgrp10/main/main.py

If you wish to look at the analysis by running our code in a local host, then do the same by running the command "streamlit run main.py" by making 
"g10-project\Streamlit Files" as the working directory.

[Numpy]: <https://numpy.org/>
[Pandas]: <https://pandas.pydata.org/>
[Matplotlib]: <https://matplotlib.org/>
[Seaborn]: <https://seaborn.pydata.org/>
[Streamlit]: <https://streamlit.io/>
