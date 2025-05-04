#  Financial Risk Profile Prediction using Machine Learning

This project leverages machine learning to classify individuals based on their financial risk profile (High, Moderate, Healthy). Using Random Forest, the model learns from demographic, credit, and behavioral data to assess financial risk accurately. The project includes preprocessing, model training, evaluation, and interpretability using feature importance.

---

##  Project Objective

To develop a machine learning model that can predict an individual's financial risk profile (Healthy, Moderate, High) based on a variety of financial and personal indicators. The goal is to provide a system that helps banks or financial institutions assess clients’ risk levels effectively and transparently.

---

##  Project Structure

- `Main.ipynb` – The main Jupyter Notebook containing:
  - Data import and cleaning
  - Exploratory Data Analysis (EDA)
  - Feature selection and preprocessing
  - Model building with Random Forest
  - Performance evaluation
  - Feature importance analysis

- `Read_me.txt` – Initial notes and explanations

---

## 📦 Libraries Used

-  **pandas** – For data manipulation and analysis  
-  **numpy** – For numerical computations
-  **LabelEncoder** – For encoding categorical labels  
-  **RandomForestClassifier** – The main ML model
-  **imblearn (SMOTE)** – For handling class imbalance through synthetic oversampling  

---

##  Model & Evaluation

### Algorithm Used:
- **Random Forest Classifier** – Chosen for its robustness, high accuracy, and ability to rank features based on importance.

### Evaluation Metrics:
- Accuracy Score
- Confusion Matrix
- Classification Report (Precision, Recall, F1-Score)

---

##  Results & Insights

The Random Forest Classifier achieved **over 90% accuracy** on the test dataset, effectively classifying individuals into appropriate financial risk categories.

###  Top Features Influencing Financial Risk:

- Credit Score  
- Income Level  
- Personal Savings Rate  
- Debt-to-Income Ratio  
- Bankruptcy History  

These features play a critical role in determining the financial health of an individual.

---

##  Key Takeaways

- **Behavioral and financial indicators** are strong predictors of risk.
- **Random Forest** provided a reliable and interpretable model without extensive tuning.
- **Feature importance analysis** helps enhance trust in model predictions and offers actionable insights.
- The model can be extended or integrated into financial systems for real-time risk assessment.

---

## 📈 Future Improvements

- Integrate with live financial data for real-time predictions  
- Expand the feature set with additional behavioral data  
- Apply cross-validation for improved generalization  
- Experiment with other ensemble models for comparison  

---

##  Contributing

Contributions are welcome! If you’d like to help improve this project:

1. Fork the repository  
2. Create a new branch (`git checkout -b feature/YourFeature`)  
3. Commit your changes (`git commit -m 'Add your feature'`)  
4. Push to the branch (`git push origin feature/YourFeature`)  
5. Open a Pull Request

For major changes or feature requests, please open an issue first to discuss your ideas.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
