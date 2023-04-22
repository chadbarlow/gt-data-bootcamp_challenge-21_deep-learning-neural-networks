<h1 align="left">NEURAL NETWORKS & DEEP LEARNING<br><i>Topic: Predicting Nonprofit Success</i> </h1> 

<p>This project aims to create a binary classifier to predict whether applicants funded by the nonprofit foundation Alphabet Soup will be successful in their ventures. The dataset provided contains over 34,000 organizations with various metadata about each organization.</p>

## Data Science Tools
- Pandas
- Scikit-learn
- TensorFlow
- Keras

## Methodology
1. Preprocess data: Handle categorical variables, drop unnecessary columns, split data into training and testing sets, and scale features using StandardScaler.
2. Compile, train, and evaluate a neural network model: Design a deep learning model using TensorFlow and Keras, create hidden layers with appropriate activation functions, and evaluate the model's accuracy and loss.
3. Optimize the model: Apply various optimization techniques to achieve a predictive accuracy higher than 75%.

## Conclusions
The neural network model provides a binary classification of the success of Alphabet Soup-funded organizations. The model's performance can be improved by optimizing the model using different techniques.

## Limitations and Further Development 
- Some features may have more impact on the prediction than others. Investigate feature importance and correlations to improve model accuracy.
- The model might overfit or underfit the data. Test different architectures, activation functions, and number of neurons in hidden layers. Explore other machine learning algorithms for comparison and possible improvement.
