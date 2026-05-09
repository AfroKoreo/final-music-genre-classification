# final-music-genre-classification
This project explores music genre classification using the Free Music Archive (FMA) metadata and feature dataset. The goal is to predict the top-level genre of a track from precomputed audio features.

For the final project, I compared two existing machine learning methods: multinomial logistic regression and k-nearest neighbors (KNN). I also introduced small adaptations by selecting a subset of genres, balancing the data with downsampling, standardizing features, and tuning the value of k for KNN.

Using a subset of 6,746 tracks across 8 genres and 518 audio features, logistic regression achieved a test accuracy of about 53.2%, while the best KNN model (k = 7) achieved about 50.4%. Overall, logistic regression performed slightly better on this dataset.

## Repository Contents
- `music_genre_logreg_knn.ipynb` — notebook with data loading, preprocessing, model training, and results
- `final_report` — written report for the final project
- `presentation` — slides for the final presentation
