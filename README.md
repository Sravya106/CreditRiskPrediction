# Credit Risk Prediction for Loan Applicants

**Project Overview:**

Thank you for giving me the opportunity to work on this project. This application aims to predict the credit risk of loan applicants. The goal is to help banks and financial institutions reduce the number of defaults by accurately predicting which applicants present high or low risk. 

We utilize machine learning models such as **Random Forest**, **KNN**, **SVM**, and **Naive Bayes** to make the predictions. The backend is integrated with **React** for the frontend, **Firebase OAuth** for authentication, **Firestore** for storing data, and **Google Cloud** for deployment. This web application helps real-time data collection and evaluates the credit risk of applicants.

---

## Features

- **Machine Learning Integration:** We use models like Random Forest, KNN, SVM, and Naive Bayes for credit risk prediction.
- **Real-Time Data:** Firebase Firestore is used to collect and store user data in real-time.
- **Secure Authentication:** Users log in securely using **Firebase OAuth**.
- **Analytics and Visualization:** Displays data insights, including a correlational heatmap, and stores user data for future predictions.


## Data Pre-Processing and Analytics

- **Handling Missing Values:** Null values are replaced or removed to ensure clean data.
- **Label Encoding:** Object or string values are converted to numerical values.
- **Normalization:** Data normalization is applied to improve model accuracy.
  
Analytics shows that the dataset consists of **700 good credits** and **300 bad credits**. The **correlational heatmap** helps identify which features are most influential in determining risk. Based on this analysis, irrelevant features like **Sex**, **Purpose**, **Job**, and **Housing** were removed. **This improved accuracy of our models by 4%**

---

## Model Building

The following models were tested:

1. **Random Forest**
2. **KNN**
3. **SVM**
4. **Naive Bayes**

**Random Forest** achieved the highest accuracy, as shown in the table below:

| Metric       | Random Forest | SVM     | Naive Bayes | KNN    |
|--------------|---------------|---------|-------------|--------|
| **Accuracy** | 0.725         | 0.63    | 0.705       | 0.68   |
| **Precision**| 0.733696      | 0.721854| 0.738372    | 0.7333 |
| **Recall**   | 0.957447      | 0.77305 | 0.900709    | 0.8581 |
| **F1 Score** | 0.830769      | 0.746575| 0.811502    | 0.79085|

---

## Frontend Using React

The frontend is built using **React**, which interacts with Firebase for authentication and Firestore for real-time data storage. The key features include:

- **Firebase OAuth Authentication**: Secure login for users.
- **Firestore Integration**: Real-time storage and retrieval of user data.
- **Credit Risk Prediction**: Uses the ML backend to classify credit risk as high or low.

---


