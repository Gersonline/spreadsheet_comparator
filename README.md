# Spreadsheet Comparator

Spreadsheet Comparator is an idea of a program to compare spreadsheets with python using pandas.

## Example:

### TABLE 1

| PLACE   | COLUMN B | COLUMN C  |
| ------- | -------- | --------- |
| HOUSE A | 123      |  STREET 1 |
| HOUSE B | not int  |  STREET 2 |
| BUILD   | 789      |  STREET 3 |


### TABLE 2

| PLACE   | COLUMN B |
| ------- | -------- |
| HOUSE A | 123      |
| HOUSE B | 456      |
| BUILD   | 789      |


### TABLE DIFERENCES

| PLACE     | COLUMN B    | ~~COLUMN C~~  |
| --------- | ----------- | ------------- |
| HOUSE A   | 123         |  STREET 1     |
| HOUSE B   | **not int** |  STREET 2     |
| **BUILD** | 789         |  STREET 3     |


- [Spreadsheet Comparator](#spreadsheet-comparator)
  - [Example:](#example)
    - [TABLE 1](#table-1)
    - [TABLE 2](#table-2)
    - [TABLE DIFERENCES](#table-diferences)
