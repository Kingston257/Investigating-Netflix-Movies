# Investigating Netflix Movies

## Project Context
![Movie popcorn on red background](redpopcorn.jpg)

**Netflix**! What started in 1997 as a DVD rental service has since exploded into one of the largest entertainment and media companies.

Given the large number of movies and series available on the platform, it is a perfect opportunity to flex one's exploratory data analysis skills and dive into the entertainment industry. Our friend, Tom has also been brushing up on his Python skills and has taken a first crack at a CSV file containing Netflix data. He believes that the average duration of movies has been declining. Using our friend's initial research, I'll delve into the Netflix data to determine whether movie lengths are actually getting shorter and explain some of the contributing factors, if any.

## The data
The dataset [netflix_data](netflix_data.csv) containing the following table details, column names and descriptions:

| Column | Description |
|--------|-------------|
| `show_id` | The ID of the show |
| `type` | Type of show |
| `title` | Title of the show |
| `director` | Director of the show |
| `cast` | Cast of the show |
| `country` | Country of origin |
| `date_added` | Date added to Netflix |
| `release_year` | Year of Netflix release |
| `duration` | Duration of the show in minutes |
| `description` | Description of the show |
| `genre` | Show genre |

## Objectives
- To confirm if movies are getting shorter in duration over the years.
- To find out and explain possible reasons.

## Project Activities
Exploratory Data Analysis: [View Code](notebook.ipynb)
- Subsetting and filtering Dataframe
- Visualization
- Looping and iteration

## Key Insights
- The argument that Netflix movies have gotten shorter over time was, in fact, wrong.
- A look at the distribution of duration of movies from 1990 to 1999 shows a peak frequent duration of 100 minutes.
