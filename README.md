# EMAIL-SPAM-DETECTION


Spam Email Detection with Logistic Regression
This Python script is part of a project aimed at building a spam email detection system. The project is divided into several sections, each with a specific purpose:



Section 1: Importing the Modules
In this section, essential Python libraries such as pandas, matplotlib, scikit-learn (for machine learning), and TfidfVectorizer for feature extraction are imported. These libraries are crucial for data manipulation, visualization, and building the machine learning model.

Section 2: Data Collection and Pre-Processing
The script loads the email data from a local Excel file and performs several data pre-processing steps, including dropping unnecessary columns, renaming columns, and handling missing values. The resulting dataset is named mail_data.
Section 3: Label Encoding
In this section, label encoding is applied to categorize spam as 0 and ham (non-spam) as 1. This step is crucial for training the machine learning model.

Section 4: Splitting the Data into Training and Test Sets
The dataset is split into training and test sets to evaluate the model's performance. The train_test_split function is used for this purpose.

Section 5: Feature Extraction
Feature extraction is performed using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization. This step converts the text data into numerical feature vectors that can be used to train the logistic regression model.

Section 6: Training the Model
A logistic regression model is created and trained using the training data. The script then evaluates the model's accuracy on both the training and test data.

Building a Predicting System
The script includes a section for making predictions on new email text. An example email is provided, and the feature extraction and model prediction are applied to classify it as either spam or ham.

Overall, this script serves as a foundation for creating a spam email detection system. It leverages machine learning techniques to classify emails and can be extended for broader email filtering applications.

