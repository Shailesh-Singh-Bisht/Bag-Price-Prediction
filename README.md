# **Bag-Price-Prediction**  
**Bag Price Prediction using Machine Learning - Kaggle Competition**  

## 📌 Project Overview  
This project predicts the price of bags using machine learning. It was submitted as part of a Kaggle competition, achieving a ranking of **1767**. The model is trained using **RandomForestRegressor** and various data preprocessing techniques.  

## 📂 Dataset  
- **train.csv** – Contains the training data with features and bag prices.  
- **test.csv** – Contains only features; the goal is to predict bag prices.  
- **submission.csv** – The final predictions on the test set. Download it here: [Submission File](https://drive.google.com/file/d/1XjJQEJcGDJZ26cqQ4uKw8FUIl-rwBc4M/view?usp=sharing)  

## 🛠️ Technologies Used  
- **Python**  
- **Jupyter Notebook**  
- **pandas** – Data manipulation  
- **RandomForestRegressor** – Model training & prediction  

## 🔄 Steps Involved  
1. **Data Preprocessing**  
   - Handle missing values  
   - Convert categorical data to numerical using encoding  
   - Feature selection & scaling  
2. **Model Training**  
   - Used `RandomForestRegressor` for prediction  
   - Tuned hyperparameters for better performance  
3. **Prediction & Submission**  
   - Generated predictions for `test.csv`  
   - Saved them in `submission.csv`  

## 🚀 How to Use  
1. Clone this repository:  
   ```sh
   git clone https://github.com/yourusername/Bag-Price-Prediction.git
   cd Bag-Price-Prediction
   ```  
2. Place `train.csv` and `test.csv` in the repo folder.  
3. Open `Bag_Price_Prediction.ipynb` in Jupyter Notebook.  
4. Run the notebook cells **one by one** to preprocess data, train the model, and generate predictions.  

## 📈 Results  
- **Model Used**: RandomForestRegressor  
- **Performance**: Achieved a ranking of **1767** on Kaggle  

