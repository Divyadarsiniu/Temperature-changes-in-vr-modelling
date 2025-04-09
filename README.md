# Temperature-changes-in-vr-modelling
## Definition:
### The Min-Max Algorithm is a divide and conquer strategy used to find the minimum and maximum element in a collection (like an array) with the least number of comparisons.The Min-Max Algorithm is a classical divide and conquer approach used to determine the minimum and maximum elements in an array or list efficiently. Instead of scanning the array twice—once for the minimum and once for the maximum—the Min-Max algorithm reduces the total number of comparisons by cleverly dividing the array into smaller subarrays and recursively solving the problem.
## Use Case:
### It is used when you want to simultaneously find both the minimum and maximum values in an array efficiently, rather than making two passes or comparing each element twice.
## Core Idea:
## Divide the array into two halves.

### Conquer by recursively finding the minimum and maximum in each half.

### Combine the results by comparing the min and max of each half to get the overall min and max.
## Time Complexity:
### Best/Average/Worst Case: O(n)

### Number of comparisons: At most (3n/2) - 2
## Applications:
### Finding temperature extremes in weather datasets.
### Identifying bounds in sensor readings.

### Real-time processing of streaming data for alerts.




https://github.com/user-attachments/assets/38b0e8e2-57e6-41da-99a9-e3c9e9d9c980

