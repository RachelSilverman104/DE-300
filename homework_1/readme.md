Open the file in your workspace and run each code block sequentially.

Question 1).

North American Airlines CARRIER and UNIQUE_CARRIER:

The table shows that the CARRIER and UNIQUE_CARRIER columns have NaN values for several rows.
After remedying the problem, the next table shows that the number of null values for CARRIER and UNIQUE_CARRIER have decreased by the number of null values due to North American Airlines.

CARRIER_NAME, AIRLINE_ID, UNIQUE_CARRIER, and UNIQUE_CARRIER_NAMES:

The first table shows the data for which at least one of the four previous mentioned columns has missing data.
The next table shows that for each Model used by OH, there is only one combination of values used for the four mentioned columns.
The next table shows the number of null values in each column, demonstrating that the four mentioned columns have been imputed.
The last table double checks that the imputation was done correctly by showing that there is still a unique combination of values used for each model type in OH.

NUMBER_OF_SEATS:

The first table shows the data for all rows with a missing number of seats.
The last table shows the number of missing values per column, demonstrating that the number fo seats have been successfully imputed.

MANUFACTURE_YEAR:

The first table shows the data for all rows with a missing manufacture year.
The last table shows a correlation matrix for the numerical data types.

CAPACITY_IN_POUNDS:

The first histogram shows the distribution of the CAPACITY_IN_POUNDS values across the dataset.
The second set of histograms show the distribution of the CAPACITY_IN_POUNDS values by models, which have missing CAPACITY_IN_POUNDS values.
The next histogram shows the imputed versus unimputated values of capacity across the whole dataset.
The last set of histograms show the imputed versus unimputed values of capacity by model.

Question 2).

OPERATING_STATUS:

The first table shows the value counts of OPERATING_STATUS before standardization of values.
The second table shows the data for the row having OPERATING_STATUS == " "
The third table shows the data for rows surrounding the row mentioned in the second table.
The last table shows the value counts of OPERATING_STATUS after standardization of values.

AIRCRAFT_STATUS:

The first table shows the value counts of AIRCRAFT_STATUS before standardization of values.
The last table shows the value counts of AIRCRAFT_STATUS after standardization of values.

MANUFACTURER:

Each table shows the value counts of MANUFACTURER after the standardization of a manufacturer name in the code block prior to the table.

MODEL:

The first table shows the value counts of MODEL before standardization of names.
The next two tables show the value counts of MODEL after the standardization of model names in the code block prior to the table.

Question 4).

The first set of histograms show the distribution of NUMBER_OF_SEATS and CAPACITY_IN_POUNDS, respectively.
The second set of histrograms show the distribution of NUMBER_OF_SEATS and CAPACITY_IN_POUNDS after the Box-Cox tranformation.

Question 5).

The first graph shows the proportion of operating status values by aircraft size.
The second graph shows the proportion of aircraft status values by aircraft size.


