# deep_learning

## Overview

The objective of this project is to assist Alphabet Soup—a philanthropic organization—in determining which funding applications from potential investors will likely result in successful ventures. By using machine learning and neural networks, this analysis aims to create an effective binary classifier to predict investment outcomes based on historical data.

## Features and Target Variable

# Feature Variables

* APPLICATION_TYPE: Type of application
* AFFILIATION: Affiliation with other entities
* CLASSIFICATION: Classification code of the organization
* USE_CASE: Use case for the funds
* ORGANIZATION: Organizational type
* STATUS: Active status
* INCOME_AMT: Income classification
* SPECIAL_CONSIDERATIONS: Any special considerations
* ASK_AMT: Amount asked by the applicant

## Target Variable
IS_SUCCESSFUL: Indicates if the funding was a success (1 = successful, 0 = not successful)

## Data Preprocessing

Variables such as EIN (Employer Identification Number) and Name were excluded from the analysis to focus on factors that directly influence funding outcomes.

## Model Architecture

# Initial Model

* Layers: 2 (80 neurons in the first layer and 30 in the second layer)
* Output Layer: 1 neuron (binary output)
* Achieved Performance: 72.62% accuracy

## Technologies Used

* Python
* TensorFlow/Keras
* Pandas
* Scikit-Learn

## Conclusion

The optimized neural network model demonstrates a marginal improvement in accuracy. Further experimentation with additional tuning, more complex model architectures, or alternative algorithms might yield better results.

## How to Contribute

Contributors looking to improve the model or suggest changes can submit pull requests or raise issues in this repository. Detailed instructions on setting up the development environment and contributing guidelines should be provided here.


