# Microsoft-Power-BI-Table-Functions

![ScreenShot](https://github.com/NavarroAlex/NORAM-Microsoft-Power-BI-Training/blob/main/Power%20BI%20Theme.png)

## Author
[alex.navarro@danone.com]

## Table Functions:
* Basic Functions that work on "Full" tables:
    - FILTER
    - RELATEDTABLE
    - ALL
    - VALUES
    - DISTINCT
* Their result is often used in other functions.
* They can be combined together to form complex expressions

### FILTER Table:

#### Link to Microsoft DAX Documentation:
[https://learn.microsoft.com/en-us/dax/filter-function-dax]
* filter the table based on some criteria and only the rows that meet the set condition will be returned.

#### Syntax:
```FILTER(<table>,<filter>)```