# loan_default_probability_prediction
This is a project that predicts vehicle loan default probability and classify the loan applications into multiple risk categories. There are two scripts, one that cleans and transforms data and does the feature importance comparison. The other selects the list of best features and fits the data to multiple models.


The file: vehicle_loans_cut is the raw data file, with over 100,000 rows.This isn't complete data as it exceeded 25MB limit.

Data Dictionary gives a summary of the headers

Cleaned_Data provides the data file we get after preprocessing

Default_Preprocessing: The python file that accomplishes data cleaning and preprocessing. Also, eliminated major features that aren't informative or eliminated from the mdoel

Default_Modelling: The python file that deals with the major modelling tasks and performance comparison.
