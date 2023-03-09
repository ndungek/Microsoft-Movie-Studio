# Microsoft Movie Studio EDA (Maureen Kitang'a)

This project is a part of the Data Science (DSF-FT) Course at Moringa School. The full project description can be found [here](https://moringa.instructure.com/courses/243/pages/phase-1-project-description?module_item_id=44802).


## Project Overview 

Following the creation of the new Microsoft Movie Studio, I have been charged with exploring 
what types of films are currently performing best at the box office. After utilizing the EDA process ,
the analysis identified the following:
  * The best month to release a movie is February.
  * The most-selling genre is Animation followed closely by Sci-Fi.
  * The best three directors are John Andreas Andersen , Robin Pront, David Delhoffen.


  ## 1. Business Problem

Microsoft has decided to venture in to the film industry by launching a new movie studio: **Microsoft Movie Studio**.
However, they are not sure where to start , because they don't have enough knowledge about the film industry.
I have been tasked with aiding the new head of Microsoft to study which films  are showing the best results at the box office, and translate my findings into actionable insights. There are many aspects that affect profitability of such an industry. 

I based my analysis on the following factors:
 * Total gross earnings
 * Genre
 * Release Date
 * Rating
 * Runtime
 * Directors
 * Studios(Competitors)


## 2. Data Understanding

I used three datasets from renowned film database websites: [Box Mojo](https://www.boxofficemojo.com/), [IMBD](https://www.imdb.com/) and [TMBD](https://www.themoviedb.org/)
 
Such data primarily comes from the years 2010-2019.
From the  [first dataset](https://www.boxofficemojo.com/) which is in .csv format, we have the movie titles, year, studio and revenue information of films that have been released and those are are yet to be released.With gross earnings being the target variable, the monetary data (domestic gross and foreign gross) columns are the main reason this dataset was selected. 

From the [second dataset](https://www.imdb.com/) which is in .db format, we have database with 8 tables containing different types of non-monetary information about films such as their genres, directors, writers and the ratings and more. This information will be used to understand the characteristics of the films that are currently performing the best at the box office.

From the [third dataset](https://www.themoviedb.org/) which is in .csv format, we have the popularity, original titles, votecount and release_date. The popularity column will be used to determine the films that are currently performing the best at the box office.



## 3. Methods

This project uses descriptive analytics to describe trends in the features of successful movies.

For all the datasets, I removed unnecessary columns, cleaned, and filtered all of the tables used. To make sure that the data we used was relevant to Microsoft's business question, we limited the data to only include movies released between 2010 - 2019 .

Data Preparation: I combined all the datasets and dropped the columns that I was not going to use for my analysis.
I focused on six perfomance metrics :
* Genre
* Release_Date
* Film/Movie
* Studio
* Rating
* Runtime

I finally decided to analyze some more data. I got the directors data loaded and determined the 20 best directors.
The above data was analyzed to produce this project's recommendations.


## Results
 
What Genres is the most profitable?
* Animation ,SciFi,Fantasy, Comedy and Family are the top five most profitable genres

![Alt text](images\Genres.png)



Which are the best months to release a movie?
* February seemed to leading with most gross earnings
* July was second, November was third
![Alt text](images\release_date.png)



Who are the best directors in the game?
* John Andreas Anderson, Robin Pront, David Delhoffen, Scott Armstrong and Brian Peter Falk.
![Alt text](images\directors.png)


Which competitor studios is leading in the industry?
* PW/D,BV, Sony,WB(NL) are the leading movie studios in terms of numbers and revenue.
![Alt text](images\studio.png)


Does the ratings of a movie really determine the gross earnings?
* Rating does not affect the gross earnings
![Alt text](images\ratings.png)


Does the runtime of a movie detemine its' popularity
![Alt text](images\runtime.png)


## Future Considerations
Further analyses could yield additional insights to improve recommendations for Microsoft's studio debut:

## For More Information
Please review the full analysis in the [Jupyter Notebook](https://github.com/ndungek/Microsoft-Movie-Studio-EDA/blob/main/index.ipynb) or the Presentation.

For any additional questions, please contact : ndungek66@gmail.com