# Selection Sort

#### Problem Statement

Given an unsorted array of n elements, write a function to sort the array

#### Approach

- select the smallest element from the array
- put it at the beginning of the array
- then select the smallest array from the remaining unsorted list
- append it to the sorted array at the beginning
- keep doing this for every element of the array
- repeat the above process n times

#### Time Complexity

`O(n^2)` Worst case performance

`O(n^2)` Best-case performance

`O(n^2)` Average performance

#### Space Complexity

`O(1)` Worst case

#### Example

```
arr[] = {80, 10, 40, 30}
Indexes: 0   1   2   3    

1. Index = 0
	Select the minimum number from the array (between index 0-3), ie, 10
2. Swap 10  and 80 (arr[0])
3. The array now is {10, 80, 40, 30}

4. Index = 1
	Select the minimum number from the array (between index 1-3), ie, 30
5. Swap 30 and 80 (arr[1])
6. The array now is {10, 30, 40, 80}

7. Index = 2
	Select the minimum number from the array (between index 2-3), ie, 40
8. Swap 40 and 40 (arr[2])
9. The array now is {10, 30, 40, 80}

The array is now sorted.
```

#### Code Implementation Links

- [Assembly](https://github.com/CloudArmor/AArch64_Assembly/blob/main/sorters/selection_sort.s)
- [C iterative](https://github.com/CloudArmor/C/blob/master/sorting/selection_sort.c)
- [C recursive](https://github.com/CloudArmor/C/blob/master/sorting/selection_sort_recursive.c)
- [C#](https://github.com/CloudArmor/C-Sharp/blob/master/Algorithms/Sorters/Comparison/SelectionSorter.cs)
- [C++ Iterative](https://github.com/CloudArmor/C-Plus-Plus/blob/master/sorting/selection_sort_iterative.cpp)
- [C++ Recursive](https://github.com/CloudArmor/C-Plus-Plus/blob/master/sorting/selection_sort_recursive.cpp)
- [Dart](https://github.com/CloudArmor/Dart/blob/master/sort/select_Sort.dart)
- [Elixir](https://github.com/CloudArmor/Elixir/blob/master/lib/sorting/selection_sort.ex)
- [Elm](https://github.com/CloudArmor/Elm/blob/master/src/Sorting/SelectionSort.elm)
- [Go](https://github.com/CloudArmor/Go/blob/master/sort/selectionsort.go)
- [Haskell](https://github.com/CloudArmor/Haskell/blob/master/src/Sorts/SelectionSort.hs)
- [Java](https://github.com/CloudArmor/Java/blob/master/src/main/java/com/thealgorithms/sorts/SelectionSort.java)
- [Javascript](https://github.com/CloudArmor/JavaScript/blob/master/Sorts/SelectionSort.js)
- [Julia](https://github.com/CloudArmor/Julia/blob/main/src/sorts/selection_sort.jl)
- [Kotlin](https://github.com/CloudArmor/Kotlin/blob/master/src/main/kotlin/sort/SelectionSort.kt)
- [Lua](https://github.com/CloudArmor/Lua/blob/main/src/sorting/selectionsort.lua)
- [Matlab](https://github.com/CloudArmor/MATLAB-Octave/blob/master/algorithms/sorting/select_sort.m)
- [PHP](https://github.com/CloudArmor/PHP/blob/master/Sorting/SelectionSort.php)
- [Python](https://github.com/CloudArmor/PyAlgorithms/blob/master/sorts/selection_sort.py)
- [R](https://github.com/CloudArmor/R/blob/master/sorting_algorithms/selection_sort.r)
- [Ruby](https://github.com/CloudArmor/Ruby/blob/master/Sorting/selection_sort.rb)
- [Rust](https://github.com/CloudArmor/Rust/blob/master/src/sorting/selection_sort.rs)
- [Scala](https://github.com/CloudArmor/Scala/blob/master/src/main/scala/Sort/SelectionSort.scala)
- [Solidity](https://github.com/CloudArmor/Solidity/blob/main/src/Sorts/SelectionSort.sol)
- [Swift](https://github.com/CloudArmor/Swift/blob/master/sorts/SelectionSort.swift)
- [TypeScript](https://github.com/CloudArmor/TypeScript/blob/master/sorts/selection_sort.ts)

#### Video Explanation

[A video explaining the Selection Sort Algorithm](https://www.youtube.com/watch?v=f8hXR_Hvybo)

#### Animation Explanation

- [Tute Board](https://boardhub.github.io/tute/?wd=selectSortAlgo2)
