# Customer-Churn-KiwiBank

**Predicting Customer Retention using Neural Networks at Kiwibank**

The main goal of this project is to develop a neural network model that forecasts customer retention at Kiwibank, helping to predict which customers are likely to stay or leave. The project involves building multiple neural network models, experimenting with different architectures and techniques to optimize performance and accuracy.

## Contents

1. **Problem Definition**
   - The problem at hand is predicting customer retention for Kiwibank using customer data. A high churn rate can negatively impact the business, and identifying customers likely to leave is key to developing targeted retention strategies.

2. **Loading Data and Python Packages**
   - **2.1. Loading Python Packages**: The necessary libraries for data manipulation, analysis, and machine learning are imported.
   - **2.2. Data Download**: The customer data is fetched and loaded for further analysis.

3. **Exploratory Data Analysis (EDA)**
   - **3.1. Descriptive Statistics**: Summary statistics of the data are computed to understand distributions, relationships, and potential outliers.
   - **3.2. Data Visualization**: Visualizations are generated to better understand the patterns and distributions within the data.

4. **Model Building**
   - **4.1. Model with 2 Layers**: The first neural network model with two layers is created.
   - **4.2. Model with 4 Layers**: A deeper model with four layers is built for improved complexity.
   - **4.3. Model with 6 Layers**: A six-layer model is tested to increase learning capacity.
   - **4.4. Model with 6 Layers & Kernel Regularizer**: Regularization techniques (Kernel Regularizer) are applied to reduce overfitting.
   - **4.5. Model with 6 Layers & Dropout**: Dropout layers are added to prevent overfitting by randomly setting the weights to zero during training.
   - **4.6. Model with 6 Layers & Batch Normalization**: Batch normalization is implemented to improve convergence speed and stability of the model.
   - **4.7. Model with 6 Layers, Kernel Regularizer & Batch Normalization**: A combination of regularization and normalization techniques is used to build a robust model.
   - **4.8. Model Evaluation**: The final models are evaluated based on various metrics, including accuracy, precision, recall, and F1-score.

5. **Conclusion**
   - A summary of the results, insights gained, and any conclusions drawn from the experiments and evaluation of the models.
