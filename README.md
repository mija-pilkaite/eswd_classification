# European Severe Weather Database Classification
European Severe Weather Database classification project. Utilizing different NLP techniques, I aimed to automatize the updates of the database as well as standardize the database for further research. 
# Overview
This project focuses on the categorization and extraction of severe weather events from the European Severe Weather Database (ESWD). The aim is to utilize advanced machine learning techniques to accurately classify text descriptions of weather events, thus reducing human dependency and enhancing the automation process for database management.
The dataset used was received from the European Severe Storms Laboratory. This research focused on the data collected in the area of France. The goal was to use the descriptions from news articles to build two types of classifiers - one that would predict the type of event and one that would predict whether this weather event should be considered severe. Right now the database is maintained manually, thus this research is the beginning of improving and automatizing a crucial database in climate research. 
More details and techniques used can be found in the report. 

### Author
Mija Pilkaite
### Supervision
Davide Buscaldi, DaSciM group, LIX, Ecole Polytechnique, France
# Project Structure
### Introduction and Objectives
Explanation of the need for automated classification of severe weather events.

Discussion on the methodology and techniques utilized for the classification.

### Classification of Severe Weather Events
Detailed analysis of data preprocessing, feature representation, and model evaluation.

Exploration of models such as Logistic Regression, Random Forest, and Fully Connected Neural Networks.

Binary Classifier for False Data

Development of a binary classifier to distinguish between true and false data related to severe weather events.

### Conclusion and Outlook
Summary of findings and discussion on the future scope of the project to enhance the classification accuracy and utility.

### Key Techniques and Technologies
Data Preprocessing: Involves tokenization, lemmatization, and removal of stopwords to prepare the dataset for modeling.

Feature Representation: Utilization of Bag of Words, TF-IDF vectorization, and SBert Transformation techniques to capture textual information.

Machine Learning Models: Implementation of logistic regression, random forests, and neural networks to classify weather events.

Evaluation Metrics: Use of accuracy, F1 scores, and confusion matrices to assess the performance of the models.

# Required Libraries
Run `pip install numpy pandas scikit-learn transformers spacy`

# Acknowledgments
Ecole Polytechnique for providing the academic environment and resources.
Prof David Buscaldi for guidance and feedback throughout the project development.
European Severe Storms Laboratory for providing the dataset.  
