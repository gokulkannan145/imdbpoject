📅 Project Introduction

Navigating through the vast ocean of new movie releases can be overwhelming. This project automates the process of extracting and analyzing movie data from IMDb for the year 2024, focusing on five key genres. The end goal is an interactive, user-friendly dashboard that allows users to explore patterns, trends, and top performers in the movie industry.

🛠️ Technologies Used

Python: Data handling with Pandas; visualizations with Seaborn, Matplotlib, and Plotly; SQL operations with SQLAlchemy.

Selenium: Web scraping automation.

MySQL: Database creation and data storage.

Streamlit: Building the interactive dashboard.

⚡ Project Workflow

1. Web Scraping

Utilized Selenium to scrape IMDb pages, collecting essential metadata for each movie, including:

Title

Genre

IMDb Rating

Duration

Number of Votes

The scraper automates navigation through genre-specific pages and saves the results into a CSV file.

2. Data Cleaning & Preprocessing

Using Pandas, the collected data was cleaned, structured, and transformed for effective analysis and visualization.

3. Database Management

Created a MySQL database (imdb) with a table named imdb_2024. Data was seamlessly pushed from Python into MySQL using MySQL Connector.

4. Dashboard Development

Built a fully interactive dashboard using Streamlit, featuring:

Sidebar filters for Genre, Rating, Votes, and Duration.

Dynamic charts powered by Plotly, Seaborn, and Matplotlib.

📊 Key Features of the Dashboard

🏅 Top 10 Movies 

📊 Genre Analysis

⏱️ Average Duration by Genre

🗳️ Voting Trends by Genres

🎥Genre based Rating

⭐ Rating Distribution 

📈 Ratings vs Votes Correlation

🥧 Most Popular Genres by Voting

🎞️ Best Movies per Genre Table

Each visualization is designed to answer specific analytical questions, offering both high-level overviews and deep dives into the data.

📂 Repository Structure

├── GUVI.ipynb              # Web scraping and data cleaning notebook
├── imdb.py          # Streamlit app script
├── IMDB_movies.csv # Final cleaned dataset
└── README.md               # Project documentation (this file)

👋 Acknowledgements

IMDb for providing the movie data.

Open-source libraries and their contributors who made this project possible.

📧 Contact

For any questions, suggestions, or collaborations, feel free to reach out through GitHub Issues or connect with me via LinkedIn!

www.linkedin.com/in/santhosh-govindarajan-5903b4151/




