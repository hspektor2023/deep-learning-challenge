# deep-learning-challenge

* Overview: The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. We are using the features in the provided dataset to create a binary classifier (IS_SUCCESSFUL) that can predict whether applicants will be successful if funded by Alphabet Soup.

* Results:

* Data Processing:
    * What variable(s) are the target(s) for your model? IS_SUCCESSFUL
    * What variable(s) are the features for your model? APPLICATION_TYPE, CLASSIFICATION
    * What variable(s) should be removed from the input data because they are neither targets nor features? I tried to remove other variables like 'AFFILIATION', 'USE_CASE', 'ORGANIZATION', 'INCOME_AMT', 'SPECIAL_CONSIDERATIONS' apparently not in use but this did not optimize the accuracy of the results.

* Compiling, Training, and Evaluating the Model:
    * How many neurons, layers, and activation functions did you select for your neural network model, and why? In the regular version, 2 hidden layers, 1 output layer. In the optimized version, 3 hidden layers, 1 output layer. 2 activation functions. 
    * Were you able to achieve the target model performance? No. I was able to improve accuracy a bit from 72.7% to 73%.
    * What steps did you take in your attempts to increase model performance? Tried to drop columns (did not work), tried different optimizer other than ADAM (did not improve), different learning rate (improved a bit), increased number of hidden layers (improved another bit).

* Summary: I know that I could have done more trial and error attemps targetting a better optimization but what was done I consider to be enough to understand what needs to be done if I ever need to work again in a neural network optimization project.