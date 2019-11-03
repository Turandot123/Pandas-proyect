# Pandas-Project

Insert information about project

Pandas-Project

Looking for SHARKS!

Insert information about project

A.Intro:

The project is about stablishing an initial hypothesis based on a data base and perform certain actions to the data base such as: cleaning, improving its content, applying statistical functions when required, etc. to be able to confirm the initial hypothesis or not

The data base corresponds to information related to records of shark attacks during a period of time which are hosted in the keggle website

Based on an initial rough assessment of the data base, my hypothesis is that Australia is the country were more shark attacks happen during the years of recording the info

B.How did the data base was manipulated?

1.Cleaning
1.1. Removing unnecessary information. Columns which do not serve to add relevant intel to the analysis for example sex, age or injury
1.2. Removing rows not filled (“NaN”) 
1.3. Removing information wrongly recorded. For example, in column year there is a year = to 55

2.Updating/Improving content 
2.1. Changing data which was wrongly added but necessary. For example the state of Florida is inserted twice with “Florida” and “Florida “. Thus, we have to manipulate the data base to convert these two rows into one which is called “Florida” 
2.2. Removing rows which are not possible to treat. Ex. In Column countries, there are rows which do not record attacks in countries but regions which correspond to more than one country such as North Atlantic. This data has been removed as well because it was not possible to create an attribution

C.Checking hypothesis 
Once the data base was ready to analyse, the count function was utilized to assess in which country during the years of observations, had more shark attacks. The country USA resulted as a winner instead of Australia

D.Going beyond validating the initial hypothesis 
After the hypothesis was tested and declined, I made a zoom on USA to assess the amount of attacks per state. I also used the library geopandas and downloaded from gis the file corresponding to the US to be able to locate the attacks and states in a map

https://www.arcgis.com/home/item.html?id=f7f805eb65eb4ab787a0a3e1116ca7e5
