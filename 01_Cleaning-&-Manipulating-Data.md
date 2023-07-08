[] - optional arguments

Functions for joining data
=concatenate(A!,”_”,B1) - upto 255 arguments
=(A1&B1&C1) - concatenate operator
=concat(A1:D1) - selects a range of adjacent cells
=textjoin(delimiter,ignore_empty_cell, text1, text2) -combines with advanced options

Functions for splitting data
=left(original_text , num_of_chars) - returns left characters
=right(original_text , num_of_chars) - returns right characters
=mid(original_text , start_num(inclusive) , num_of_chars) -returns middle characters

Combining Text Functions
=find(find_text , within_text , [start_num])
=len(text)

Cleaning Data and Changing case
=clean(text) - strips non printable text(first 32)
=trim(text) - removes extra spaces
=upper(text) - uppercase
=lower(text) - lowercase
=proper(text) - capitalises first letter

Removing and replacing text
=substitute(text, old , new, [instance]) - replaces text
=unicode(character) - returns ASCII value of character
=unichar(value) - returns character for given ASCII value
