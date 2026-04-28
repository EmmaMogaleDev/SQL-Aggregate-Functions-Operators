# BrightLearn — Exercise 02: SQL Aggregate Functions & Operators

This repo contains my handwritten notes and answers for Exercise 02 of the BrightLearn Basic SQL course. The exercise focuses on aggregate functions and operators — 15 queries written by hand across 5 tables, with the expected output drawn out for each one.

The tables cover students, courses, enrolments, salaries, and projects, and the queries get progressively more involved as the exercise goes on.

## What I worked on

The exercise covers `COUNT`, `SUM`, `AVG`, `MIN`, `MAX`, `GROUP BY`, `HAVING`, `DISTINCT`, `BETWEEN`, `IN`, `ORDER BY`, and `LIMIT`. Each question asks you to write the SQL and then predict the exact output before checking — which really forces you to think through what the query is actually doing row by row.

## What I learned the most

The biggest thing that clicked for me was the difference between `WHERE`, `GROUP BY`, and `HAVING` and how they work together in the right order. Before this exercise I was confusing when to use `WHERE` versus `HAVING` — now I understand that `WHERE` filters rows before any grouping happens, while `HAVING` filters the groups themselves after `GROUP BY` has run. Question 6 in particular made that distinction very clear.

I also got a lot more comfortable with aliasing aggregate results using `AS`, and doing simple arithmetic like `salary + bonus` directly inside a query without needing a separate column in the table.
