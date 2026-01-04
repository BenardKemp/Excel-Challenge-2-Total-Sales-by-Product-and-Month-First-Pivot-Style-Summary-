# SolveWithExcel – Challenge #2
## Total Sales by Product and Month (Pivot-Style Summary with Formulas)

This challenge focuses on building a month-based sales summary in Excel using formulas instead of Pivot Tables. You will group transaction data by product and month and construct a clean, dashboard-ready report using SUMIFS.
This mirrors real-world reporting scenarios where Excel is used as a lightweight analytics tool.

Difficulty
Beginner → Early Intermediate

Estimated Time
15–25 minutes

# The Problem

You are given transaction-level sales data.
Management wants to see monthly sales totals per product, plus overall monthly totals.

# Your task is to:

Convert transaction dates into month buckets
Calculate sales amounts per row

Build a pivot-style summary table using formulas
No Pivot Tables are required for this challenge.

# Dataset

SalesData columns:

Date
Product
Quantity
Unit Price

Products:

Laptop
Mouse
Keyboard

Months covered:

January 2025
February 2025
March 2025

# Your Tasks

## 1. Calculate Sales Amount

Add a calculated column:

Sales Amount = Quantity × Unit Price

## 2. Create a Month Column

Convert each date into a month bucket such as:

2025-01
2025-02
2025-03

## 3. Build the Monthly Summary

Create a summary table with:

Rows: Month
Columns: Product

Values: Total Sales Amount
A final column summing each row

Each cell should be calculated using formulas.

# Requirements

Use Excel formulas only
Do not use Pivot Tables
The summary must update automatically when data changes
Avoid hard-coded totals

Expected Results

January 2025
Laptop: 2700
Mouse: 140
Keyboard: 135
Total: 2975

February 2025
Laptop: 1800
Mouse: 200
Keyboard: 90
Total: 2090

March 2025
Laptop: 1800
Mouse: 80
Keyboard: 45
Total: 1925

# Learning Objectives

By completing this challenge, you will practice:
Bucketing dates into months
Using SUMIFS for multi-condition aggregation
Building pivot-style summaries with formulas
Structuring Excel reports for dashboards

Files Included

solvewithexcel_challenge_2_solution_hidden.xlsx
→ Blank calculation cells for learners

solvewithexcel_challenge_2_solution_revealed.xlsx
→ Completed formulas for reference

# Next Challenge

In the next challenge, you will:

Add dynamic filtering
Prepare this summary for a dashboard-style layout
Compare formula-based summaries with Pivot Tables

# About SolveWithExcel

SolveWithExcel focuses on solving real-world business problems using Excel.
Learn more at https://solvewithexcel.org
