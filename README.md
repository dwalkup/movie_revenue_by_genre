GROUP MEMBERS:
  David Walkup, Carson Lloyd

PROJECT GOALS:
  We were provided the scenario "Microsoft wants to make movies but knows nothing about the industry. Explore the types of films doing well at the box office and provide insights toward what type of movie Microsoft should make."
  Initially, we thought to determine the movie genre with the highest revenue but were unable to obtain movie budget data within the allotted time. We changed our focus to answer the following questions: "What movie genre grossed the most at the box office?" and "Did the MPAA rating given to movies affect the box office gross?"

FINDINGS:
  Based on our analysis, Microsoft's studio-to-be should focus their efforts on one of three genre and rating combinations:
  1) A PG-13 rated action movie - these movies appear to be very popular, and a PG-13 rating allows for a large potential audience. Gross box office performance tends to be very strong.
  2) A PG rated animation - again, these movies appear to be very popular based on gross box office and a PG rating allows for a large potential audience.
  3) An R rated comedy - comedies perform well in the box office, compared to categories other than action movies. An R rating may limit the potential audience size, but was the MPAA rating that performed best among comedies in our analysis.
  
  On the surface, G rated animations looked like a good choice as well, but with only 10 of them in the set of 500 movies we analyzed, we chose not to recommend them.

DATA USED IN THIS PROJECT:
  The final dataset used in this project is named 'combined_movie_data_2010_to_2019.csv' in the data folder of this repository.
  The original data as acquired is split between two files, 'data/movies_2010_to_2014_data.csv' and 'data/moviedf15_19data.csv'. These were combined into the final dataset after aligning the columns in both sets of data to allow clean concatenation of the DataFrames.
  We scraped the website at IMDB.com for our data. The data we chose to use consists of the top 50 movies by box office gross released each year, starting with 2010.
