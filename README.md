# Organizational Risk Watchlist

## Overview

The Organizational Risk Watchlist is a beginner-level Python project designed to classify organizations based on their risk scores.

The program collects information for five organizations, assigns each organization to either a high-risk or low-risk category, and calculates the average risk score for each group.

This project builds on foundational Python concepts while introducing basic data organization and analysis.

## Features

* Collects organization names through user input
* Collects numerical risk scores
* Classifies organizations as:

  * **High Risk:** Risk score ≥ 70
  * **Low Risk:** Risk score < 70
* Stores organizations in separate high- and low-risk lists
* Stores risk scores in corresponding lists
* Counts the number of organizations in each category
* Calculates the average risk score for each category
* Handles situations where there are no organizations in a category

## Python Concepts Used

* Variables
* User input with `input()`
* Type conversion with `int()`
* Lists
* `.append()`
* `if/else` conditional statements
* Comparison operators
* `len()`
* `sum()`
* Basic arithmetic and averages

## Example

A user might enter:

```text
Organization 1: Northstar Compliance Group
Risk Score: 45

Organization 2: Blue Harbor Technologies
Risk Score: 82

Organization 3: Piedmont Financial Services
Risk Score: 65

Organization 4: Summit Health Systems
Risk Score: 91

Organization 5: Atlas Environmental Solutions
Risk Score: 30
```

The program would classify the organizations and produce results similar to:

```text
High Risk Organizations: ['Blue Harbor Technologies', 'Summit Health Systems']
Number of High Risk Organizations: 2

Low Risk Organizations: ['Northstar Compliance Group', 'Piedmont Financial Services', 'Atlas Environmental Solutions']
Number of Low Risk Organizations: 3

Average high risk score: 86.5
Average low risk score: 46.67
```

## Purpose

I built this project as part of my process of developing foundational Python skills and exploring how programming can be applied to areas such as risk analysis, compliance, research, and organizational decision-making.

The project is intentionally built with basic Python rather than advanced libraries or frameworks. The next stage of development will focus on improving the program's efficiency using loops and functions, followed by working with larger datasets and tools such as Pandas and SQL.

## Future Improvements

Potential future versions could:

* Use `for` loops to eliminate repetitive code
* Use functions to organize the program
* Allow users to analyze more than five organizations
* Read organizational data from a CSV file
* Use Pandas for larger datasets
* Add additional risk factors
* Generate summary reports or visualizations
* Connect the analysis to a database using SQL

## Author

Built as an independent Python learning project.
