# Breast Cancer Prediction 🧬

This project applies **Logistic Regression**, a supervised machine learning algorithm, to predict whether a breast tumor is malignant or benign using clinical diagnostic data. The model is trained on historical labeled data and evaluated using standard classification metrics.

## 🧪 Data Preprocessing

1. **Column Removal:**
   - Removed irrelevant columns such as patient ID or unnamed columns that do not contribute to prediction.

2. **Label Encoding:**
   - Converted the `diagnosis` column:
     - `M` (Malignant) → `1`
     - `B` (Benign) → `0`

3. **Feature Scaling:**
   - Used `StandardScaler` to normalize all features so they have a mean of 0 and standard deviation of 1.
   - Helps improve performance of gradient-based models like logistic regression.

4. **Train-Test Split:**
   - Split the dataset into training and testing sets using an 80:20 ratio to evaluate generalization performance.

## 📊 Model Performance

The model is evaluated using the following metrics:
- **Precision**
- **Recall**
- **F1-Score**
- **Cross-Validation Accuracy**

These metrics were calculated on both the training and test sets to ensure generalization.

## 🛠️ Tools & Libraries

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn (for visualization)

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Srinidhi2274/Breast-cancer-prediction.git
   cd breast-cancer-prediction
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use venv\Scripts\activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the notebook:
   ```bash
   jupyter notebook breast_cancer_prediction.ipynb
   ```

## 🔒 Permissions

This repository is read-only for others. Only the owner can make changes. If you'd like to suggest changes, please open an issue or submit a pull request for review.

## 📎 License

This project is released under the MIT License.
