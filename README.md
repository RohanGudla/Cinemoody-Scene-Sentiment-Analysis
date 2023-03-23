Here's a condensed version of your content:

---

# MovieMood: A Mood-Based Movie Recommendation System

## Project Overview

MovieMood is a Python-based movie recommendation system that takes users' current emotions into account when suggesting movies. It offers a user-friendly Graphical User Interface (GUI) and uses text-retrieval techniques to provide tailored movie recommendations based on users' emotions.

## Emotion Associated with Genre

Users can choose from 10 different emotions, including positive emotions like "Happy" and "Excited" and negative emotions like "Sad" and "Fearful." Each emotion corresponds to a specific movie genre. For example, "Happy" is associated with Horror movies, while "Sad" is linked to Drama films.

## Application of Crawling

Movie information is scraped from two websites: IMDb and Rotten Tomatoes. Separate crawlers are used for each website to extract movie details. IMDb provides detailed information, while Rotten Tomatoes has a more straightforward structure.

## Ranking and Scoring

User rating scores from both IMDb and Rotten Tomatoes are considered. Ratings are converted to a 10-point scale for comparison. The number of ratings is also factored in using logistic regression to assign weightage to the final movie score.

## Presenting Movie Information

Recommended movies are displayed using `Treeview` in the GUI, providing details like movie length, maturity grading, cast, etc.

## "You May Also Like..."

The system recommends three similar movies based on a user's favorite movie, using Cosine Similarity analysis on movie summaries.

## Self-Evaluation

The project was equally divided between the team members, resulting in the successful completion of the mood-based movie recommender system. Additional features like cosine similarity and logistic regression were added for enhanced functionality.

## Environment Set-Up

Refer to `requirements.txt` for package information. You can install all packages at once using `$ pip install -r requirements.txt`. Ensure you use **Python 3**.

## How to Use

Activate the program through `main.py`. The program will start running, and the scraping process may take up to 30 seconds.

## Video Presentation

Watch the [YouTube presentation](https://youtu.be/DIIRPvu-ts0) for a visual overview.

---

Your project overview has been summarized for easier readability.