# Data-Analyst-Notes
Formula in Microsoft Excel or Google Sheets that involves more complex data analysis

1. Calculate the Average of a Range:
In Excel:=AVERAGE(B2:B10)
In Google Sheets:=AVERAGE(B2:B10)
2. Count the Number of Entries in a Range:
In Excel:=COUNT(A2:A100)
In Google Sheets:=COUNT(A2:A100)
3. Summarize Data with SUMIFS (Sum with Conditions):
In Excel:=SUMIFS(C2:C100, A2:A100, "Category1", B2:B100, "Condition2")
In Google Sheets:=SUMIFS(C2:C100, A2:A100, "Category1", B2:B100, "Condition2")
4. Calculate the Percentage of Total:
In Excel:=B2/SUM(B2:B10)
In Google Sheets:=B2/SUM(B2:B10)


Cheat sheet with Microsoft Excel formulas that are useful for data analysts:

1. Basic Math Formulas:
- Addition: `=A1 + B1`
- Subtraction: `=A1 - B1`
- Multiplication: `=A1 * B1`
- Division: `=A1 / B1`
2. Averaging:
- Average: `=AVERAGE(A1:A10)`
3. Date and Time:
- Extract Day: `=DAY(A1)`
- Extract Month: `=MONTH(A1)`
- Extract Year: `=YEAR(A1)`
- Current Date: `=TODAY()`
4. Text Manipulation:
- Concatenate: `=CONCATENATE(A1, " ", B1)`
- Length of Text: `=LEN(A1)`
- Upper/Lower Case: `=UPPER(A1)` or `=LOWER(A1)`
5. Logical Functions:
- IF Statement: `=IF(condition, value_if_true, value_if_false)`
- AND: `=AND(condition1, condition2, ...)`
- OR: `=OR(condition1, condition2, ...)`
6. VLOOKUP and HLOOKUP:
- Vertical Lookup: `=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])`
- Horizontal Lookup: `=HLOOKUP(lookup_value, table_array, row_index_num, [range_lookup])`
7. Statistical Functions:
- SUM: `=SUM(A1:A10)`
- COUNT: `=COUNT(A1:A10)`
- MIN/MAX: `=MIN(A1:A10)` or `=MAX(A1:A10)`
- Standard Deviation: `=STDEV(A1:A10)`
- Variance: `=VAR(A1:A10)`
8. PivotTables:
- Create PivotTable: Select your data, go to Insert -> PivotTable
- Drag fields into Rows, Columns, Values, or Filters area
9. Data Cleaning:
- Remove Duplicates: Select data, go to Data -> Remove Duplicates
Number Roundup
ROUND =ROUND(B4,0)
ROUNDUP =ROUNDUP(B4,0)
ROUNDDOWN =ROUNDDOWN(B4,0)
