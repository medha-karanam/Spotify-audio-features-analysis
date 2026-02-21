## What Drives Song Popularity?
### An Exploratory Business Analytics Study of Spotify Audio Features
### Project Overview:
This project investigates whether intrinsic audio features — such as energy, danceability, valence, tempo, and loudness, are associated with track popularity on Spotify.

The goal was to evaluate whether audio characteristics alone can serve as meaningful indicators of commercial success, and to assess their potential value for recommendation systems, playlist strategy, and music content optimization.

### Tools & Technologies 
- SQL : Data aggregation and feature segmentation
- Python (Pandas, Seaborn, Matplotlib) : Data analysis & visualization
- Jupyter Notebook : Analytical workflow
- Git & GitHub : Version control

### Analytical Workflow
1. SQL Data Aggregation
- Calculated total track count
- Computed average feature values
- Aggregated popularity across feature buckets
2. Exploratory Visualization
- Initial line plots to inspect feature relationships
- Reflection on limitations of sequential visualization for non-temporal data
3. Correlation Analysis
- Generated a correlation heatmap across audio features and popularity
- Identified relative strength of linear relationships
4. Scatter Plots with Regression Lines
- Examined dispersion patterns
- Evaluated trend strength visually

### Key Findings
- No audio feature demonstrated a strong linear relationship with track popularity.
- Danceability and loudness showed the highest relative correlations (r ≈ 0.05 and r ≈ 0.04), though these associations were minimal.
- Scatter plots confirmed substantial variance in popularity across all feature levels.
- These findings suggest that audio characteristics alone are insufficient predictors of streaming success.

### Business Implications 
The weak correlations indicate that track popularity is likely influenced more heavily by external and contextual factors such as:
- Artist reputation
- Playlist placement
- Marketing efforts
- Social media exposure
- Listener behavior patterns
For streaming platforms and music marketers, this suggests that recommendation systems and promotional strategies should incorporate behavioral and contextual data rather than relying solely on intrinsic audio attributes.

### Future Improvements
- Incorporate artist-level and playlist-level metadata
- Explore interaction effects between audio features
- Implement classification models to predict top-performing tracks
- Test non-linear models to capture more complex relationships
