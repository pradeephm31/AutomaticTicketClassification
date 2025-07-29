# AutomaticTicketClassification
AutomaticTicketClassification

📌 Problem Statement
The goal is to develop a machine learning pipeline that classifies customer complaints into relevant product/service categories. This will enable automated segregation of tickets, leading to quicker issue resolution and improved customer service.

The dataset provided is in .json format and consists of unlabelled customer complaints. To analyze and organize this data, you will apply topic modeling using Non-negative Matrix Factorization (NMF) to identify patterns and cluster the complaints into the following five categories:

Credit card / Prepaid card

Bank account services

Theft / Dispute reporting

Mortgages / Loans

Others

Once the data is clustered, you can treat the resulting labels as targets to train a supervised classification model (e.g., Logistic Regression, Decision Tree, Random Forest). This model will then be used to classify new incoming complaints.

🔁 Pipeline Overview
You will build an end-to-end ML pipeline that includes the following stages:

Data Loading
Load and inspect the unlabelled .json complaint dataset.

Text Preprocessing
Clean and tokenize the complaint text. This may include lowercasing, removing stopwords, punctuation, and lemmatization.

Exploratory Data Analysis (EDA)
Analyze the distribution and structure of the data to extract meaningful insights.

Feature Extraction
Convert text into numerical features using techniques like TF-IDF.

Topic Modeling (NMF)
Apply Non-negative Matrix Factorization to discover latent topics and cluster complaints into the 5 categories.

Model Building (Supervised Learning)
Use the generated topic clusters as labels to train a supervised classifier.

Model Training and Evaluation
Split the data, train the model, and evaluate performance using appropriate metrics (e.g., accuracy, F1-score).

Model Inference
Use the trained model to predict the category of new/unseen customer complaints.

🧠 Technologies & Techniques
Natural Language Processing (NLP)

Non-negative Matrix Factorization (NMF)

TF-IDF Vectorization

Scikit-learn ML Models

Pandas, NumPy, Matplotlib, Seaborn

🚀 Objective
Build a robust classification system that helps customer support teams quickly direct complaints to the appropriate department, improving service efficiency and response times.
