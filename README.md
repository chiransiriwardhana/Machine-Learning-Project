# Machine-Learning-Project


# Feature Engineering

1. Find duplicate rows and remove them.

2. Find columns which contains NaN and replace NaN values using mode. 

3. Change values less than 25 in funder and installer column to 'others'.

4. Use target encoding to covert non-numerical columns to numerical columns.

5. Exatract month and year from "date_recorded" column and create new columns called month and year

6. Perform log normalization for population column

7. Convert 0 value in funder and installer columns to "others"

8. First calculate uncertainity coefficient to identify most related features then remove less related columns from train and test sets

9. Encode label set ( convert "non functional", "functional needs repair", and "functional" to 0, 1, and 2)

10. Do target encoding for non-numerical columns.

11. permit and public_meeting columns contain boolean values. Therefore True and False in permit and public_meeting columns are converted to 1s and 0s

12. perform onehot encoding for permit and public_meeting columns.

13. provided dataset is unbalanced. So, SMOTE is used to handle unbalanced dataset

14. Normalize the train and test sets before fed into XGB classifier.(but it reduce accuracy)

15. datset is normalized before using the XGB classifier.

16. use XGB classifier and catboost classifier to clssify. However XGB classifier gives better result. Therefore final results are generated using XGB classifier



# Other works

1. Plot bar chart for label set and identify behavior of dataset. (dataset is imbalanced)

2. Plot confusion matrix

3. Perform K-fold cross validation

4. Use XGB classifier and Catboost classifier
