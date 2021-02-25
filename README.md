<p align="center">
  <a href="" rel="noopener">
 <img width=700px height=500px src="images/logo.PNG" alt="Project logo"></a>
</p>

<h3 align="center">WA High School</h3>

<div align="center">

</div>

---

<p align="center">  An analysis of Western Australia's High Schools rankings
    <br> 
</p>

## 📝 Table of Contents

- [Team](#Team)
- [About](#about)
- [Getting Started](#getting_started)
- [Visualizations](#visualizations)
- [Acknowledgements](#acknowledgement)


## 🧐 Team <a name = "Team"></a>
•	Rye Capati
•	Parastoo Razavi


## 🧐 About <a name = "about"></a>
**Description:**
Analysis of Western Australia's High Schools rankings based on ATAR, NAPLAN, & ICSEA.<br>
Data clean-up:
1.	Merging data from various datasets
2.	Check for duplication
3.	Check for invalid value
4.	Make sure the data frame is consistent for all the data set.
5.	Make sure no rows are accidentally deleted


**Summary:**
For much of human history, education has served an important purpose, ensuring we have the tools to survive. People need jobs to eat and to have jobs, they need to learn how to work.
Education has been an essential part of every society. Education shows us the importance of hard work and, at the same time, helps us grow and develop.
In this project, we analyse the rankings of High Schools in Western Australia based on 3 factors.
- Median ATAR scores of Year 12 students per school 
- NAPLAN scores of Year 9 students per school 
- ICSEA scores per school

There are 193 High Schools with 103,198 enrolled High Shool students included in our 2016-2020 dataset.
<br>


**Limitation and Challenges:**
- There is no single source of information or centralized dataset with regards to schools information.
- Yearly ATAR & NAPLAN scores per school are not publicly or readily available online. 
- Not all schools are present per year in our dataset (eg. unavailable data or school/s closing) 
- Some schools change their name which affects the comparison of the data. 
- School name varies per dataset (eg. format of school name)
<br>


## 🏁 Getting Started <a name = "getting_started"></a>

**Questions to Answer:** <br>
1.	What are the top 10 countries with the largest population?
2.	What is the percentage of the top 10 countries compared to the rest of the world?
3.	What are the top 10 cities with the largest population?
4.  Is the largest populated city located in the largest populated country in the world?
5.	Predicted population from 2020 to 2050 (eg. Australia)?


## ✍️ Visualizations <a name = "visualizations"></a>

* World map with 2020 country population details. 
![Global_Map](images/global_map.PNG)

* Top 10 Countries & Top 10 cities in 2020. 
![top_10](images/top_10.PNG)

* Top 10 Countries vs World Population ratio in 2020. 
![population_ratio](images/population_ratio.PNG)

* Australia population actual & prediction. 
![au_population](images/australia_population.PNG)

* Australia sex ratio. 
![au_sex_ration](images/australia_sex_ratio.PNG)

* Australia birth rate. 
![au_birthrate](images/australia_birthrate.PNG)

* Australia death rate. 
![au_deathrate](images/australia_deathrate.PNG)

* Countries population actual &prediction. 
![country_table](images/country_table.PNG)

* Cities population in 2019 & 2020. 
![cities_table](images/city_table.PNG)

* API data. 
![api](images/api.PNG)

## 🎉 Acknowledgements <a name = "acknowledgement"></a>
- UWA Data Science
- Data source (scraped): https://worldpopulationreview.com
- Data source (scraped): https://www.iban.com/country-codes
- Data source (csv): https://datacatalog.worldbank.org
- Data source (geojson download): https://github.com/johan/world.geo.json/blob/master/countries.geo.json
