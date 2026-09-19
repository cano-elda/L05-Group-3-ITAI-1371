Xinyu's Entry:

Working with this lab helped me understand that data preparation is an important step when preparing a dataset for a machine learning model. Because a model is trained with the data provided, any missing or inappropriately prepared data will negatively affect the model and any resulting predictions made by the model. I worked with missing data in the “Age” column for this part of the lab and used median imputation for the missing data. After imputing the missing data, I checked the “Age” column to verify that there were no missing values left in the column.

I also learned that instead of using the mean for imputing the missing values in numerical data, it is better to use the median. This is because the mean is strongly affected by very high or very low values in a skewed distribution, whereas the median is not. Therefore, for a skewed distribution with very high or very low values, it is better to use the median instead of the mean. This also means that instead of using the same method for all missing values in a data set, we should look at the distribution of the feature and decide whether it is appropriate to use that method for that feature.

Preprocessing can also affect how a machine learning model works. In this case, by imputing missing Age values, we ensured that all samples with any amount of information can be used for training a model, rather than having to exclude whole rows of data. However, the imputation method used here has the severe limitation that every missing Age value is replaced by the same value. This leads to a loss of information in cases where there is real variation in the ages of passengers who are missing. Future versions of this model could benefit from a comparison with other imputation methods and possibly from incorporating further information about the passengers.


Elda's Entry:

This lab teaches how to get the Titanic dataset ready for a model by filling in missing values, changing categories into numbers, and scaling features.  

The median was used to fill in missing Age values so those rows would not be deleted. Scaling Age and Fare with StandardScaler showed why it’s important  

to place features with different ranges on a similar scale. An important thing that I learned was that negative values do not always mean something is wrong.


Michelle‘s Entry:

In this lab I learned that preprocessing and cleaning the data is a must before doing anything else with it. Raw data usually has missing values and text that a model can't understand, so if we skip this essential step then the model can give wrong results or worst case scenario it won’t run at all. What stood out to me was how much of machine learning is just preparing the data. The part I found hardest to understand was why we drop one of the columns after one-hot encoding. It took me a bit to see that if Sex_male is 0 we already know the person is female so the extra column isn't needed, which leads me to the question when is the correct moment to keep or drop a column?
