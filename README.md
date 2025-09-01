# IMDb_Sentiment_Analysis
This project provides a solid foundation for sentiment analysis on this dataset, with potential for further improvement through exploring more advanced techniques or extensive hyperparameter tuning.
This project focuses on building and evaluating sentiment analysis models for IMDb movie reviews. The process involved the following steps:

Data Loading and Exploration: The dataset was loaded and explored to understand its structure, identify missing values (none found), and analyze the distribution of sentiment.

Data Preprocessing and Cleaning: Text data was cleaned by removing HTML tags, punctuation, and special characters, converting text to lowercase, and handling extra whitespace. Further preprocessing included tokenization, stop word removal, and stemming/lemmatization.

Feature Engineering: TF-IDF vectorization was applied to convert text data into numerical features. Additional textual features such as word count, character count, and average word length were also extracted.

Model Development: Multinomial Naive Bayes, Logistic Regression, and Support Vector Machine models were trained on the preprocessed and vectorized data.

Model Evaluation: The models were evaluated using accuracy, classification reports, and confusion matrices. Hyperparameter tuning was performed on Logistic Regression and Support Vector Machine models to potentially improve performance.

Visualization: Plots were generated to visualize the sentiment distribution, compare model accuracies, and display confusion matrices.

Key Findings:

The dataset is well-balanced between positive and negative sentiments.
Logistic Regression showed a slight improvement in accuracy after hyperparameter tuning, achieving the highest accuracy among the models tested.
Multinomial Naive Bayes and Support Vector Machine models also performed reasonably well.
