# Sentiment Analysis of Amazon Product Reviews

---

## **Project Overview**
This project focuses on sentiment analysis of Amazon product reviews specifically for Redmi products. The aim is to classify reviews as positive, negative, or neutral based on the sentiment expressed in the text. A range of machine learning models were evaluated to identify the most effective approach for this task. This README outlines the dataset, methodology, performance, and insights derived from the analysis.

---

## **Dataset Description**
The dataset consists of Amazon product reviews related to Redmi products. It includes:
- **Review Text:** The main text of the customer review.
- **Rating:** A numeric rating from 1 to 5.
- **Review Date:** The date the review was posted.

### **Data Preprocessing**
1. **Cleaning:** Removed stopwords, punctuation, and special characters from the review text.
2. **Normalization:** Converted text to lowercase for uniformity.
3. **Tokenization:** Split the text into individual tokens (words).
4. **Vectorization:** Used techniques like TF-IDF and Word2Vec for feature extraction.
5. **Balancing:** Handled class imbalance using SMOTE (Synthetic Minority Oversampling Technique).

---

## **Models Evaluated**
The following machine learning models were tested and compared:
1. **Logistic Regression**
2. **Random Forest**
3. **Support Vector Machine (SVM)**
4. **Neural Network**

### **Evaluation Metrics**
- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **ROC-AUC**

---

## **Model Performance**

| **Metric**       | **Logistic Regression** | **Random Forest** | **SVM**               | **Neural Network**     |
|-------------------|--------------------------|-------------------|-----------------------|-------------------------|
| **Accuracy**      | 0.88                    | 0.91              | **0.92**              | **0.93**               |
| **Precision**     | 0.87                    | 0.89              | **0.91**              | **0.93**               |
| **Recall**        | 0.89                    | 0.93              | **0.94**              | **0.95**               |
| **F1 Score**      | 0.88                    | 0.91              | **0.92**              | **0.94**               |
| **ROC AUC**       | 0.90                    | 0.93              | **0.94**              | **0.96**               |

### **Best Performing Model**
The **Neural Network** outperformed other models with the highest overall accuracy (0.93) and a balanced performance across all metrics. This makes it the best choice for this sentiment analysis task.

---

## **Key Insights**
1. **Neural Network:** High precision and recall make it ideal for identifying both positive and negative sentiments accurately.
2. **Support Vector Machine (SVM):** A close contender, offering high accuracy and F1 Score with the best ROC-AUC (0.94).
3. **Random Forest:** Achieved high recall, useful for scenarios where identifying all relevant sentiments is critical.
4. **Logistic Regression:** Provides good interpretability and serves as a reliable baseline model.

---

## **Conclusion and Recommendations**
Based on the performance metrics and analysis, the **Neural Network** model is recommended for deployment in applications requiring high accuracy and precision. Future work can involve:
- Exploring ensemble techniques for further performance improvements.
- Extending the analysis to include multi-lingual reviews.
- Utilizing advanced Natural Language Processing (NLP) techniques like transformer-based models (e.g., BERT).

---

## **How to Run the Project**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name/sentiment-analysis-redmi.git
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Preprocess the dataset:
   - Use the `preprocessing.py` script to clean and prepare the data.

4. Train the models:
   - Run `train_model.py` to train and evaluate the machine learning models.

5. Generate predictions:
   - Use the `predict.py` script to classify new reviews as positive, negative, or neutral.

---

## **Directory Structure**
```plaintext
sentiment-analysis-redmi/
|-- data/
|   |-- raw/                # Raw dataset files
|   |-- processed/          # Processed data files
|-- notebooks/              # Jupyter notebooks for exploration and analysis
|-- src/
|   |-- preprocessing.py    # Data preprocessing script
|   |-- train_model.py      # Model training script
|   |-- predict.py          # Prediction script
|-- reports/                # Analysis reports and visualizations
|-- requirements.txt        # Project dependencies
|-- README.md               # Project documentation (this file)
```

---



## Contributing

Contributions are welcome! If you have ideas to improve this repository or want to add more projects, please feel free to:

1. Fork the repository.
2. Make your changes.
3. Submit a pull request.

---

## License
This repository is licensed under the MIT License. Feel free to use and modify the code as needed.

---

## Author
**Md. Rasel Sarker**  
Email: [rasel.sarker6933@gmail.com](mailto:rasel.sarker6933@gmail.com)  

<br>
<h1 align="left">
 <h2><img src = "https://media2.giphy.com/media/QssGEmpkyEOhBCb7e1/giphy.gif?cid=ecf05e47a0n3gi1bfqntqmob8g9aid1oyj2wr3ds3mg700bl&rid=giphy.gif" width=30px valign="bottom"> 🌐 Connect with Me:</h2>
</h1>

<p align="center">
  <a href="mailto:rasel.sarker6933@gmail.com"><img src="https://img.shields.io/badge/Email-rasel.sarker6933@gmail.com-blue?style=flat-square&logo=gmail"></a>
  <a href="https://github.com/raselsarker69"><img src="https://img.shields.io/badge/GitHub-%40Raselsarker-lightgrey?style=flat-square&logo=github"></a>
  <a href="https://www.linkedin.com/in/rasel-sarker-405160227/"><img src="https://img.shields.io/badge/LinkedIn-Rasel%20Sarker-blue?style=flat-square&logo=linkedin"></a>
  <a href="https://www.facebook.com/mdrasel.sarker.7773631"><img src="https://img.shields.io/badge/Facebook-%40Raselsarker-blue?style=flat-square&logo=facebook"></a>
  <a href="https://www.kaggle.com/mdraselsarker"><img src="https://img.shields.io/badge/Kaggle-%40Raselsarker-blue?style=flat-square&logo=kaggle"></a>
  <a href="https://www.youtube.com/@raselsarker69"><img src="https://img.shields.io/badge/YouTube-Rasel%20Sarker-red?style=flat-square&logo=youtube"></a>
  <a href="https://www.facebook.com/groups/832585175685301"><img src="https://img.shields.io/badge/Facebook%20Group-Rasel%20Sarker%20Group-blue?style=flat-square&logo=facebook"></a>
  <br>
  <img src="https://img.shields.io/badge/Phone-%2B8801581528651-green?style=flat-square&logo=whatsapp">
</p>
 

---

<div align="center">

Thank you for visiting my repository. I hope these projects inspire and guide your learning journey!

---

Feel free to explore, learn, and build upon these projects. Happy coding!<br>

&copy; 2025 Machine Learning Projects

</div>
