#Functions

##Introduction
This module focused on Functions. There are different types of functions with different purposes. Many of the functions that we have already used are System Functions – they are built into the SQL Server system and can’t be modified. There are some Aggregate functions built in, such as COUNT, SUM, MAX, MIN, and AVG. There are some conversion functions, such as CAST and CONVERT, and many other useful functions which are part of the SQL system. We learned how to use a lot of these, but we also learned to create our own functions when there was no ready-made built-in Function to do the task needed.

##When to Use a User Defined Function
User Defined Functions are very useful when you might want to reuse some code that can accept parameters. Views are also useful for re-use, but can’t take parameters, so that is where UDFs come in handy. UDFs can either be Scalar (returning a single value) or Tabular (returning a table of values). They can take one or more parameters, and they can be used inside other SQL scripts, stored procedures, and functions.  
