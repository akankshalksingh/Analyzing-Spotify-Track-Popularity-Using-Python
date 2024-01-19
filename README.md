# Analyzing Spotify Track Popularity Using Python

Music streaming services like Spotify have revolutionized how we discover and listen to music. With over 82 million tracks and 406 million users, Spotify offers invaluable insights into what makes songs popular. In this post, I’ll conduct an exploratory data analysis in Python to unravel what drives track popularity on Spotify.

## Project Overview:

For this analysis, I’ll use a dataset from Kaggle containing 232,725 tracks with 18 audio features including danceability, energy, loudness, speechiness, and more. My goal is to explore how these track attributes relate to popularity.


## Key Findings:

- Data Insights:
    - Top/bottom popular tracks by genre and era.
    - Genre distribution (dominated by pop and rap).
- Visualizations:
    - Distributions of key audio features (danceability, energy, loudness).
    - Correlation map showing relationships between features.
- Statistical Analysis:
    - Strong positive correlation between danceability and energy (upbeat songs).
    - Negative correlation of acousticness with energy and loudness (quieter, calmer songs).
- Regression Model:
    - Quantified impact of audio features on popularity:
        - Danceability and energy have positive coefficients, increasing popularity.
        - Acousticness has a negative coefficient, decreasing popularity.
    - Model explains 31% of popularity variance, indicating other influential factors.
  
## Conclusion

The analysis unveiled significant links between audio features and Spotify track popularity. While factors like danceability and energy boost a song's reach, music taste remains nuanced and unpredictable. While we can't craft guaranteed hits through data alone, this exploratory journey reveals valuable insights into what makes us groove and click "play." The soundtrack of our lives is richer and more complex than algorithms can fully capture, but by delving into its data, we gain a deeper appreciation for the captivating melodies that resonate with us.
