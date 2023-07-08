IF - =,<,<=,>,>=,<>
=if(condition,truevalue,falsevalue)
=and()
=or()

Vlookup - references a vertical table to find and return values
values have to be in first columns of original dataset
=vlookup(value, yable_array , col_index , [approx/exact_ match])
true - approx, false - exact

Xlookup - both v&h and advanced features 
=xlookup(lookup_value, lookup_array, return_array, [if_not_found])

Advanced Data Matching
index - returns a value in a list or table based on coordinates
=index(array, row_num, [column_num])

match - locates the position of a lookup in a row, column or table
=match(lookup_value, lookup_array, [match_type])

VLOOKUP cannot be used when the value you wish to return is to the left of the lookup value. 
