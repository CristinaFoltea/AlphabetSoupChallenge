# AlphabetSoupChallenge

How many neurons and layers did you select for your neural network model? Why?
After lots of trial and error I settle on the 2 layer one with 10 the other with 6. I was never able to increase the model performance over 53%

Were you able to achieve the target model performance? What steps did you take to try and increase model performance?

1. Removed highly distributed column
2. Binning and drop columns
3. Changed the number of neurons
4. Changed the number of layers
5. Change the number of epochs
6. Different types of activation function for input and output

If you were to implement a different model to solve this classification problem, which would you choose? Why?

To solve this classification problem I would choose to use random forest because:
 - It handles well tabular, nonlinear data
 - Is robust against overfitting 
 - Faster than a neural network 