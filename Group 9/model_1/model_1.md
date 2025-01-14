# Model 1

### Running the model
In order to run the model you should include all the features from `investigation_train_large` dataset, 
but you should drop the `Ja`, `Nee` and `checked` column. 


### Testing the model
We recommend you test the model on the following categories:
1. Usual performance metrics, including precision, recall, F1 score, etc.
2. Fairness metrics such as equal opportunity and predictive equality which can show possible biases
 on sensible categories such as age, gender etc.
3. Resilience to noise.