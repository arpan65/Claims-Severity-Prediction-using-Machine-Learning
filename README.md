# Claims-Severity-Prediction-using-Machine-Learning

## Business Problem

In the life-cycle of insurance, when the insured incurred a loss and notify the insurer, the process in called FNOL (First Notice of Loss). When a FNOL hits the insurer'system it is important to identify the complexity of the claim. At present general insurance carriers spend almost 40% of the claim life cycle's time in the process of assigning and re-assigning the claims to the adjusters based on changing complexity level and adjuster's experience. 

The ability to correctly predict the cost that can occur in a claim helps both the Insurer and Insured greatly. Insurer can assign the claims to experienced claim adjusters based on severity for faster processing, reserve on claims also set be set properly using a data driven approach.

For example, if a claim is severe it can be assigned to an experienced claim handlers, similarty non severe/ lower complexity claims can be directly channelized to payment. Most of the leading digital P&C products like Guidewire, Duckceek has in-built hook up points to asssign claim's complexity using rule based engines or calling external APIs. So we can also deploy the model as REST endpoints and integrate with the systems easily.


## Business-ML Problem Mapping

We can map this problem with a Regression problem of machine Learning, where we will predict the cost that may occur in the claim and based on the predicted cost we can segment the claim's severity

Machine Learning Problem Class: Regression
Problem Statement: Predict the severity class of the claim based on probable cost
![image](https://user-images.githubusercontent.com/25381042/175468466-a1c8ca2a-3da7-4ea0-8361-e03feefb0f03.png)


## Files Included
Data - contains Allstate claims data (https://www.kaggle.com/c/allstate-claims-severity)

Notebook - ipython notebook, contains the source code for data exploration, feature engineering and modeling techniques

## License
MIT
