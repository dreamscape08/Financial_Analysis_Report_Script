<p align="center">
  Financial Analysis Script
</p>

<!-- I used the dataset called -- [budget_data.csv] located in (Financial Analysis Report Script/Resources/budget_data.csv)-->

The dataset requires a two column structure,**[Date]/[Profit/Losses]**.

The script analyzes the records to calculate each of the following:

* The total number of months included in the dataset.

* The net total amount of Profit/Losses over the entire period.

* The average of the changes in Profit/Losses over the entire period.

* The greatest increase in profits (date and amount) over the entire period.

* The greatest decrease in losses (date and amount) over the entire period.

**The resulting analysis will look similar to the following:**

  ```text
  Financial Analysis
  ----------------------------
  Total Months: 86
  Total: $38382578
  Average  Change: $-2315.12
  Greatest Increase in Profits: Feb-2012 ($1926159)
  Greatest Decrease in Profits: Sep-2013 ($-2196167)
  ```

The final script should print the analysis to the terminal and export a text file with the results.
