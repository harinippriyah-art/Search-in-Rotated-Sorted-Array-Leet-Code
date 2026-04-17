Search in Rotated Sorted Array
This repository provides an efficient Java implementation to search for a target value within an array that was originally sorted but subsequently rotated at an unknown pivot.
Key Logic
The algorithm leverages Binary Search by identifying whether the left or right half of the current range is properly sorted. This allows the search space to be halved in each iteration, meeting the O(log n) requirement.
Complexity
Time: 
 – Binary search approach.
Space: 
 – Constant space usage.
