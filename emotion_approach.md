Approach -

1. We found out that the dataset was imbalanced so we used SMOTE technique to balance the dataset.

2. Then we created some manual features based on the reviews like num_of_words, num_unique_words, mean_word_length etc.

3. Then we cleaned the text, remove punctuation, top words and did lemmatization and stemming.

4. We used TF_IDF Vectorizer to generate numeric features from the given text.

5. For modeling we used RandomForestClassifier. Accuracy can be further increased using ensemble techniques.

