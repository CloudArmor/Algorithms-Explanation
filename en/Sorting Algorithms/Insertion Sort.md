# Insertion Sort

#### Problem Statement

Given an array of n elements, write a function to sort the array in increasing order.

#### Approach

- Define a "key" index, the subarray to the left of which is sorted.
- Initiate "key" as 1, ie. the second element of array(as there is only one element to left of the second element, which can be considered as sorted array with one element).
- If value of element at (key - 1) position is less than value of element at (key) position; increment "key".
- Else move elements of sorted subarray that are greater than value of element at "key" to one position ahead of their current position. Put the value of element at "key" in the newly created void.

#### Time Complexity

- `О(n^2)` comparisons, `О(n^2)` swaps -- Worst Case

- `O(n)` comparisons, `O(1)` swaps -- Best Case

#### Space Complexity

`O(1)` -- (No extra space needed, sorting done in place)

#### Example

```

12, 11, 13, 5, 6

Let us loop for i = 1 (second element of the array) to 4 (Size of input array)

i = 1.
Since 11 is smaller than 12, move 12 and insert 11 before 12
11, 12, 13, 5, 6

i = 2.
13 will remain at its position as all elements in sorted subarray are smaller than 13
11, 12, 13, 5, 6

i = 3.
5 will move to the beginning,
and all other elements from 11 to 13 will move one position ahead of their current position.
5, 11, 12, 13, 6

i = 4.
6 will move to position after 5,
and elements from 11 to 13 will move one position ahead of their current position.
5, 6, 11, 12, 13  -- sorted array
```

#### Code Implementation Links

- [Assembly](https://github.com/CloudArmor/AArch64_Assembly/blob/main/sorters/insertion_sort.s)
- [C](https://github.com/CloudArmor/C/blob/master/sorting/insertion_sort.c)
- [C#](https://github.com/CloudArmor/C-Sharp/blob/master/Algorithms/Sorters/Comparison/InsertionSorter.cs)
- [C++](https://github.com/CloudArmor/C-Plus-Plus/blob/master/sorting/insertion_sort.cpp)
- [Dart](https://github.com/CloudArmor/Dart/blob/master/sort/insert_Sort.dart)
- [Elixir](https://github.com/CloudArmor/Elixir/blob/master/lib/sorting/insertion_sort.ex)
- [Elm](https://github.com/CloudArmor/Elm/blob/master/src/Sorting/InsertionSort.elm)
- [F#](https://github.com/CloudArmor/F-Sharp/blob/main/Algorithms/Sort/Insertion_Sort.fs)
- [Go](https://github.com/CloudArmor/Go/blob/master/sort/insertionsort.go)
- [Haskell](https://github.com/CloudArmor/Haskell/blob/master/src/Sorts/InsertionSort.hs)
- [Java](https://github.com/CloudArmor/Java/blob/master/src/main/java/com/thealgorithms/sorts/InsertionSort.java)
- [JavaScript](https://github.com/CloudArmor/JavaScript/blob/master/Sorts/InsertionSort.js)
- [Julia](https://github.com/CloudArmor/Julia/blob/main/src/sorts/insertion_sort.jl)
- [Kotlin](https://github.com/CloudArmor/Kotlin/blob/master/src/main/kotlin/sort/InsertionSort.kt)
- [Lua](https://github.com/CloudArmor/Lua/blob/main/src/sorting/insertionsort.lua)
- [Matlab](https://github.com/CloudArmor/MATLAB-Octave/blob/master/algorithms/sorting/insertion_sort.m)
- [PHP](https://github.com/CloudArmor/PHP/blob/master/Sorting/InsertionSort.php)
- [Python](https://github.com/CloudArmor/PyAlgorithms/blob/master/sorts/insertion_sort.py)
- [R](https://github.com/CloudArmor/R/blob/master/sorting_algorithms/insertion_sort.r)
- [Ruby](https://github.com/CloudArmor/Ruby/blob/master/sorting/insertion_sort.rb)
- [Rust](https://github.com/CloudArmor/Rust/blob/master/src/sorting/insertion_sort.rs)
- [Scala Iterative](https://github.com/CloudArmor/Scala/blob/master/src/main/scala/Sort/InsertionSort.scala)
- [Scala Recursive](https://github.com/CloudArmor/Scala/blob/master/src/main/scala/Sort/RecursiveInsertionSort.scala)
- [Swift](https://github.com/CloudArmor/Swift/blob/master/sorts/InsertionSort.swift)
- [TypeScript](https://github.com/CloudArmor/TypeScript/blob/master/sorts/insertion_sort.ts)

#### Video Explanation

[A CS50 video explaining the Insertion Search Algorithm](https://www.youtube.com/watch?v=DFG-XuyPYUQ)
