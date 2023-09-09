# Deep-Learning-Challenge

Overview of the Analysis
- The purpose of this assignment was to build a model that would predict the success of a charity named Alphabet Soup.

Results
* The variale which is the target of the model is a column titled "IS_SUCCESSFUL" as we wanted to discover what would be successful or not successful for this organization.
* The features of the model are the rest of the columns that give more information, such as "CLASSIFICATION", "INCOME_AMT", etc.
* The data that was removed from the model was "EIN" and "NAME"

Compiling, Training, and Evaluating the Model
* The first time running this model I did two layers with 100 neurons, then 80 neurons while using the ReLU activation function.  In my next attempt I added a third layer with 60 neurons, which also utilized the ReLU activation function.  This did not improve the accuracy.  My final attempt I increased the neurons to 180, 140 and 100 and there was still no improvement to the accuracy.

Summary
* My attempts were not successful with this model, in the future I would attempt to drop other columns to see if that makes any improvement.  I think I would have also attempted to use previous machine learning algorithm, classical machine learning may have given better results. 
