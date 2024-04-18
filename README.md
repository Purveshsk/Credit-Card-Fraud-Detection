Credit card Fraud detection
Dataset for the repo can be downloaded from this link : https://huggingface.co/datasets/purveshsk/Creditcard_dataset 
We will use a real dataset of anonymized credit card transactions made by European cardholders from Spetember 2013. These transactions are labeled as fraudulent or genuine, and we will build a fraud detection solution using machine learning to predict the correct labels for never-before-seen instances.
This dataset is highly imbalanced. Of the 284807 transactions, only 491 are fraudulent (0.172%). This low percentage of fraud is pretty typical for credit card transactions.
There are 28 features, all of which are numerical, and there are no categorical variables. These features are not the original features but rather the outputof principal component analysis. The original features were distilled to 28 principal components using this form of dimensionality reduction.
