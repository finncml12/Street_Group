# Street_Group
Technical assessment for Street Group

Thank you for taking the time to review the work that I have done.

For the task, I chose to explore linear regression, random forest and XGBoosted trees models using Python. However, I unfortunately had technical issues when trying to run the XGBoosted trees, and I didn't have enough time then to fix the issue to then successfully use the method.

The final model I produced is saved as final_model.pkl. I have included a small script which contains the code to use the model without having to run all of the code. The data to be used by model needs to be read into the script. I have included 2 sections of code to do that, one that reads in json data from an API, and the other that reads the json data from a local area.

Once the data has been read in, one-hot encoding needs to be applied to the property_type column, to convert it to a numeric format for use in the model. The data can then be fed into the model, and predictions can be obtained.
