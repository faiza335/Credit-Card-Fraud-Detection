# Credit-Card-Fraud-Detection
### 📌 Project Overview
Financial fraud transactions are a major challenge for banks worldwide. This project focuses on building a highly accurate **Machine Learning model** to detect fraudulent credit card transactions. The primary challenge was the **extreme class imbalance** (0.17% fraud vs 99.83% normal), which was handled using advanced data science techniques.

### 🚀 Key Technical Features
- **Data Scaling:** Applied `StandardScaler` to normalize the 'Time' and 'Amount' features.
- **Handling Class Imbalance:** Used **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset, improving the model's ability to learn fraud patterns.
- **Model:** Built a **Random Forest Classifier** to achieve high precision and recall.
- **Evaluation:** Focused on **Precision-Recall** and **F1-Score** instead of just accuracy.

### 📊 Performance Results
The model delivered excellent results on the test set:
- **Precision (Class 1):** 96% (Low false alarms)
- **Recall (Class 1):** 87% (Detected most of the actual frauds)
- **F1-Score:** 91% (Solid balance between precision and recall)

### 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, Imbalanced-learn
- **Environment:** Google Colab / VS Code

### 📂 How to use
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run the `fraud_detection.ipynb` notebook to see the full analysis.

<img width="595" height="468" alt="image" src="https://github.com/user-attachments/assets/a20081a9-b015-46df-b5f6-dcc3e3f1a3f5" />

   <img width="610" height="612" alt="image" src="https://github.com/user-attachments/assets/309d56d9-a36a-4288-8570-e1957b5e25b7" />

   <img width="875" height="589" alt="image" src="https://github.com/user-attachments/assets/590ea42e-2228-45ec-ab8c-09027f23ab12" />
   
