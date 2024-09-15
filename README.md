# ZN Framework - FX Library

## Overview

**FX Library** is a utility package designed for the ZN Framework, providing a variety of helpful functions to assist in tasks such as data manipulation, file handling, database queries, and more. 

## Installation

To integrate the **FX Library**, ensure that the ZN Framework is installed. You can install the library in one of the following ways:

1. **Global Installation (Recommended)**:  
   Place the `FX.php` file in the `External/Libraries/` directory. This allows the FX Library to be shared and used across all projects within your ZN Framework environment.

2. **Project-Specific Installation**:
Alternatively, you can place the `FX.php` file in the `Libraries/` folder of a specific project. This limits the library's usage to that particular project.

By using the global installation method, FX Library becomes accessible across multiple projects, promoting code reuse and ease of maintenance. 
If you need the library restricted to a single project, choose the project-specific installation instead.

## Features

### Database Functions
- **FX::Avg($Column, $Table)**: Returns the average value of a column in a specific table.
- **FX::Sum($Column, $Table)**: Returns the sum of a column in a specific table.
- **FX::CountRows($Table)**: Counts the total rows in a table.
- **FX::WhereCount($Table, $Column, $Value)**: Counts rows where a condition is met.
- **FX::WhereData($Table, $Column, $Value, $Data)**: Retrieves specific data from a table where a condition is met.
- **FX::GetValue($Table, $Value, $ID)**: Fetches a value from a table by ID.

### Data Manipulation & Output
### User & Session Management
### Security & Validation
### Miscellaneous
