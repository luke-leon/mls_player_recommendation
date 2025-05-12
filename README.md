# MLS Player Recommendation System

This project builds a player recommendation tool to help Major League Soccer (MLS) teams identify under-the-radar prospects that align with their current roster's playstyle and needs. The focus is on Toronto FC, but the methodology generalizes across clubs.

## Project Overview
- **Goal:** Recommend potential player signings based on similarity to high-performing players on the current roster.
- **Data Source:** Player performance data from domestic and international leagues
- **Approach:**
  - Engineered features from player stats to capture position, style, and impact.
  - Built a similarity-based recommendation engine to match target players to comparable prospects.
  - Visualized candidate players based on key metrics and team needs.

## Tools & Techniques
- **Python**: `pandas`, `scikit-learn`, `matplotlib`
- **Analytics**: Feature engineering, similarity scoring, clustering
- **Visualization**: Attribute radar charts and scatter plots for candidate comparison

## Files
- `mls_player_recommendation.ipynb`: Notebook with data cleaning, feature engineering, and player similarity model
- `slides.pdf`: Presentation summarizing the approach, visuals, and final recommendations

## Key Takeaways
- Demonstrated how data science can support smarter scouting decisions in professional sports.
- Built a scalable framework that can be reused across teams and leagues.
- Highlighted the value of similarity-based models in environments with complex decision tradeoffs.
