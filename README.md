# Microsoft-Power-BI-Data Analysis Expression Basics

![ScreenShot](https://github.com/NavarroAlex/NORAM-Microsoft-Power-BI-Training/blob/main/Power%20BI%20Theme.png)

## Author
[alex.navarro@danone.com]

## What is DAX?:
* Language of:
    - Microsoft Power Pivot
    - Microsoft Power BI
    - SSAS Tabular
* Resembles Microsoft Excel:
    - Because it was born with PowerPivot, in 2010.
* Important Differences:
    - No concept of "Row" and "Column"
    Different Type System:
* Sophisticated Functions:
* Designed for data models and business intelligence calculations.

## DAX Formatter:
[https://www.daxformatter.com]

## DAX Type:
* Numeric Types:
    - Integer(64)
    - Decimal (floating point)
    - Curreny (money)
    - DATE (DateTime)
    - TRUE/FALSE (Boolean)
* Other Types:
    - String
    - Binary Objects

## Basic Aggregation Functions and CALCULATE:
* CALCULATE
* SUM
* DIVIDE
* AVERAGE
* MIN
* MAX

### CALCULATE:
* Definition:
    - Evaluates an expression in a modified filter context.
Syntax:
```
CALCULATE(<expression>[, <filter1> [, <filter2> [, …]]])
```
* Link to documentation:
    - [https://learn.microsoft.com/en-us/dax/calculate-function-dax]

### SUM:
* Definition:
    - Adds all the numbers in a column.
Syntax:
```
SUM(<column>)
```
* Link to documentation:
    - [https://learn.microsoft.com/en-us/dax/sum-function-dax]

### DIVIDE:
* Definition:
    - Adds all the numbers in a column.
Syntax:
```
DIVIDE(<numerator>, <denominator> [,<alternateresult>])
```
* Link to documentation:
    - [https://learn.microsoft.com/en-us/dax/best-practices/dax-divide-function-operator]