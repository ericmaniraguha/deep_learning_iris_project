# deep_learning_projects (iris, sparm classifications, and IT Operations: Root cause Analysis )

1. iris dataset 
        Perform the following steps for preparing data
        a. Load data into a pandas dataframe
        b. Convert the dataframe to a numpy array
        c. Scale the feature dataset
        d. Use one-hot-encoding for the target variable
        e. Split into training and test datasets

2. sparm classification (SMS dataset)
    - Text processing 
        a. Clearning
        b. Stop words removals
        c. Lemmatization (is the process of reducing a word to its base or root form, also known as the lemma) e.g running => run
        d. Numeric representation
                -TF-IDF vs word embeddings (TfidfVectorizer also includes options for text preprocessing, such as removing stopwords and applying lemmatization or stemming. Additionally, it allows for the use of n-grams, which are sequences of adjacent words in the text.)
    code_05_XX Spam -Classification example

3. exercise problem (IT Operations: Root cause Analysis)
     a. A data center team want to build a model to predict causes of issues reported by customers.
     b. they use system monitoring tool to track CMPU, memory and application latency for all their servers 
     c. In addition they also trakc specific errors reported by applications.

## Problem statements:
        a. Using data about CPU load, memory load, network delays, and three types of errors, build a model to predict the root cause for error
        b. A data set is availavle for each incident, indicating if any load issues or errors was observed during that time.

## Steps to solve the problem 

1. preprocessing incident data
2. Data Conversion 
3. build and evaluate the model
4. predict the root causes 