# 🎬 Movie Ratings Analysis

This project analyzes movie ratings from a dataset using Python and the Pandas and Matplotlib libraries.

- File Used: `movie_ratings.csv`
- Columns:
  - `Title`: Name of the movie
  - `Genre`: Type of genre (e.g., Action, Comedy, Horror)
  - `Rating`: IMDb-style rating from 0–10
  - `Year`: Release year of the movie

Project Goals
1. Calculate:
   - Average movie rating
   - Movies with ratings above 8.0
   - Highest-rated movies sorted by rating
2. Filter:
   - Only movies rated above 8.0
   - Only movies in the **Horror** genre
3. Categorize movies based on their rating:
   - `Excellent`: ≥ 9
   - `Great`: > 8 and < 9
   - `Good`: > 7 and < 8
   - `Average`: ≤ 7
4. Visualize:
   - A scatter plot of `Rating` vs. `Year`
   - A bar chart of average ratings per genre

Libraries Used
- `pandas` for data manipulation
- `matplotlib.pyplot` for data visualization

Visual Outputs
- **Scatter Plot**: Shows the correlation between release year and rating.
- **Bar Chart**: Displays the average rating for each genre.

