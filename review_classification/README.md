
1. Prepare project
    * Import libraries, set up graph quality tweaks and progress bar
    * Open data files
2. EDA
    * Number of reviews over time
    * Number of reviews per movie
    * Distribution of ratings (on a scale of 1-10)
    * Distribution of polarities over time
3. Data preprocessing 
    * Compose evaluation routine for models
    * Normalize text
    * Split into train and test sets
4. Train and evaluate models
    * Dummy model to establish baseline
    * NLTK, TF-idf, and Logistic Regression
    * SpaCy, TF-idf, and Logistic Regression
    * SpaCy, TF-idf, and LGBMClassifier
    * BERT
5. Test models on reviews I wrote
6. Conclusion


### Objective
Train a model for Film Junky Union's system for filtering and categorizing movie reviews. This project uses a dataset of IMBD movie reviews with polarity labelling to build a model for classifying positive and negative reviews. It will need to have an F1 score of at least 0.85.
