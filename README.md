# Module-Challange-12

# Module 12 Report Template

## Analysis Overview of Machine Learning Models

## Objective of the Challenge:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variable predictions (ex: `value_counts`).
* Describe the stages of the machine learning process as part of this analysis.
* Briefly describe methods used (ex:`LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  
  <img width="303" alt="image" src="https://user-images.githubusercontent.com/105945472/184495465-d042b684-767e-4b33-8d57-27c803bf493d.png">

* Model 1 Conclusion: 
  The Logistic Regression Model predicted a imbalance of '0' healthy loans. 

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  
  <img width="299" alt="image" src="https://user-images.githubusercontent.com/105945472/184495630-3d94589d-dc16-4f98-abc6-f7c949ac9b8f.png">

* Model 2 Conclusion:
  The RandomSampler model doesn't look to have any changes in data compared with respect to the Logistic Regression Model.

## Summary
Depending on your data needs I don't beleive one model is a better preformer than the other. However, if there is a strong imbalance is data then implementing a Random Sampler model would be a great resource to use to compare and confirm agaisnt the Logistic Regression Model. Use of these models are depenent on the problems your trying to solve.
