# Performing EDA on Box Office Movies.

## Business Problem.

- Microsoft sees all the big companies creating original video content and they want to get in on the fun.**

- They have decided to create a new movie studio, but they don’t know anything about creating movies.**

- You are charged with exploring what types of films are currently doing the best at the box office.**

- You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.**

## Business Problem Solution.

- After analyzing the business problem, I have decided to determine which movies made the most profit at the box office and use the profit as a measure of the movies' performance.

- With that, I shall use the  **'movie_gross'** dataset ( availed by the institution, obtained through web scrapping) to gain insights that will offer solutions to the business problem.

- This dataset gives **information on the revenue generated from different movies in the time period 2010-2018.**

- My **aim** is to **perform exploratory data analysis** on the dataset **using the 'Python Programming Language'** on the **Jupyter Notebook IDE** and **draw meaningful insights** in regards to the **performance of the different movies** at the Box office.

## Dataset Overview and Transformation.

- The dataset contains **3387 records** and a total of **5 columns**, namely; 'title', 'studio','domestic_gross','foregn_gross', and 'year'.

- Upon inspection, the dataset contained null values of insignificant impact, thus **I dropped the null values**.

- I then **renamed the 'domestic gross' column to 'domestic gross ($) ' and the 'foreign gross' column to ' foreign gross ($) '**, and then formatted both columns to numerical values.

- I also **renamed the 'title' and 'year' columns to 'movie_title' and 'release year'** respectively. This is so as to make the column names more intuitive.

- Finally, I **capitalized all of the column names** .In addition, I ensured that all numerical values in the dataset would be displayed as float data type upon further computation.

  ## Performing EDA on the Cleaned and Transformed Dataset.

- I performed EDA on the clean and transformed dataset by:

     **1).** Obtaining **summary statistics** of the dataset. These statistics include the measures of central tendency and measures of dispersion of the dataset's numerical columns.
  
     **2).** Creating **two subset data frames from the original data frame and named them 'top_1_percent' and 'bottom_1_percent'** and then proceeded to visualize the subsets separately. The former data frame contains the top 1%  of movies in terms of revenue generation while the latter contains the bottom 1% of movies in terms of revenue generation. I obtained useful insights by comparing the similarities and differences between these two categories.
 
     **3).** I also **created and visualized a 'grouped_by_year' data frame** which is also a subset of the 'movie_gross' data frame. This data frame contains  numerical data, from the 'movie_gross' data frame, grouped in years. From the visualization, I was able to determine the general trend in movie revenue generation over the years.
 
     **4).** Lastly, I **generated a 'grouped_by_studio' data frame**,  which is also a subset of the 'movie_gross' data frame, and visualized it. This data set contains revenue generated from various studios over the selected time period. From this, I was able to identify studios that generated the most income and use this insight to ensure that marketing is more efficient and targeted.

## Insights Gained From Performing EDA& My Reccommendations To The Microsoft Team.

- After performing EDA on the 'movie_gross' dataset and making use of my domain knowledge, I have come to the following conclusions;

     **1).** The Microsoft team should primarily focus on creating movies that are bound to have a sequel. This is because, over the time period of 2010-2018, most of the top-performing movies are either prequels or sequels while the bottom performers are stand-alone movies. The team should also look into the genres of these top-performing movies so as to capitalize on these genre markets.

     **2).** The team should  majorly focus on creating movies that appeal to foreign markets. This is because, across the given time period, foreign gross revenue has been significantly higher than Domestic gross revenue. Still, on the same basis, the team should set aside a significantly higher marketing budget for foreign market advertisement in comparison to domestic market advertising.

     **3).** I would also recommend that the Microsoft team consider collaborating with the Top 10 ranked Studios( in terms of revenue generation) when running marketing campaigns. This is because these studios are more likely to have a wider audience reach and are frequented by top movie fanatics.

    **4).** Lastly, the team could investigate the cause of a spike in movie revenue generation from the year 2014 onwards. Might it be due to a change in movie graphics? Could it be due to a focus on a particular topic(s)? etc...From this, the team could obtain information to be used as a guide during movie production in order to ensure that their movies are top-ranking. (From the data availed, I am not able to perform this analysis).




