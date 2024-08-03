# IMDB-Video-Games-Dive-Deep-using-SQL

This project involves analyzing video game data obtained from IMDb. The analysis is conducted using SQL queries within a Python environment, utilizing SQLite as the database engine. The goal is to extract meaningful insights about video games, such as release patterns, ratings, genres, and more.

## Project Overview

The notebook is designed to interact with a dataset of video games, which includes details like:

- **Name**: The title of the game.
- **URL**: Link to the IMDb page of the game.
- **Year**: Release year of the game.
- **Certificate**: Age certification (e.g., E, T, M).
- **Rating**: IMDb rating.
- **Votes**: Number of votes the game has received on IMDb.
- **Plot**: A brief description of the game's plot.
- **Genres**: Boolean indicators for various genres (e.g., Action, Adventure, Comedy).

## Key Features

- **SQL Queries**: The notebook includes several SQL queries that retrieve specific data subsets from the database. For instance, it counts the number of Spider-Man games released within different time periods.
- **Data Analysis**: The extracted data is used to perform analysis and gain insights into trends and patterns in video game releases.
- **Data Visualization**: Although not covered in this draft, the project could be extended to include visualizations of the queried data for better understanding and presentation.

## Getting Started

### Prerequisites

To run the notebook, you'll need the following:

- **Python 3.x** installed.
- **SQLite3**: The project uses SQLite as the database engine.
- **Pandas**: For data manipulation and analysis.
- **Jupyter Notebook**: To run the `.ipynb` file interactively.

You can install the required Python packages using pip:

```bash
pip install pandas sqlite3
```

### Running the Notebook
`
1. Navigate to the project directory:
   ```bash
   cd imdb-video-games-sql-analysis
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open the `IMDB Video Games Dive Deep using SQL.ipynb` file and run the cells to execute the analysis.

## Project Structure

- `IMDB Video Games Dive Deep using SQL.ipynb`: The main Jupyter Notebook containing the analysis.
- `data/`: A directory where you should place your database file (e.g., `videogame.db`).

## Contributions

Contributions are welcome! If you have any suggestions, improvements, or additional queries to include, feel free to fork this repository and submit a pull request.

## Acknowledgements

- IMDb for providing the video game data.
- The Python community for providing essential libraries like Pandas and SQLite.
