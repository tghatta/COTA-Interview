# COTA-Interview


#This program processes a pre-sorted list of string, divides it into three cols, and print the elements in 3column table. The list is also capable enough to divide as evenly as possible, regardless of it being divisible by 3.


#Logic:
# WE get the base number of elements per column by len(data)//3
# Any remainder is distributed by adding one extra element to the first few columns
