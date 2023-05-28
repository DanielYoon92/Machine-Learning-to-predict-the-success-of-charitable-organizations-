# deep-learning-challenge


Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.




Overview:
This analysis aims to build a deep learning model using a neural network to predict the success of charitable organizations based on provided dataset features.

Data Preprocessing:
Target variable: "IS_SUCCESSFUL" indicates the success of a charity organization.
Features: All columns except "EIN" and "NAME" are used.
Non-beneficial columns removed.
Model Development:

Neural network model with three layers: two hidden layers and one output layer.
Hidden layers: First layer has 80 neurons with ReLU activation, second layer has 30 neurons with ReLU activation.
Output layer: One neuron with sigmoid activation for binary classification.
Model compiled with "binary_crossentropy" loss, "adam" optimizer, and "accuracy" metric.
Trained for 100 epochs, achieving approximately 75% accuracy on the test data.
Model Improvement Attempts:

Binning: Application types and classifications were grouped to enhance model generalization.
Feature Scaling: StandardScaler used to normalize feature scales.
Neural Network Architecture: Adjusted the number of neurons and layers.
Activation Functions: ReLU activation introduced non-linearity for improved learning.
Optimizer: "adam" optimizer used for efficient gradient descent.
Training Duration: Model trained for 100 epochs to capture patterns.

Summary:

The deep learning model successfully achieved an accuracy of approximately 75% on the test data, meeting the desired model performance. However, there is still potential for further improvement. To enhance the model's predictive capability in determining the success of charitable organizations, additional strategies can be explored. Continuous experimentation and refinement would be key to maximizing the model's effectiveness and generating more precise predictions regarding charitable organization success.
