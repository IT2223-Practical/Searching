# Searching

## arrayTimeComplexity.m ##

This code demonstrates two search methods for finding a number (index = 998) in an array a = 1:1000.

### 1. Linear Search (First Part):
   
Loop from start to end of the array.

Compares each element to the target (998).

If found, prints the index and stops.

Uses tic/toc to measure execution time.

### 2. Binary Search (Second Part):
   
More efficient search using divide-and-conquer.

Calculates middle of the array.

If mid value equals target, it prints the index.

Otherwise, narrows the search range (startPoint, endPoint).

Also uses tic/toc to measure time.

![timeComplexity](https://github.com/user-attachments/assets/fc6286b4-713c-434d-8887-6ab6e7d148bb)


## lenearSearch.m ##
Search for a specific value (index = 9) in the array a = [3, 5, 7, 9, 11, 13] using a linear search, and print its position if found.

![lenear](https://github.com/user-attachments/assets/d5f8be3f-3baa-4aa1-97aa-dc5c4e732d31)

## lenearSearchTime.m ##

This MATLAB code performs a linear search to find the value 9 in the array a = [3, 5, 7, 9, 11, 13].

It uses a for loop to check each element.

If the value is found, it:

Sets found = true

Updates index to the position (1-based)

Breaks the loop

After the search, it prints the index if found or "not found" otherwise.

tic and toc measure the time taken for the search.

![lenearTime](https://github.com/user-attachments/assets/bb35979f-f8b8-4730-a86d-88f193159f48)

## binarySearch.m

The code searches for the number 62 in a sorted array using the binary search algorithm. It repeatedly checks the middle element and narrows down the search range until the target is found or the range is empty. If the target is found, it prints "Element found", otherwise "Element not found".

<img width="552" alt="binarySearch" src="https://github.com/user-attachments/assets/e82523c6-64c1-466e-8f45-73546e79849a" />

## binaryTime.m

The code uses the binary search algorithm to efficiently locate the number 62 in a sorted array. It tracks the time taken to execute the search and prints whether the element was found or not.

<img width="548" alt="binaryTime" src="https://github.com/user-attachments/assets/c270754b-5bb5-4a09-b0aa-4528543739d7" />



