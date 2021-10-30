# Neural_Network_Charity_Analysis

## Purpose
Create a binary classification model that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results

### _Data Preprocessing_

•	Model's target variable: "Is Successful"

•	Model's features variables: "Status", "Asking Amount", "Application Type", "Income Amount", "Classification", "Special Considerations"

•	Variables that are neither targets nor features, and therefore removed:  "EIN", "Name", "Affiliation", "Use_Case", "Organization"


### _Compiling, Training, and Evaluating the Model_

•	Number of neurons, layers, and activation functions selected for this neural network model, and why:

In researching the question of how many neurons, how many layers, etc, the answer that kept appearing is that there is no "right" way to go about this, that it is trial and error.  I therefore started with numbers in Canvas's example.  

•	Was target model performance of greater than 75% achieved:

No, first attempt fell short, performance = 72.84%:  

<img width="486" alt="2021-10-30 (5)" src="https://user-images.githubusercontent.com/84471904/139559138-ee7c51d1-428d-4c1f-aa6c-7c6c4bf88d07.png">

•	Steps taken to try and increase model performance:

1.  Add more neurons:

Doubling the nuerons in both layers did not change performance.

<img width="557" alt="2021-10-30 (7)" src="https://user-images.githubusercontent.com/84471904/139559258-2e2b416e-5a0d-4700-990c-32d0e814787a.png">


2.  Add a hidden layer:

Adding another hidden layer decreased accuracy slightly to 72.51%

<img width="511" alt="2021-10-30 (3)" src="https://user-images.githubusercontent.com/84471904/139558753-3f3bcaa1-b0e7-4fa0-88c4-e92cfd984fa2.png">

3.  Use a different activation function for the hidden layers:

Changing the activation function to sigmoid decreased accuracy slightly to 72.68%

<img width="537" alt="2021-10-30 (9)" src="https://user-images.githubusercontent.com/84471904/139559519-4164b076-3b67-431b-ba59-805e25d146b8.png">






