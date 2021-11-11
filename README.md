# Deep-Learning-Homework-Charity-Funding-Predictor
create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

What variable(s) are considered the target(s) for your model?
the IS_SUCCESSFUL column was the target variable for the model because it documented if the money was used effectively by an applicant.

What variable(s) are considered to be the features for your model?
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS and ASK_AMT columns where all considered to be the features for my model.

What variable(s) are neither targets nor features, and should be removed from the input data?
EIN and NAME columns were neither targets nor features and were removed from my input data as well as APPLICATION_TYPE in my optimzied version.

How many neurons, layers, and activation functions did you select for your neural network model, and why?
For my first model I chose 13 neurons, 2 layers, relu and sigmoid activation functions for my neural network model because its what i was familair with from my class activities. upon further research i read that you should have at least as many neurons for however many inputs you have so in my optimized version I added 140 neurons, 4 layers and I used relu, telu and sigmoid activation functions.

Were you able to achieve the target model performance?
No matter how hard I tried I was not able to achieve the target model performance.

What steps did you take to try and increase model performance?
I removed the APPLICATION_TYPE column, I increased the amount of neurons, layers, epochs and I ran three different activation types.
 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
overall I believe the model ran ok, I think supervised learning would have been a better choice of a model because supervised learning allows you to produce a data output from the previous instance of data points. 
