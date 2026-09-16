# Assignment 2: Build onto an existing database

## 1. Original database
[IMDb Top 250 Movies Database](https://www.kaggle.com/datasets/rajugc/imdb-top-250-movies-dataset) 

## 2. Description of the original database
[IMDB Top 250 Movies.csv](https://github.com/user-attachments/files/32302939/IMDB.Top.250.Movies.csv)

The original database was created by Chidambara Raju G and published on Kaggle. It contains 250 highest-rated movies on IMDb as of 2021. The data was taken from IMDb and includes information such as the movie's rank, title, release year, IMDb rating, genre, runtime, budget, worldwide box office, cast, director, and writers. 
One important limitation of this data is that this is a snapshot of IMDb's rankings from 2021 rather than a current and updated ranking. IMDb's rankings change as users continue to rank movies, so the data isn't reflective of modern opinions. The database also represents IMDb's users' ratings rather than professional critics' opinions, so the data reflects audience ratings. Because the dataset was curated for educational purposes, it is also dependent on the information that was available on IMDb at the time it was collected.

## 3. Reporting question
How much Academy Award recognition did the movies at the top of IMDb's ranking receive, and where do IMDb's audience ratings and Oscar recognition differ?
The original database shows which movies are highly rated by IMDb users, but it does not include information about Academy Award nominations or wins. Adding the Oscar nominations and wins makes it possible to compare audience recognition on IMDb with recognition from the Academy Awards. 
This information could possibly be useful for an entertainment audience because a movie can be thought of very highly by audiences without having to receive many Oscars, while other highly rated movies have received extensive recognition from the Academy. For instance, *The Shawshank Redemption* was nominated for seven Academy Awards but did not win any, yet it is the highest ranked movie in the IMDb dataset. 

## 4. Expanded dataset
[Expanded IMDb/Oscar dataset](https://github.com/user-attachments/files/32303139/IMDB.Top.250.Movies.%2B.Academy.Awards.nominations.wins.csv)

I added two new fields to the original database: Oscar Nominations and Oscar Wins. I researched these fields using Academy of Motion Picture Arts and Sciences records. I also included an Oscar Source column with a source for each researched record, as well as a Notes column for information about noteworthy records. 

## 5. Difficult judgment calls/unusual records
The main judgment call I had to make was determining how to count Oscar nominations and wins. I counted each Academy Award category in which a movie was nominated and each category in which it won. I used the Academy's official records as opposed to relying on general movie websites to ensure accuracy. 
One unusual example is *The Shawshank Redemption*. While it is ranked extremely high on IMDb, it received seven Oscar nominations and no wins. The Academy's 1995 ceremony records list nominations for Best Picture, Actor in a Leading Role, Cinematography, Film Editing, etc. 
Another potential limitation is that Oscar recognition and IMDb ratings all measure different elements. IMDb ratings come directly from users, while Academy Awards are determined through the Academy's awards process. Therefore, the dataset can show differences between two types of recognition, but it cannot decide that one is a better measure of movie quality than the other. 

## 6. AI Disclosure
I did not use AI on this assignment. 
