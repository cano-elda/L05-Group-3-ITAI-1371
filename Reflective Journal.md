Xinyu's Entry:

This lab showed me the importance of data preparation for a machine learning model. In this lab, we dealt with missing values in a dataset. I filled the missing values in the Age column with the median of that column. It showed me that missing values can’t be ignored, as they will affect the rest of the lab as well as analyses done in later labs.

I also learned that the median can be better than the mean to replace missing values in a column. The median is less affected by high values and low values in the data. Thus, it is a better representation of the data if it contains many outliers or is not symmetric. This means that the choice of a missing value replacement also depends on the type of the data in the column.

A second key takeaway from this assignment is the notion of what it means to run cells in a notebook in order. At first, I received an error because I seems that the DataFrame that I had created for the assignment had not been loaded when I ran my own code for the assignment. But running the cells before (in order) worked just fine.



Elda's Entry:

This lab teaches how to get the Titanic dataset ready for a model by filling in missing values, changing categories into numbers, and scaling features.  

The median was used to fill in missing Age values so those rows would not be deleted. Scaling Age and Fare with StandardScaler showed why it’s important  

to place features with different ranges on a similar scale. An important thing that I learned was that negative values do not always mean something is wrong.


Michelle‘s Entry:
In this lab I learned that preprocessing and cleaning the data is a must before doing anything else with it. Raw data usually has missing values and text that a model can't understand, so if we skip this essential step then the model can give wrong results or worst case scenario it won’t run at all. What stood out to me was how much of machine learning is just preparing the data. The part I found hardest to understand was why we drop one of the columns after one-hot encoding. It took me a bit to see that if Sex_male is 0 we already know the person is female so the extra column isn't needed, which leads me to the question when is the correct moment to keep or drop a column?
