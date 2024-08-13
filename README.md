# deep-learning-challenge
Module 21 Challenge

# Background
The project was implemented to develop classifier using machine learning and neural networks. The purpose is to predict the success  of application by applicants to funds from Alphabet Soup, a nonprofit foundation. The task is to create user friendly  tool to help Alphabet Soup to select applicants with potentially highest chance of success in their business. The analyis was based on dataset that contained over 340000 organizations that received funding from Alphabet Soup. The data points include elements of each of organization, applicant type, classification, funding and industry affiliation among other features. Some of the key expectation from the challenge is data procecssing, modeling and model compilation, training, evaluation, model optimization and analysis output and reporting. 

# Activites

Data Preprocessing

- Charity data was loaded into a Pandas DataFrame
- Features were identified
- non-beneficial ID columns (EIN and NAME) removed
- unique and value counts were performed
- Handle rare categorical variables
- feature array (X) and target array (y) created
- data split into training and testing sets
- Saling was applied to data using StandardScaler

Model Compilation, Training, and Evaluation
- A neural network model with appropriate input features and layer nodes designed
- Hidden layers, output layer with relevant activation functions created
- Model compilation and model training
- Model performance using test data evaluated
- Results exported to to AlphabetSoupCharity.h5 file

Model rerun and Optimization
- Preliminary preprocessing was done
- An optimized neural network models was tested
- At least four optimization methods with different combinations of neuron, hidden layers and activation layers tried
- The output was saved as .keras, because HDF5 is now a legacy format.

Analysis Report
A report that includes purpose, results and discussion, model performance, and summary was generated


Key findings
Relying on 34000 data points for past funding to entities, a neural network model was developed and ran which gave an accuracy of approximately 73.13% across multiple optimization attempts. Four iterations of hyperparameter tuning adjusting layers and activation 
was done to improve accuracy, however, the accuracy did not go beyond 73% to reach the expected target 75%. This could mean that the current approach may have maximum improvable from this data. Exploration of other machine learning to improve accuracy could be tried in future. 


