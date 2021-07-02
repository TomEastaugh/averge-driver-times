# AverageDriverTimes 

An app that reads a csv file of lap times (`driver,time`), calculates the top 3 drivers by average lap time,
and writes them to a local file.

## Running Test
To run all the test execute the following command `sbt test`

## Improvements
As I have treated this app as a task that should not be overly complicated.
Below is a list of improvement I would implement if the task required.   

- Return a list of all errors when trying to extract LapTimes from CSV lines.
- Validate incoming csv has the correct number of columns.
- Validate incoming driver times to ensure they are valid decimals.
- Round the average time produced in the output file.
