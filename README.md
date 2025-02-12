# California House Price Prediction

![House Price Prediction](https://raw.githubusercontent.com/Amanyadav-07/California_House_Price_Prediction/main/assets/banner.gif)

## 📌 Overview
This project predicts house prices in California using multiple machine learning models. The dataset undergoes preprocessing steps such as outlier handling, feature scaling, and hyperparameter tuning to improve prediction accuracy. Various regression models are trained and evaluated to determine the best-performing approach.

## 📊 Models and Performance

| Model               | Accuracy (%) |
|---------------------|--------------|
| Elastic Net        | 65.12        |
| Lasso Regression   | 65.12        |
| Random Forest      | 82.51        |
| XGBoost Regressor  | 84.89        |

## 📂 Repository Structure
```
├── housing.csv                   # Dataset 
├── models/                 # Trained model scripts
│   ├── elastic_net.py
│   ├── lasso_regression.py
│   ├── random_forest.py
│   ├── xgboost_regressor.py
├── requirements.txt        # Dependencies
├── README.md               # Project documentation
```

## 🔧 Data Preprocessing
- **Outlier Handling:** Imputed outliers with mean and median values.
- **Feature Scaling:** Applied StandardScaler for normalization.
- **Hyperparameter Tuning:** Used GridSearchCV for optimal model parameters.

## 🚀 Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Amanyadav-07/California_House_Price_Prediction.git
   cd California_House_Price_Prediction
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## 📌 Usage
Run the desired model script:
```bash
python models/random_forest.py
```

## 📈 Results & Visualizations

![Model Performance](https://raw.githubusercontent.com/Amanyadav-07/California_House_Price_Prediction/main/assets/performance.gif)

## 🤝 Contributing
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

## 📝 License
This project is licensed under the MIT License.

