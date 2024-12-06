# Car_price_ML_model
# Car Price Prediction Using Linear Regression

This project aims to predict car prices based on various features such as age, mileage, brand value, and other relevant factors using a linear regression model.

## 📁 Dataset
The dataset used in this project (`car_price.csv`) includes the following features:
- **Feature 1**: [Description of the feature]
- **Feature 2**: [Description of the feature]
- ...
- **Price**: The target variable representing the car's price.

The dataset contains `N` rows and `K` columns. (Replace `N` and `K` with actual numbers.)

### Sample Dataset Snapshot:
| Feature 1 | Feature 2 | ... | Price |
|-----------|-----------|-----|-------|
| Example 1 | Example 2 | ... | 10000 |

---

## 🔧 Project Workflow
1. **Data Preprocessing**:
   - Handled missing values.
   - Performed feature scaling (if applicable).
   - Encoded categorical variables.

2. **Model Training**:
   - Used a linear regression model from `sklearn` to train on the dataset.
   - Split data into training and testing sets for evaluation.

3. **Model Evaluation**:
   - Evaluated the model using metrics like Mean Squared Error (MSE) ,MAPE and R² Score.

4. **Prediction**:
   - The model predicts car prices based on user-provided input values for features.

---

## 🛠️ Installation and Usage
### Prerequisites
- Python 3.x
- Libraries: `pandas`, `numpy`, `sklearn`, `matplotlib`, `seaborn`

### Steps to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/car_price_ML_model.git
   cd car_price_ML_model
