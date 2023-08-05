# Deep Learning Challenge: Predicting Success for Funding Applicants

## Background
The nonprofit foundation Alphabet Soup aims to enhance the selection process of applicants for funding by identifying those with the highest likelihood of success. In this project, we will utilize machine learning and neural networks to create a binary classifier that predicts whether organizations will succeed if funded by Alphabet Soup.

## Dataset
Alphabet Soup provided a CSV dataset containing information on over 34,000 organizations that received funding. The dataset includes various columns with metadata about each organization, such as:
- EIN and NAME: Identification columns
- APPLICATION_TYPE: Alphabet Soup application type
- AFFILIATION: Affiliated sector of industry
- CLASSIFICATION: Government organization classification
- USE_CASE: Use case for funding
- ORGANIZATION: Organization type
- STATUS: Active status
- INCOME_AMT: Income classification
- SPECIAL_CONSIDERATIONS: Special considerations for application
- ASK_AMT: Funding amount requested
- IS_SUCCESSFUL: Whether the money was used effectively

## Step 1: Preprocess the Data
1. Read in the 'charity_data.csv' using Pandas.
2. Identify target and feature variables.
3. Drop unnecessary columns (EIN and NAME).
4. Determine the number of unique values for each column.
5. Bin "rare" categorical variables into an 'Other' category.
6. Encode categorical variables using pd.get_dummies().
7. Split data into features (X) and target (y) arrays.
8. Split data into training and testing datasets.
9. Scale training and testing features using StandardScaler.

## Step 2: Compile, Train, and Evaluate the Model
1. Create a neural network model using TensorFlow and Keras.
2. Design hidden layers with appropriate activation functions.
3. Create an output layer with the appropriate activation function.
4. Compile and train the model.
5. Create a callback to save model weights every five epochs.
6. Evaluate the model using test data and calculate loss and accuracy.
7. Save model results to 'AlphabetSoupCharity.h5'.

## Step 3: Optimize the Model
1. Import dependencies and read 'charity_data.csv'.
2. Preprocess the dataset considering optimization adjustments.
3. Design a neural network model for optimization.
4. Save optimized model results to 'AlphabetSoupCharity_Optimization.h5'.

## Step 4: Write a Report on the Neural Network Model
Provide a detailed report on the analysis:
- Explain the purpose of the analysis.
- Address questions about data preprocessing.
- Discuss model design choices and attempts to improve performance.
- Summarize the overall results and provide a recommendation for a different model approach.

## Step 5: Copy Files Into Your Repository
1. Download Colab notebooks.
2. Place them in the 'Deep Learning Challenge' directory in your local repository.
3. Push the added files to GitHub for final submission.
