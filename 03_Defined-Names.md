# Cell referencing and Naming
Relative referencing - references change for every row
Absolute referencing - Fixed cell reference

# To toggle reference type - Press Fn F4
N2 - relative
$N$2 - absolute

Name box - Variable Names (Named Ranges)

# To select all data - ctrl shift down
Formulas - Defined name
Select All Data and click Define Name
Select Name and adjust range and cope

Create From Selection - automatically create multiple named ranges
Ctrl shift F3 - Select names from values

# Name manager - Select Data and click on name manager
Create, update or delete ranges
Cant change Scope while editing

# Documenting Named Ranges
Use in Formula(F3) - Paste Names - Paste List
Will not automatically update

# Calculations with Named Ranges
Named Range can refer to a constant number

=countif() - single criteria
=countifs(range1,criteria1, range2, criteria2...) - 127 criteria

=sumifs(sum_range1,criteria_range1,criteria1....)
=averageifs
=maxifs
=minifs

# Automating Data Validation
Data Tools - Data Validation
Any Values -> List
Source -> Named Range

# Dynamic Named Range
counta(range) - number of nonempty cells
offset(starting_point,start_rows, start_columns,rows to include ) - returns range that is specified number of rows or columns from a range
