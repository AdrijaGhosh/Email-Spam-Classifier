This project presents a comprehensive approach to building an email spam classifier using machine learning techniques. 
The process involves several stages, including data preprocessing, exploratory data analysis (EDA), feature engineering, model selection, and performance evaluation.
The dataset used for this study comprises a collection of emails labeled as spam or non-spam (ham). 
The initial step involves data preprocessing, where various text cleaning techniques are applied, including encoding handling, removing unnecessary columns, dealing with missing values, and eliminating duplicates.
Furthermore, text normalization techniques such as tokenization, stop word removal, punctuation removal, and stemming are employed to transform the raw text into a structured format suitable for analysis.
The EDA phase explores the characteristics of the dataset to gain insights into the distribution of spam and ham emails, analyze the length of messages, and examine the frequency of words.
Visualizations such as histograms, bar plots, word clouds, and correlation matrices are utilized to visualize the data and identify patterns.
Feature engineering involves extracting numerical features from the text data, including the number of characters, words, and sentences in each email. Additionally, term frequency-inverse document frequency (TF-IDF) vectors are generated to represent the textual content in a numerical format suitable for machine learning algorithms.
For model building, a variety of classifiers including Naive Bayes, Support Vector Machines, Decision Trees, Logistic Regression, Random Forest, and Gradient Boosting are trained and evaluated using performance metrics such as accuracy and precision. Hyperparameter tuning and model selection techniques are employed to optimize the classifiers' performance. Finally, the best working ML model with the least false positives i.e highest precession is selected.
