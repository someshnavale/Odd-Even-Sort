# Odd-Even-Sort

Pseudo code for Odd-Even Sort:
if n>2 then
 1. apply odd-even merge(n/2) recursively to the even subsequence a0, a2, ..., an-2 and to the
odd subsequence a1, a3, , ..., an-1
 2. comparison [i : i+1] for all i element {1, 3, 5, 7, ..., n-3}
else
 comparison [0 : 1]
