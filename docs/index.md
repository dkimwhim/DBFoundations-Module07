# Explain Functions
*Daniel Kim  *
*August 21, 2020  *
*Foundations of Database  *
*Assignment 07  *

## Introduction
In this document, I will be answering two questions:
1. Explain when you would use a SQL UDF.
2. Explain are the differences between Scalar, Inline, and Multi-Statement Functions.

## Explain when you would use a SQL UDF.
If the SQL Server’s built-in-functions are insufficient to generate the desired end query, we must build UDF (User Defined Functions). We can incorporate built-in-functions into our UDFs.

## Explain are the differences between Scalar, Inline, and Multi-Statement Functions.
We use scalar functions to return a single value whereas inline and multi-statement return a table. An inline and multi-statement functions can be similar in their end results with the difference being the syntax and more importantly the use of multiple statements in the latter. In a multi-statement function, the table must be defined at the start.

## Summary
Functions provide the customizability in formatting the data to present to end users for reporting and analytical inquiries.

## Citations
- https://database.guide/what-is-a-table-valued-function-in-sql-server/
- University of Washington IT Foundations 130 Modules
