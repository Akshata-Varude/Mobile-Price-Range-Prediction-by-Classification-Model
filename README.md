# Mobile-Price-Range-Prediction-by-Classification-Model
# Peoject Summary:- 
The mobile phone industry is fiercely competitive, and the price of a mobile phone is determined by multiple factors such as battery power, Bluetooth, camera quality, and screen size. To investigate the factors that influence the price range of mobile phones, a study was conducted. The study utilized a dataset containing approximately 21 variables to forecast the price range of mobile phones, which are categorized as low, medium, high, and very high.

In this project, we aim to develop a classification model for mobile price range prediction. In this project, we provided with dataset containing 21 features like information on battery power, bluetooth, info on the front camera and back camera, mobile is touch screen or not, pixel resolution by height and width, etc.

In this project following steps are involved.
1. Data Exploration and Inspection of the raw data.
2. Understanding variables and data wrangling by finding null/missing values, and finding duplicates.
3. Exploratory Data Analysis(EDA) involves data visualization, and understanding the relationship between variables.
4. Hypothesis testing.
5. Feature engineering and data preprocessing.
6. ML implementation, we implement a 3 ml model

      *   Logistic Regression
      *   Randomforest Classifier
      *   XG Boost Classifier  

The outcome is a valuable tool that aids consumers and manufacturers in navigating the mobile phone market more effectively. With the continuous evolution of mobile technology, this project holds the potential for ongoing enhancements and contributions to the field of predictive analytics.

# Problem Statement:-
In the current competitive mobile phone market, determining the optimal price range for a new mobile phone model is a crucial challenge for manufacturers and retailers. Pricing a mobile phone too high can deter potential buyers, while pricing it too low may result in missed revenue opportunities. Therefore, the primary objective of this project is to create a predictive model that can estimate the appropriate price range for a mobile phone, considering a wide array of technical features and characteristics.

# Conclusion:-
Certainly! Here's a paraphrased summary of observations and results:

1. **Price Ranges and Distribution:**
   - The dataset comprises mobile phones classified into four price ranges, each with a similar number of elements.

2. **Bluetooth Presence:**
   - Approximately half of the devices have Bluetooth, while the other half do not.

3. **Battery and Price Relationship:**
   - There is a gradual increase in battery capacity as the price range of mobile phones increases.

4. **RAM and Price Relationship:**
   - RAM exhibits a continuous increase in capacity with the rise in price range, indicating its significance in determining the phone's cost.

5. **Weight and Cost Relationship:**
   - Costly phones tend to be lighter, suggesting an inverse relationship between weight and price range.

6. **Significant Features:**
   - RAM, battery power, and pixel specifications play a more significant role in determining the price range of mobile phones.

7. **Classification Models:**
   - Implemented three classification models: Logistic Regression, Random Forest, and XG Boost.

8. **Model Performance:**
   - Achieved fairly good results for all three algorithms.
   - Logistic Regression achieved an accuracy of approximately 98%, while Random Forest and XG Boost showed around 90% accuracy.

9. **Data Classification:**
   - The high accuracy suggests that the data were well-classified by the models.

10. **Model Comparison:**
    - Logistic Regression outperformed the other two models in terms of accuracy.

In summary, the analysis indicates that certain features, especially RAM, battery power, and pixel specifications, play a crucial role in determining the price range of mobile phones. The implemented classification models, particularly Logistic Regression, demonstrated effective performance in classifying the data into the specified price ranges.
