# Assignment #7 – Functions

**Dev:** *SHuang*

**Date:** *5.31.2022*

## Introduction
In the seventh week of the course IT Foundations of Database Management, 
we learned about Functions including their usages and how to write them.
## When to use a SQL UDF
A User Defined Function, or UDF, is a custom function that a user can create. 
These are helpful if the user needs to use a function not available from SQL server’s built-in functions. 
UDFs can also be stored. In cases where the user is using a series of functions which 
become increasingly complex, it’s useful to utilize a UDF to write the 
function once and store it for repeated use.
## Scalar, Inline, and Multi-Statement Functions
The three main types of functions are the scalar, inline, and multi-statement functions. 
Scalar functions are functions that let the user bring back a single value. 
In contrast, inline and multi-statement functions will return a table of results when called on.

Inline and multi-statement functions differ in that multi-statement function can have multiple 
statements and has a more rigid structure. Inline functions do not require 
the usage of BEGIN and END blocks or the usage of the RETURN operator.
However multi-statement functions do.
## Summary
Functions in SQL allow the user to do “work” with data within a database. 
The user can modify data in tables, parse or combine data, 
and create custom functions for more complex tasks.
