# deep-learning-challenge


The target variable for this model was the success variable. Focusing on this column meant that the model could potentially predict success rates of future projcts.
APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT are the feature variables, as they are all descriptive of the project. They can each contribute to the success in one way or another.
EIN and Name should be dropped, as they are neither targets or features. Since EIN is an ID column, it might throw accuracy off. With name being unique to each row, turning it into dummy variables would be useless, making the model less efficient and lowering accuracy.
Compiling the model took a few tries of experimenting with different neurons and hidden layers. Eventually I settled on the fastest and most accurate number I could get.

I selected three layers, as it allowed me to reach 73.5% accuracy the most consistently. I selected 10 neurons for the first, and 8 for the second as it allowed for the most efficient runtime, but allowed me to get a slightly higher average accuracy percentage.
I was off of the target in the main six tests, and many others that were done to try answers "out of chance" in casse I was wrong.
I attempted removing more variables, adding layers, adding neurons, changing the target variable, and changing the activation methods.
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
I would say that the results are inconclusive, at a sub 85% accuracy rate, I would not trust the model to accurately predict the success of a project. Additionally, I think the model could be served better if there was less dummy variables, and more solid integers. 
