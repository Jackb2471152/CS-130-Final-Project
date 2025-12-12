## Data Source:
I used Kaggle to find the dataset.
* https://www.kaggle.com/datasets/trolukovich/football-players-salaries?resource=download

## Data Preparation/Cleaning:
* * Removed rows that have value 0 for age, total value, avg year, total guaranteed, fully guaranteed. 
* Organized each player by position group. 
* Removed any duplicated players. 
* Renamed corner-backs and safety's to defensive-backs since players play multiple positions. 
* Renamed 3-4-outside-linebackers, 4-3-outside-linebackers and inside-linebackers to linebackers since players play multiple positions. 
* Renamed 4-3-defensive-end, 3-4-defensive-end, 4-3-defensive-tackle and 3-4-defensive-tackle to defensive-line since players play multiple positions. 
* Figured out how many players there were per position. 
## Assumptions:
* * Assumed that this data set is from 2019 since it was posted on Kaggle 6 years ago.  
* Assumed that this data is accurate.  
* Assumed some position titles were used interchangeably, so the rolls were combined.  
## Limitations:
* example
