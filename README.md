# Diamond Price Prediction - Data Science Project

This repository contains a completed data science project focused on predicting diamond prices. The dataset features various attributes of diamonds such as carat weight, cut quality, color, clarity, and physical dimensions. Advanced techniques like Principal Component Analysis (PCA), Density-Based Spatial Clustering of Applications with Noise (DBSCAN), and clustering have been employed to improve the model's performance.

## Dataset Features:

- **Price:** Price of the diamond in US dollars ($326--$18,823)

- **Carat:** Weight of the diamond (0.2--5.01)

- **Cut:** Quality of the diamond cut (Fair, Good, Very Good, Premium, Ideal)

- **Color:** Diamond color, from J (worst) to D (best)

- **Clarity:** A measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))

- **X:** Length in mm (0--10.74)

- **Y:** Width in mm (0--58.9)

- **Z:** Depth in mm (0--31.8)

- **Depth:** Total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)

- **Table:** Width of the top of the diamond relative to the widest point (43--95)

## Model Improvements:

This project involved an in-depth analysis of the data and the application of advanced data science methods. The key improvements include:

- **PCA:** Principal Component Analysis was used to merge features with a correlation greater than 0.7. This helped to reduce the dimensionality of the dataset while preserving its essential structure.

- **DBSCAN:** Density-Based Spatial Clustering of Applications with Noise was used to detect and remove outliers in the dataset, improving the model's robustness.

- **Clustering:** Clustering was performed to create new features, enhancing the dataset's expressiveness.

Through these improvements, the model's performance improved significantly, lowering the error from 540 to 525.


