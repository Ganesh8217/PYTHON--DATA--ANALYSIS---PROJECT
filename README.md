🎬 Netflix Data Analysis Using Python

(Exploratory Data Analysis on Netflix Titles Dataset)

This project performs an in-depth Exploratory Data Analysis (EDA) on the Netflix Titles Dataset using Python, 
Pandas, Matplotlib, Seaborn, and other essential data analysis tools. The analysis uncovers key insights related to Netflix’s content—its growth, 
genres, release trends, ratings, countries, and more, based on 8,807 titles from Movies and TV Shows.


7e23a6c8-cc65-4de2-ae76-0ae347c…

📌 Project Objective

To analyze the Netflix dataset and extract insights about:

📺 Distribution of Movies vs TV Shows

🌍 Country-wise content production

⭐ Content ratings breakdown

🎭 Most popular genres

🎬 Top directors

📈 Trends in content release over the years

🧼 Data cleaning, transformation, and preprocessing steps

📂 Dataset Overview

According to the dataset preview (Page 1–2) 

7e23a6c8-cc65-4de2-ae76-0ae347c…

:

Rows: 8,807

Columns: 12

Features include:

show_id

type (Movie / TV Show)

title

director

cast

country

date_added

release_year

rating

duration

genre/listed_in

description

🛠 Technologies & Libraries Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

🧹 Data Cleaning Steps

Based on Pages 3–8 of your notebook 

7e23a6c8-cc65-4de2-ae76-0ae347c…

:

Handled missing values in:

rating → filled with TV-MA

director, cast → filled with Unknown

country → filled with mode (United States)

Removed rows with missing:

date_added

duration

Converted:

date_added → datetime

Extracted new features: month, year

Renamed:

listed_in → genre

Extracted primary genre from comma-separated values

🔍 Key Analysis & Visualizations
1️⃣ Which year has the maximum releases?

From bar charts on pages 11–12:

2020 and 2019 had the highest number of releases.

2️⃣ Content Type Distribution

From Page 12:

Movies: 6128

TV Shows: 2666

Movies form the majority of the dataset.

3️⃣ Countries with the highest releases

From plots on Pages 13–14:

United States dominates both TV Shows and Movies.

Followed by India, United Kingdom, Japan, and Canada.

4️⃣ Most Common Content Ratings

According to Pages 15–16:

Most common TV show ratings: TV-MA, TV-14

Most common movie ratings: TV-MA, R, PG-13

5️⃣ Most Popular Genres

From Pages 17–20:

TV Shows:

International TV Shows

Crime TV Shows

British TV Shows

Docuseries

Movies:

Dramas

Comedies

Action & Adventure

Children & Family Movies

6️⃣ Overall Most Frequent Genre

Based on Page 20 graph:

Dramas

Comedies

Action & Adventure
are the most common genres.

7️⃣ Top 10 Directors

From Page 21:
Some of the most frequent directors include:

Rajiv Chilaka

Raul Campos

Marcus Raboy

Sunit Kumar

Cathy Garcia-Molina

Martin Scorsese

8️⃣ How content releases changed over the years

Graph on Page 22–23 shows:

Sharp increase in releases after 2010

Peak around 2018–2020

Minimal content before 2000

📈 Insights

Netflix experienced explosive growth between 2010 and 2020.

Movies dominate the platform’s catalog.

The US is the leading content producer.

TV-MA and TV-14 rating categories dominate, showing Netflix targets mature audiences.

Dramas and Comedies are the most popular genres on the platform.


👨‍💻 Author

Gollapalli Ganesh
Data Analyst | Python | SQL | Power BI |DATASCIENCE

⭐ Support

If you found this project useful, please ⭐ star the repository to support my work!
