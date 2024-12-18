# Find-All-Duplicates-in-an-Array
Given an integer array nums of length n where 1 ≤ nums[i] ≤ n, some elements appear twice and others appear once. Return an array of all the elements that appear twice.
Explanation
Index Mapping:

Since the array elements are in the range 1 to n, we use the value of each element (as an index) to mark the corresponding position in the array.
Marking as Negative:

If nums[i] is positive, it means we are visiting this index for the first time.
Mark it as negative to indicate it has been visited.
Finding Duplicates:

If nums[index] is already negative when you visit it again, then the number has appeared before, so add it to the result.
Output:

The result list contains all the numbers that appear twice.
