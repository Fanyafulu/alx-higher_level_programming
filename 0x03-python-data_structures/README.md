sts

Python knows a number of compound data types, used to group together other values. The most versatile is the list, which can be written as a list of comma-separated values (items) between square brackets. Lists might contain items of different types, but usually the items all have the same type.



>>>

squares = [1, 4, 9, 16, 25]

squares

[1, 4, 9, 16, 25]

Like strings (and all other built-in sequence types), lists can be indexed and sliced:



>>>

squares[0]  # indexing returns the item

1

squares[-1]

25

squares[-3:]  # slicing returns a new list

[9, 16, 25]

All slice operations return a new list containing the requested elements. This means that the following slice returns a shallow copy of the list:
