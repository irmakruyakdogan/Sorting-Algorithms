
# Sorting Algorithms




## Insertion Sort and Selection Sort

 I'm explaining how an example is done for Insertion Sort and Selection Sort.


## Insertion Sort

This algorithm iterates through each element, inserting each element into its appropriate position as it traverses the array. During the process, when inserting an element into the sorted part of the array, it is compared with the preceding elements and placed into the correct position.

Insertion Sort has a worst-case time complexity of 
𝑂(𝑛^2)
𝑂(n^2), but it can perform well on small datasets. The step-by-step process of the algorithm can be summarized as follows:

1.)Assuming the first element in the array is already sorted, we start with the second element in the array.

2.)Compare the second element with the first element and check if the second element is smaller, then swap them.

3.)Continue this process by comparing each element with the preceding ones and inserting it into the correct position by swapping as necessary.

4.)Repeat this process until the entire array is sorted."


## Selection Sort
This algorithm sorts the given array by comparing individual elements from smallest to largest or from largest to smallest, and by swapping them into their appropriate positions. 

The time complexity of this algorithm is O(n^2), meaning its performance significantly decreases as the size of the array increases. The step-by-step process of Selection Sort is as follows:

1.)Start from the beginning of the array, and at each step, find the smallest or largest element in the remaining part of the array.

2.)Place the found smallest or largest element at the end of the sorted portion of the array, or place the largest element at the beginning of the sorted portion.

3.)Repeat the process until all elements are sorted, iterating through the entire array.

## Example
![Example](odev_yeni.jpg)
