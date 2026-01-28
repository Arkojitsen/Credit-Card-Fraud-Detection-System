# *💳 Credit Card Fraud Detection System*

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. A Logistic Regression model is trained on a highly imbalanced real-world dataset to classify transactions as legitimate or fraudulent.

The system demonstrates key steps involved in a typical ML pipeline, including data exploration, preprocessing, handling class imbalance, model training, and evaluation.

# *🎯 Objectives*

- Identify fraudulent credit card transactions accurately

- Handle highly imbalanced data effectively

- Build and evaluate a reliable classification model

- Understand real-world financial fraud detection challenges

# *📂 Dataset Description*

- The dataset contains 284,807 transactions

- Each transaction has 30 numerical features

- Features V1 to V28 are PCA-transformed for confidentiality

- Amount represents the transaction value

- Class is the target variable:

   - 0 → Legitimate Transaction

   - 1 → Fraudulent Transaction

# *🔍 Key Observations*

- Fraudulent transactions are extremely rare

- Only 492 fraud cases exist in the entire dataset

- The dataset is highly imbalanced

# *🔬 Data Analysis & Preprocessing*

- Verified dataset structure and data types

- Checked for missing values (none found)

- Analyzed transaction distributions for both classes

- Compared statistical measures between legitimate and fraudulent transactions

# *⚖️ Handling Class Imbalance*

To address imbalance:

- Under-sampling was applied

- Equal number of legitimate and fraudulent transactions were selected

- Final balanced dataset contained:

  - 492 legitimate

  - 492 fraudulent

  - 984 total transactions

This ensured fair learning for the classification model.

# *🧠 Model Building*

- Algorithm Used: Logistic Regression

- Features and target variable were separated

- Data was split into:

  - Training set (80%)

  - Testing set (20%)

Feature scaling was applied using standardization

# *📊 Model Evaluation*

Model performance was evaluated using accuracy score:

- Training Accuracy: ~93.7%

- Testing Accuracy: ~91.3%

These results indicate strong generalization performance on unseen data.

# *🛠️ Technologies & Libraries Used*

- Python

- NumPy

- Pandas

- Scikit-learn

# *🚀 Key Learnings*

- Importance of handling imbalanced datasets

- Real-world fraud detection challenges

- Logistic Regression as a baseline classification model

- Data preprocessing and feature scaling techniques

# *📌 Future Improvements*

- Use advanced models like Random Forest or XGBoost

- Apply SMOTE for better imbalance handling

- Evaluate using precision, recall, and ROC-AUC

- Deploy the model as a web application

# *👤 Author*

Arkojit Sen
