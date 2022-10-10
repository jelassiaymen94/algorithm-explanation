# algorithm-explanation

# 3- Linear Search

linear Search is an algorithm we can use to find an element in an array.

Linear search algorithm works as follow

1 - Iterate across the array from left to right, looking for the element
2 - If the first element is what you're looking for, stop .
3 - Otherwise move to the next element and keep going until you find the element, or you don't.

Time Complexity of Linear Search Algorithm is O(n).
Here, n is the number of elements in the linear array.

# 3-1 Linsear Search Pseudocode

```
Begin
for i = 0 to (n - 1) by 1 do
if (a[i] = item) then
set loc = i
Exit
endif
endfor
set loc = -1
End

```
