📈 Google-Stock-Price-Pridiction
  This project predicts **Google stock prices** using a **Linear Regression model**. 
  The dataset includes stock features such as **Open, High, Low, Volume**, and the target variable **Close price**.
  
  📈 Google Stock Price Prediction using Linear Regression

📌 Project Overview
This project focuses on predicting **Google stock closing prices** using a **Linear Regression model**.  
The model is trained on historical stock market data, with preprocessing steps like feature scaling and dataset splitting to improve accuracy.
actual vs predicted prices are visualized for evaluation.  

⚙️ Steps Performed
1. Data Selection: Chose useful columns (`Date, Open, High, Low, Close, Volume`).  
2. Data Scaling: Applied `MinMaxScaler` to normalize features.  
3. Feature & Target Selection:  
   - Features (X): `Open, High, Low, Volume`  
   - Target (y): `Close`  
4. Train-Test Split: Split dataset into 80% training and 20% testing.  
5. Model Training: Fitted a Linear Regression model using `scikit-learn`.  
6. Prediction: Predicted stock closing prices on the test set.  
7. Evaluation:  
   - Mean Squared Error (MSE): 4.3039e-05
   - R² Score: 0.996 (excellent fit)  
8. Visualization: Plotted **Actual vs Predicted prices** using Matplotlib.  


 📊 Results
- ✅ Very low prediction error (MSE close to 0)  
- ✅ High accuracy (R² ~ 0.996)  
- ✅ The graph showed a comparison between the actual Google stock prices (blue line) and the predicted stock prices (red line) over the test period.
- The two lines are very close to each other and almost overlap throughout the time series.
- This indicates that the Linear Regression model was able to capture the stock price patterns very accurately.

 🛠️ Technologies Used
- **Python**  
- **Pandas & NumPy** – Data handling  
- **Scikit-learn** – Linear Regression, scaling, evaluation  
- **Matplotlib** – Data visualization  

📢 Conclusion
The Linear Regression model performed very well in predicting stock prices.
