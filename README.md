# deep-learning-challenge
Overview of the analysis: Explain the purpose of this analysis.

The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.


Data Preprocessing
What variable(s) are the target(s) for your model?
The target variable is the 'IS_SUCCESSFUL' column from application_df

What variable(s) are the features for your model?
The feature variables are every other column from application_df --> this was defined by dropping the 'IS_SUCCESSFUL' column from the original dataframe

What variable(s) should be removed from the input data because they are neither targets nor features?
Both 'EIN' and 'NAME' columns were dropped/removed, because they were neither targets nor features for the dataset



Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
3 layers were added.

Were you able to achieve the target model performance?
My model reached 57.9% accuracy.

What steps did you take in your attempts to increase model performance?
Added multiple layers.

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
Overall, the deep learning model was around 58% accurate in predicting the classification problem. Using a model with greater correlation between input and output would likely result in higher prediction accuracy. This could be achieved by doing additional data cleanup up front, as well as by using a model with different activation functions and iterating until higher accuracy is reached.
