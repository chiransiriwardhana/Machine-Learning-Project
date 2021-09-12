# Machine-Learning-Project

# Feature Engineering
1. Find duplicate rows and remove them
2.Find columns which contains NaN and replace NaN values using mode 
Change values less than 25 in funder and installer column to 'others'
Use target encoding to covert non-numerical columns to numerical columns
Exatract month and year from "date_recorded" column and create new columns called month and year
Perform log normalization for population column
Convert 0 value in funder column to "others"
Encode label set ( convert "non functional", "functional needs repair", and "functional" to 0, 1, and 2)
Do target encoding for non-numerical columns.
permit and public_meeting columns contain boolean values. Therefore True and False in permit and public_meeting columns are converted to 1s and 0s
perform onehot encoding for permit and public_meeting columns.
provided dataset is unbalanced. So, SMOTE is used to handle unbalanced dataset
datset is normalized before using the XGB classifier.

use XGB classifier and catboost classifier to clssify. However XGB classifier gives better result. Therefore final results are generated using XGB classifier
