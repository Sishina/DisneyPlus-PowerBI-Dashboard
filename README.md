# DisneyPlus-PowerBI-Dashboard
An interactive Power BI dashboard analyzing Disney Plus Movies. This project explores IMDb ratings, movie genres, and yearly trends using data cleaning and DAX formulas. It helps to visualize the top rated films and compare performance against targets. Includes the Excel dataset and the .pbix dashboard file.
### 1.Project Overview
The goal of this project is to analyze Disney Plus Shows data using Excel and Power BI. I created a dashboard to show charts, important details like ratings, genres, and release years.
### 2.Tools Used
	* Microsoft Excel
 	* Power BI
### 3. Dataset
  Source: Disney plus Shows data. 
  Data Contains: 19 Columns and 21 Rows. The Column names are Imdb id, Title, Plot, Type, Rated, Year, released at, Added at, Runtime, Genre, Director, Writer,      Actors, Language, Country, Awards, Metascore, Imdb_rating, Imdb_votes.
### 4. Steps Followed
	*  Cleaned the data using Excel and Power Query.
	*  I replaced missing values with ‘Unknown’. I changed Date column into Date format. Then I changed the runtime column from text to numbers.
	*  Created a ‘Rating Status’ column using Power Query to categorize movies as Excellent, Good, or Average based on their IMDb rating  scores. 
	* Used Excel formulas and Pivot Tables for basic analysis.
	* Imported the data into Power BI.
	* Built dashboards using charts, slicers and KPIs.
	* I added "Apply all slicers" and "Clear all slicers" buttons to make it easy to use.
 ### Data Modeling & DAX Measures
	* Average imdb rating =AVERAGE(disney plus shows11[imdb_rating])
	*	Top Rating Movie = MAX(disney_plus_shows11[imdb_rating])
	*	Target Rating=9
### 5. Key Insights
  	a. Animation and Adventure movies are the most popular in this data.
	b. Movie ratings generally reached a high point around 1992(Aladdin's Rating is 8.0).
	c. Aladdin is one of the most popular films people like(imdb-votes-356283).
### 6. Screenshots
<img width="1212" height="768" alt="Screenshot 2026-04-02 222917" src="https://github.com/user-attachments/assets/9977b037-60aa-4c39-9d10-691d0feb2bc6" />
<img width="1138" height="638" alt="Screenshot 2026-04-02 223016" src="https://github.com/user-attachments/assets/c64a1131-c86b-4aff-86a2-ece24bc425b2" />

### 7. Files included
  	* Cleaned Data of Disney plus shows.xlsx - Cleaned dataset of Disney Plus movies.
 	* Dashboard of Disney plus Shows.pbix - Power BI dashboard file with all visualizations.
	* README.md - Project Description
 
### 8. How to use
	*	Open ‘Disney plus shows’ data.xlsx to see how the movie data was cleaned and organized.
	*	Open ‘Disney plus shows’ Dashboard.pbix in Power BI Desktop to see the charts and graphs.
	*	Use slicers (Rating status and Country) to filter the dashboard and see specific movie details.
	*	Click on Apply all slicers to update all visuals at once.
	
# Conclusion
The final dashboard is a clear and colourful tool. It helps anyone quickly see which movies on Disney Plus have the best ratings and which genres are the most common.
