# THIS REPOSITORY CONTAINS GHANA-19 DATASET AND VARIOUS HEAD-START PROJECTS TO WET YOUR APPETITE FOR FUTURE RESEARCH

### The Dataset

This sub-repository contains Ghana Covid-19 datasets. This dataset is recorded region-wise, meaning each row corresponds to a particular region of the 16 regions. This region-wise categorization will help you easily do exploratory analyses and predictive modelling on regional basics.
This dataset is extracted from the Ghana Health Service covid19 page and been pre-processed ,reshaped into commas separated text file.


### Content
This Dataset contains 6 different columns as described below:

- region : This contains the names of all the 16 administrative regions in Ghana.
- accum_case: This column contains the accumulative number of cases recorded in each region.
eg. region1 case. case = addition of previous case + current recorded case.
- recovered: This is the accumulative region-wise recovered cases.
- recovered_per: Is the percentage(over 100) of the number of recorded cases.
- active_case: This the number of active cases in the region.
eg. active_case = case-recovered-number of deaths.
- date : The death columns obviously contains the date ( yyyy-mm-dd) for the particular entry.
- new_case: This column records the daily positive cases of covid-19.




### Acknowledgements

- Ghana Health Service.
- Snagit OCR

### Inspiration

The main reason of this dataset is to inspire various Data Scientists to find solutions to these questions
- What is the main contribution factor for the covid-19 spread in Ghana?
- Can we know the number of cases to be recorded maybe one-week ahead of time so we do necessary preparation before-hand?

### Disclaimer
This data is extracted from the official Ghana Health Service website for educational and research purposes.
Whiles we endeavor to keep this data up to date and correct, we make no representations,warranties of any kinds,express or implied about the accuracy, adequacy, completeness, legality, reliability or usefulness of any information. This disclaimer applies to both isolated and aggregate uses of the information. The information is provided on an "as is" basis and few features extracted from the original data.
Any reliability you put on this data is strictly at your own risk. For any validation and verification, we recommend you to go the [official GHS website](https://www.ghanahealthservice.org/covid19/)
