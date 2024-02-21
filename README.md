Data Processor
This Python script processes data from a CSV file, performs matching operations, and saves the results into separate CSV files for matched and unmatched items.

Overview
The DataProcessor class is designed to:

Load data from a CSV file.
Extract matching criteria from the data.
Group and filter the data based on the matching criteria.
Save the matched and unmatched data into separate CSV files.
Provide statistics on the processed data, including total sum, matched count, and unmatched count.
Usage
To use the DataProcessor class, follow these steps:

Instantiate the class with the file path to the CSV file as a parameter.
Call the process_data() method to perform data processing.
Retrieve statistics using the update_record() method.
Save the output using the save_output() method.
