# Prefix_Sum
This includes problem on Prefix Sum
Description
Our Task: Given an array arr[] of size n, its prefix sum array is another array prefixSum[ ] of the same size, such that the value of prefixSum[i] is arr[0] + arr[1] + arr[2] … arr[i]. 
Examples : 

Input  : arr[] = {10, 20, 10, 5, 15}
Output : prefixSum[] = {10, 30, 40, 45, 60}
Explanation : While traversing the array, update the element by adding it with its previous element.
prefixSum[0] = 10, 
prefixSum[1] = prefixSum[0] + arr[1] = 30, 
prefixSum[2] = prefixSum[1] + arr[2] = 40 and so on.

To fill the prefix sum array, we run through index 1 to last and keep on adding the present element with the previous value in the prefix sum array.

Time Complexity: O(n)
Auxiliary Space: O(n)
