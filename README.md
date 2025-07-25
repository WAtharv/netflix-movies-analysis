
Netflix Movies Analysis

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)

=======================

A data analysis project exploring trends and insights in Netflix movies using Python and Pandas. This project focuses on understanding popular genres, release years, movie durations, and other key attributes to derive meaningful patterns from Netflix's catalog.

Project Structure
-----------------
netflix-movies-analysis/
├── mymoviedb.csv        # Main dataset used for analysis
├── movie_analysis.ipynb    # Jupyter notebook with all analysis and visualizations
├── .gitignore                # Files and directories ignored by Git
├── README.txt                # Project documentation (this file)

Features
--------
- Data cleaning and preprocessing using Pandas
- Analysis by year, genre, type, and duration
- Visualizations using Matplotlib & Seaborn
- Insights on trends, most popular content, and content types

Technologies Used
-----------------
- Python 3.10
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

Dataset
-------
- Source: Netflix Movies Dataset on Kaggle
- File: mymoviedb.csv
- Description: Contains data about Netflix titles including 	Release_Date,Title,Overview,Popularity ,Vote_Count,	Vote_Average,	Original_Language,	Genre,	Poster_Url

Getting Started
---------------
1. Clone the Repository
   git clone https://github.com/WAtharv/netflix-movies-analysis.git
   cd netflix-movies-analysis

2. Create & Activate Virtual Environment (Optional but Recommended)
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. Install Dependencies
   pip install -r requirements.txt

   If you don't have a requirements.txt, you can create one with:
   pip freeze > requirements.txt

4. Run the Notebook
   jupyter notebook movie_analysis.ipynb

Key Questions & Insights (with Visualizations)
---------------------------------------------


Netflix is an American subscription-based video-on-demand streaming service that delivers a wide
variety of TV shows, movies, documentaries, anime, and original content across multiple genres. 
Founded in 1997 by Reed Hastings and Marc Randolph in Scotts Valley, California, it initially 
operated as a DVD-by-mail rental service before transitioning to streaming in 2007. As of 2025, 
Netflix is the world’s most-subscribed streaming platform, with over 300 million paid memberships 
across more than 190 countries, offering content in multiple languages on internet-connected 
devices such as smartphones, tablets, smart TVs, and gaming consoles

The following analytical questions were explored and visualized in the notebook:

1. What is the most frequent genre of movies released on Netflix?
   ✔️ Visualized using a cat plot from genre counts.

2. Which movie has the highest average votes (vote_avg)?
   ✔️ Identified the movie with the highest average votes and plotted comparative vote averages.

3. What movie got the highest popularity? What's its genre?
   ✔️ 	Release_Date	Title	        Popularity	Vote_Count	Vote_Average	Genre
0	2021	Spider-Man: No Way Home	5083.954	8940	         popular	Action
1	2021	Spider-Man: No Way Home	5083.954	8940	         popular	Adventure
2	2021	Spider-Man: No Way Home	5083.954	8940	         popular	Science Fiction
        summarized in a tabular form 

4. What movie got the lowest popularity? What's its genre?
   ✔️ summarized into a tabular form 

5. Which year has the most released movies on Netflix?
   ✔️ Visualized using a hist plot showing count of movies per release year.

All answers are backed by visual graphs created using Matplotlib/Seaborn in the notebook Netflix_Analysis.ipynb.

License
-------
This project is licensed under the MIT License. You are free to use, modify, and distribute it for personal or commercial purposes.

Author
------
WAtharv .
GitHub Profile: https://github.com/WAtharv
Open to collaboration and feedback!

Acknowledgements
----------------
- Netflix for the idea
- Kaggle for the dataset
- The Python open-source community
