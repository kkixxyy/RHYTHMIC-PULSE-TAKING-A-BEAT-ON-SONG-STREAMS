#RHYTHMIC-PULSE-TAKING-A-BEAT-ON-SONG-STREAMS

#Project-Description
The primary objective of this analysis is to delve deep into the 2023 Spotify,Apple music, Deezer streaming trends for top songs. Our goal is to predict the total number of song streams for this year by using a linear regression model and a variety of libraries and techniques, such as NumPy, Pandas, Seaborn, Matplotlib, and Scikit-learn models.We were especially interested in the song stream counts in this data for our project. We believe that a song's overall popularity may be inferred from the song's raw total number of streams.

#Data Set
The Kaggle-sourced dataset serves as the cornerstone of our analysis, encompassing a comprehensive repository of songs released until July 2023.

#Methodology
In order to assess the effectiveness of our models, we choose to compute the Root Mean Squared Error (RMSE) and the Root Mean Absolute Error (RMAE) using a k-fold cross validation method. Our objective is to forecast the expected amount of plays a song will receive based on how frequently it has been added to playlists across three major streaming services. These assessment measures serve as indicators for the precision of our models.

#Results
Initially, the performance indicators were significantly improved by applying a log transformation to the dataset. Further gains were obtained by switching from a linear regression model to a polynomial regression model, more precisely a degree 3 polynomial. Compared to the initial linear model, the resultant polynomial regression model performed significantly better, with an average RMSE of around 232 million, indicating a 44 million drop. Furthermore, the original linear regression was around 1,500 units higher than the RMAE of 12,395. The polynomial model more accurately represented the actual data's form, even in the face of little differences in the direct comparison between anticipated and actual values.

#Conclusion
The analysis revealed strong correlations between playlist adds and streams, vital in driving song popularity. These relationships are well captured by the polynomial model, which highlights platform-specific trends: In contrast to Apple Music's more steady growth trend, Spotify and Deezer show decreased stream growth with greater additions.
