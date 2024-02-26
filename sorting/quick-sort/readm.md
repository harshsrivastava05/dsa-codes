Working of quickSort()

<p>Initially, the low points to the first index and the high points to the last index.</p>
<p>Get the index(where the pivot should be placed after sorting) using a partition() function call it partition index.</p>
<p>Call the function quickSort() for the left and the right subarray recursively. i.e quickSort(arr, low, partitionIndex – 1) and quickSort(arr, partitioning + 1, high) do this while(low<high)</p>
