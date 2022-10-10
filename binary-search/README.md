# algorithm-explanation

# 2- Binary Search

Binary search is an algorithm for finding an element in a sorted array by continuously dividing the search area in half.

An example is looking for a word in a dictionary(Binary), you wouldn't look in every page until you find the word Binary, instead you open it in the middle and see if it's on the right or left side then you repeat the same steps until finaly you find the page you're looking for

## 2- 1 Binary Search Pseudocode

```
Procedure binary_search
   A ← sorted array
   n ← size of array
   x ← value to be searched

   lowerBound : 1
   upperBound : n

   while x not found
      if upperBound < lowerBound
         EXIT: x does not exists.

      set midPoint = lowerBound + ( upperBound - lowerBound ) / 2

      if A[midPoint] < x
         set lowerBound = midPoint + 1

      if A[midPoint] > x
         set upperBound = midPoint - 1

      if A[midPoint] = x
         EXIT: x found at location midPoint
   end while

end procedure

```
