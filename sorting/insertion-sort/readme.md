Insertion sort is an algorithm used to sort a collection of elements in ascending or descending order. The basic idea behind the algorithm is to divide the list into two parts: a sorted part and an unsorted part.

Initially, the sorted part contains only the first element of the list, while the rest of the list is in the unsorted part. The algorithm then iterates through each element in the unsorted part, picking one at a time, and inserts it into its correct position in the sorted part.

To do this, the algorithm compares the current element with each element in the sorted part, starting from the rightmost element. It continues to move to the left until it finds an element that is smaller (if sorting in ascending order) or larger (if sorting in descending order) than the current element.

Once the correct position has been found, the algorithm shifts all the elements to the right of that position to make room for the current element, and then inserts the current element into its correct position.

Time Complexity: O(N^2) 
Auxiliary Space: O(1)
