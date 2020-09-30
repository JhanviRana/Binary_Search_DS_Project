# Binary_Search_DS_Project
This Project Contains the Implementation of Binary Search in Real Life

In computer science, binary search, also known as half-interval search,[1] logarithmic search,[2] or binary chop,[3]
is a search algorithm that finds the position of a target value within a sorted array.

Binary search compares the target value to the middle element of the array.

If they are not equal, the half in which the target cannot lie is eliminated and the search continues on the remaining half, again taking the middle element to compare to the target value, and repeating this until the target value is found. 

If the search ends with the remaining half being empty, the target is not in the array.

ALGORITHM
Parameters inital_value , end_value

Step 1 : Find the middle element of array. using ,
middle = initial_value + end_value / 2 ;
Step 2 : If middle = element, return ‘element found’ and index.
Step 3 : if middle > element, call the function with end_value = middle - 1 .
Step 4 : if middle < element, call the function with start_value = middle + 1 .
Step 5 : exit.
