# This contains EDA and pipeline formation for cyberbullying dataset (youtub_parserd_dataset)
## To access the pipeline go to pipeline.ipynb to test the pipeline on other dataset for "youtube_parsed_dataset".


**Changes**
## Another file FinalPipeline2.ipynb is made in which we used numerical_columns as test parameters instead of processed_text so as to evaluate Accuracy and AUC scores on it.
## FinalPipeline_Report.ipynb and FinalPipeline2_Report.ipynb are added in which I tried to provide a good explaination of code and its output for both FinalPipeline.ipynb and FinalPipeline2.ipynb respectively.



**Test Resuts**
Random forest : Achieved AUC score of around 0.99 and outperformed every other model in both cases.
Logistic Regression: Achieved an accuracy of approximately 91.9% and an AUC score of about 97.1%, indicating good per
formance in distinguishing between cyberbullying and non-bullying instances.
XGBoost: Outperformed logistic regression with higher accuracy (~94.8%) and AUC score (~98.8%), suggesting superior predictive capabilities.
Decision Tree: Although providing acceptable performance with an accuracy of around 90.1% and an AUC score of about 90.4%, it lags behind logistic regression and XGBoost.


**Change 2**
## LSTM model is integrated in a pipeline. The function is saved inside LSTM_pipeline.ipynb. AUC of 96.5 is obtained using LSTM model. Code description is also provided in the end.


