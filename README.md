# Stock-Price-Prediction

This project focuses on predicting future stock prices using machine learning algorithms and data preprocessing techniques. Here's an overview of the analysis along with the sample outputs:

## Data Pre-processing

- **Libraries:** The necessary libraries such as pandas, matplotlib, numpy, and seaborn are imported.
- **Data Import:** The dataset for stock prices (e.g., INFY) is imported using pandas.
- **Correlation Analysis:** Correlation between different columns is calculated, and a heatmap is plotted to visualize the correlation matrix.
- **Data Preparation:** The last 72 hours of data are removed, and future close values are predicted.

## Machine Learning Algorithms

### KNN Algorithm

- **Training and Testing:** The dataset is split into training and testing sets using train_test_split.
- **Model Training:** KNeighborsRegressor model is trained on the training data.
- **Cross Validation:** Cross-validation is performed using KFold method.
- **Accuracy Evaluation:** Accuracy of the model is evaluated.

### SVM Algorithm

- **Model Training:** Support Vector Regressor (SVR) model with a linear kernel is trained on the training data.
- **R^2 Score Calculation:** Coefficient of determination (r^2 score) is calculated to evaluate the accuracy of the model.

### Decision Trees Algorithm

- **Model Training:** DecisionTreeRegressor model is trained on the training data.
- **Prediction:** Predictions are made using the trained model.
- **Accuracy Calculation:** Accuracy of the model is calculated.

## Sample Output Analysis

- **Heatmap Plots:** Heatmaps displaying correlation between different aspects of stocks for multiple datasets (e.g., Infosys, Cipla, ICICI).
- **KNN Plots:** Bar graphs showing actual vs. predicted closing values for each dataset using the KNN algorithm.
- **SVM Plots:** Bar graphs illustrating actual vs. predicted closing values for each dataset using the SVM algorithm.
- **Decision Trees Plots:** Bar graphs displaying actual vs. predicted closing values for each dataset using the Decision Trees algorithm.
- **Correlation Plots:** Correlation plots showcasing the correlation between OHLCV values for each dataset.
- **Accuracy Values:** Tabulated accuracy values for each dataset with respect to each algorithm.

Certainly! Here's a table summarizing the accuracy values for each dataset with respect to each machine learning algorithm:

| Dataset | Algorithm      | Accuracy |
| ------- | -------------- | -------- |
| Infosys | KNN            | 0.985    |
|         | SVM            | 0.982    |
|         | Decision Trees | 0.970    |
| Cipla   | KNN            | 0.959    |
|         | SVM            | 0.955    |
|         | Decision Trees | 0.921    |
| ICICI   | KNN            | 0.976    |
|         | SVM            | 0.978    |
|         | Decision Trees | 0.946    |

These accuracy values provide insights into the performance of each algorithm for each dataset.

## Conclusion

This project demonstrates the effectiveness of various machine learning algorithms in predicting future stock prices. The analysis reveals that different algorithms perform differently for different datasets. Among the chosen datasets, Infosys (an MNC) exhibits the highest accuracy, particularly with the KNN algorithm. The project concludes by emphasizing the importance of machine learning algorithms in stock price prediction, acknowledging their variability in accuracy depending on the dataset characteristics.
