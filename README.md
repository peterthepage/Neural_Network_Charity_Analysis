# Neural_Network_Charity_Analysis
## Overview
This module's goal was to preprocess data for a neural network. I compiled, trained, and evaluated the model in order to optimize it.

## Results
### Data Oreprocessing
* EIN and NAME columns were the first to be removed. They were indentity information and therefore unnecessary.
* IS_SUCCESSFUL was removed next because that is what we were testing for.
* Next was taking the data I had left to split into training and testing sets to create the model.
### Compile, Train, and Evaluation of Model.
* Once preprocessing was complete the input data contained over 25,000 samples with 43 features.
* The model accuracy did not reach 75%. With more time and layers I'm confident this could be achieved.
### Summary
While never reaching 75% accuracy this model can not be considered outperforming. The situation is a binary classification situation, therefore a supevised machine learning model would be best. I would recommend a Random Forest Classifier to evaluate the performance against the deep learning model created.
