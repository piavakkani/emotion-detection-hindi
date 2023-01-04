## Emotion Detection from text in Hindi

Emotion detection (ED) is vital in determining individual interest in any field. Significant work has been done to detect emotions from textual data in English, Spanish, and other high-resource languages. However, emotion classification has not been well studied in low-resource languages like Hindi due to the lack of annotated datasets.

We used a dataset that consisted of Hindi sentences in the Devanagari script that were annotated in the four categories - happy, sad, angry and neutral. Link for the dataset: https://github.com/skn1998/Emotions-Classification-in-Hindi-Text

We performed data preprocessing which included the following tasks - outlier removal, labelling the data, and removing missing data, numbers, symbols and punctuation marks. Next, we performed tokenization. Tokenization is used in NLP to split the text into smaller units called tokens that can be processed more easily. Following tokenization, we implemented keyword extraction, also known as feature engineering, where we extracted the most important words and expressions from our data.

In this project, two models were compared - Naive Bayes and Support Vector Machine. We also have a Logistic Regression model.

### Obtained results
1. Naive Bayes - 0.55
2. SVM - 0.51
3. Logistic Regression - 0.56

### Future Work
+ In the future, we aim on evaluating this model on data after the stopwords have been removed. 
+ Future work can be done by evaluating a bigger dataset. 
+ Additional labelled datasets can be prepared in Hindi language for paragraph and sentence-based Emotion Detection. 
+ Moreover, more emotions like surprise, fear and nervousness can be included and studied. 
