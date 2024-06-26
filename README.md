# Spam-Review-Detection

About the project: we focus on predicting the review of customer is spam or not, good review or just write without mind

The class label is spam and not spam, where "0" indicates not spam and "1" indicates spam reviews. All in .json file​, data cleaning Only Toys and Games category​, we take only reviewText and class and 100000 datapoints​, apply contractions, remove special​ characters like '$' and '!', remove numeric digits like '19.99'​. Feature extraction include CountVectorizer, IfIDFVectorizer, Combine of both, Word Embedding using BERT, Spacy library and 7 ML, 4 DL, 2 LLM models

Multinomial Naive Bayes​, DecisionTreeClassifier​, LogisticRegression​, RandomForestClassifier, LinearSVC​, Perceptron​, XGBoost​, LSTM, GRU​, CNN, BiLSTM, BERT, GPT2, Mamba models

Learn more about the dataset: https://www.kaggle.com/datasets/naveedhn/amazon-product-review-spam-and-non-spam, 

We only use subdata of this which is Toys_and_Games category via Toys_and_Games.json
- Open and read the file `Project2.pptx` which is a presentation of our work, kind of brief report
- Open and read the file `Project2.pdf` which is a report of our work 
- All our ML model in `ML` folder, same with `DL` and `LLM`
- For inference, run file `Infer/spam-detection-infer.ipynb` and change sentence to the review you want to check
