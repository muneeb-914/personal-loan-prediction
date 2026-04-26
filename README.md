# Personal Loan Acceptance Prediction

## Objective
Predict which bank customers are likely to accept a personal loan offer, enabling targeted marketing campaigns.

## Dataset
- **Source:** Kaggle — Bank Personal Loan Modelling Dataset
- **Shape:** 5,000 rows × 14 columns
- **Target:** Personal Loan (0 = Rejected, 1 = Accepted)
- **Class Distribution:** 4,520 Rejected (90.4%), 480 Accepted (9.6%)

## Approach
1. Explored dataset structure and distributions
2. Performed EDA with 4 visualizations
3. Dropped irrelevant columns (ID, ZIP Code)
4. Removed invalid data (negative experience values)
5. Trained Decision Tree Classifier

## Results & Insights
- **Accuracy: 98.08%**
- **Education is #1 predictor** (importance: 0.45)
- **Income is #2 predictor** (importance: 0.32)
- High-income, highly-educated customers with families accept loans most
- Age, CreditCard, Online Banking have almost zero influence

## Technologies Used
- Python, Pandas, NumPy
- Scikit-learn (Decision Tree, train_test_split)
- Matplotlib, Seaborn
