<h1>Module 21: Advanced Machine Learning</h1>

<h2>Background:</h2>
<p>The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as:

- EIN and NAME—Identification columns
  
- APPLICATION_TYPE—Alphabet Soup application type
  
- AFFILIATION—Affiliated sector of industry
  
- CLASSIFICATION—Government organization classification
  
- USE_CASE—Use case for funding
  
- ORGANIZATION—Organization type
  
- STATUS—Active status
  
- INCOME_AMT—Income classification
  
- SPECIAL_CONSIDERATIONS—Special considerations for application

- ASK_AMT—Funding amount requested
  
- IS_SUCCESSFUL—Was the money used effectively</p>

<h2>Requirements:</h2>

<h3>1. Preprocessing the Data</h3>

- Create a dataframe containing the charity_data.csv data , and identify the target and feature variables in the dataset

  [insert image here]
  
- Drop the EIN and NAME columns

  [insert image here]
  
- Determine the number of unique values in each column

  [insert image here]
  
- For columns with more than 10 unique values, determine the number of data points for each unique value

  [insert image here]
  
- Create a new value called Other that contains rare categorical variables

  [insert image here]

- Create a feature array, X, and a target array, y by using the preprocessed data

  [insert image here]

- Split the preprocessed data into training and testing datasets

  [insert image here]

- Scale the data by using a StandardScaler that has been fitted to the training data

  [insert image here]

<h3>2. Compile, Train and Evaluate the Model</h3>

- Create a neural network model with a defined number of input features and nodes for each layer

  [insert image here]
  
- Create hidden layers and an output layer with appropriate activation functions

  [insert image here]

- Check the structure of the model

  [insert image here]
  
- Compile and train the model

  [insert image here]
  
- Evaluate the model using the test data to determine the loss and accuracy

  [insert image here]
  
- Export your results to an HDF5 file named AlphabetSoupCharity.

  [insert image here]

<h3>3. Optimize the Model</h3>

- Repeat the preprocessing steps in a new Jupyter notebook
  
- Create a new neural network model, implementing at least 3 model optimization methods

- Save and export your results to an HDF5 file named AlphabetSoupCharity_Optimization

<h3>4. Write a Report on the Neural Network Model</h3>

Link to the written report can be found here: [insert link to Google Sheet]

- Write an analysis that includes a title and multiple sections, labeled with headers and subheaders

- Format images in the report so that they display correction
  
- Explain the purpose of the analysis
  
- Answer all 6 questions in the results section
  
- Summarize the overall results of your model
  
- Describe how you could use a different model to solve the same problem, and explain why you would use that model
