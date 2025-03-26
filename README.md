# 🚀 Smarter Reconciliation and Anomaly Detection using Gen AI

## 📌 Table of Contents
- [Introduction](#-introduction)
- [Demo](#-demo)
- [What It Does](#-what-it-does)
- [Challenges We Faced](#-challenges-we-faced)
- [How to Run](#-how-to-run)
- [Tech Stack](#-tech-stack)
- [Team](#-team)

---

## 🎯 Introduction
Reconciliation often involves comparing large datasets from different sources (e.g., financial transactions, inventory records) to identify mismatches or discrepancies. 
Traditional methods rely on rule-based algorithms or manual checks, which can be time-consuming and error-prone. 
Similarly, anomaly detection for fraud, errors, or deviations requires sophisticated pattern recognition and adaptive learning.

## 🎥 Demo
Click the links below for demo vedio and documnet with screenshots

🔗📹 [Video Demo](https://github.com/ewfx/sradg-gen-sena-fraud-prevention/tree/7fbecf11dbc51709b447a4af9e59bf62dabf1805/artifacts/demo) 

   ![Screenshot 1](https://github.com/ewfx/sradg-gen-sena-fraud-prevention/tree/7fbecf11dbc51709b447a4af9e59bf62dabf1805/artifacts/demo/Demo_Screenshots.docx)

## ⚙️ What It Does
-Automate the reconciliation process.

-Enhance accuracy in identifying mismatches and anomalies.

-Reduce manual intervention.

-Provide actionable insights for faster resolution.

## 🚧 Challenges We Faced
How to present the agent using visualisations, and providing option to drop or add coloumns for reconsiliation.

# 🏃 How to Run
1. Clone the repository  
   
2. Install dependencies  
   pip install streamlit pandas numpy scikit-learn matplotlib seaborn
   
4. Run the project
   - **streamlit run SmarterReconciliation_GenAI.py & npx localtunnel --port 8501**
   - A URL will be generated to access the Streamlit application.
   - To access the application we will need a tunnel password and to generate the same, use this command:
     **wget -q -O - ipv4.icanhazip.com** 
   -You can use the google colab and use the above steps to run our application, if you do not have Python installed.
5. We have placed the sample data sets in artifacts folder for testing.
   

# 🏗️ Tech Stack
- 🔹 **Frontend**: Streamlit
- 🔹 **Plotting and Visualisation**: seaborn and matplotlib for plotting and visualisation.
- 🔹 **Data Processing**: Pandas and NumPy
- 🔹 **LLMs**: K-Means for clustering and Isolation forest for anomolies detection.
- 🔹 **Machine Learning**: Scikit-learn
  
# 👥 Team
- Phani Kanth Daliparthi
- Tarun Kumar Kollipara
- Sruthi Malladi
- Ammanna babu Kagitha
