# Movies-ETL
## Project Overview

The purpose of this project is to take raw movie data from Wikipedia and Kaggle and combine them into a functional database. This will be accomplished using Python to clean and transform the data and then it will moved into a PostgreSQL database. 

## Wikipedia Data
Due to the nature of Wikipedia it is not surprsing that much of the data pulled out of the raw .json is very messy. Each category such as budget, runtime, box office, etc all had the data entered in multiple different ways. We were able to use regular expressions to bring our data to a uniform format. 

## Kaggle Data
This data was much cleaner, but had much more missing information. What differneces in formatting we did have were cleaned up with regular expressions. We then merged the data together, primarily using the Wikipedia info to fill in for missing information from Kaggle. This allowed us to create a more complete picture and then move it into a PostgreSQL database. 
