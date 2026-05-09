# final-music-genre-classification
This project explores music genre classification using the Free Music Archive (FMA) metadata and feature dataset. The goal is to predict the top-level genre of a track from precomputed audio features.

For the final project, I compared two standard machine learning methods, multinomial logistic regression and k-nearest neighbors (KNN), and also proposed an improved hybrid method using Principal Component Analysis followed by KNN (PCA+KNN). The motivation for the hybrid method was to test whether reducing the dimensionality of the 518-feature input space would improve nearest-neighbor classification.

Using a subset of 6,746 tracks across 8 genres, logistic regression achieved a test accuracy of about 53.2%, while the best KNN model (k = 7) achieved about 50.4%. The best PCA+KNN model, using 100 principal components and k = 7, also achieved about 50.4%. Overall, logistic regression performed best on this dataset, while PCA+KNN provided a reasonable but not superior improvement over standard KNN.

## Repository Contents
- `music_genre_logreg_knn.ipynb` — notebook with data loading, preprocessing, model training, and results
- `final_report` — written report for the final project
- `presentation` — slides for the final presentation
