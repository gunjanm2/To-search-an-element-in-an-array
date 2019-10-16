# Searching
## Linear Search
It is used to find whether a given number is present in an array and if it is present then at what location it occurs. It is also known as sequential search. It is straightforward, we keep on comparing each element with the element to search until it is found or the list ends. 
## Binary Search
Binary search is a fast search algorithm with run-time complexity of Ο(log n). This search algorithm works on the principle of divide and conquer. For this algorithm to work properly, the data collection should be in the sorted form.
Binary search looks for a particular item by comparing the middle most item of the collection. If a match occurs, then the index of item is returned. If the middle item is greater than the item, then the item is searched in the sub-array to the left of the middle item. Otherwise, the item is searched for in the sub-array to the right of the middle item. This process continues on the sub-array as well until the size of the subarray reduces to zero.
