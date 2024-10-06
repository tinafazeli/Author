# Author
This project is designed to identify the author of a text based on specific word features using a machine learning model (Random Forest). The model is trained on a dataset where each sample (text) is represented as a set of features indicating the presence or absence of certain words. The target is to classify the author of each text.

# Model : 
The project uses a Random Forest Classifier to predict the author based on word features.
Preprocessing steps include handling missing data and encoding author labels.
The model's performance is evaluated using the F1 Score (macro-averaging).

# Dataset :
The dataset consists of:
A column for each word feature (0 or 1), representing the presence/absence of a word in the text.
A target column (author) that contains the name or ID of the author for each text.
