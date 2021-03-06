# Tidying the Data Codebook
## Original Data
Source at: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The data is a series of readings from the accelerometer and gyroscope readings in smartphones kept on experiment participants during various physical activities.

## Data Sets

The original data features over 500 measurements and derivations taken from the sensors on the phones. The tidy data set created by this program extracts 79 of those which were deemed relevant to what we were looking for. 

The data in this set is an average of the data from the raw set with respect to a test subject and the activity performed--i.e. all measurements taken while subject 4 wasl laying down are averaged together into a single mean average value.

## Variable Names

**Names of the measurements were kept almost identical to the originals**, but special characters ("(",")","-") were removed, and the variables were camel-cased for readability. For in-depth information on the exact meaning of the variables themselves, please see the files included in the data by the researchers.


