# lab-4-
Lab 4: Data Quality Assessment & Preprocessing
lab Overview
In this lab, I focused on the critical stage of Data Preprocessing before building machine learning models. Real-world data is often noisy, incomplete, or inconsistent. The goal of this project was to assess the quality of a sales dataset and apply various techniques to clean and normalize the data for better model performance.

Tasks Completed:
Data Quality Assessment: Identified missing values, inconsistent formats, and potential noise in the dataset.

Handling Missing Values: Applied strategic methods (like Mean/Median imputation or dropping rows) to handle incomplete data, ensuring the integrity of the remaining dataset.

Outlier Detection & Handling: Used the IQR (Interquartile Range) method to detect extreme values that could skew the model and handled them appropriately.

Feature Scaling (Normalization): * Applied Min-Max Scaling to bring features into a range between 0 and 1.

Applied Z-score Standardization to center the data around a mean of 0 with a standard deviation of 1.

Dimensionality Reduction (PCA): Explored Principal Component Analysis (PCA) to reduce the number of features while retaining the most important information (variance), which is crucial for high-dimensional datasets.

Tools & Libraries Used:
Python

Pandas & NumPy (For data manipulation and quality assessment)

Matplotlib & Seaborn (For visualizing outliers and distribution of scaled data)

Scikit-Learn (For implementing PCA and Scaling techniques)
