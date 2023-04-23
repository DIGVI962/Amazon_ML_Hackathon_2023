# Amazon_ML_Hackathon_2023


In this solution we have concatenated the DESCRIPTION, BULLET_POINTS and TITLE as our attribute and saved it to TITLE.

We have first cleaned the text in the TITLE column and then victorized it and acquired th TF-IDF score.

We have then utilized the TF-IDF score as independant attributes to train a Logistic regression model.

For the target variable we have taken PRODUCT_LENGTH and Encoded it via LabelEncoder() function.

After training our model we tested it.

Applying this model on the Test dataset we achieved the predicted PRODUCT_LENGTH value in an array.

After entering it into a dataframe along with PRODUCT_ID we have exported the file as a csv and submitted.
