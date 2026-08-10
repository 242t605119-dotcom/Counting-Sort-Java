# Counting Sort - Java

## Description

This program sorts an array using the Counting Sort algorithm. It counts how many times each value occurs and uses those counts to arrange the elements in ascending order.

## Features

- Takes elements from the user
- Counts the frequency of each value
- Sorts the array in ascending order
- Handles duplicate elements
- Simple implementation using an additional array

## How It Works

The program first finds the largest element in the array.

A count array is then created to store the frequency of each value. After counting all elements, the original array is rebuilt using the stored frequencies.

## Algorithm

1. Read the array elements.
2. Find the maximum value.
3. Create a count array.
4. Count the occurrence of each element.
5. Traverse the count array.
6. Place each value into the original array according to its frequency.
7. Display the sorted array.

## Concepts Used

- Java
- Arrays
- Counting Sort
- Frequency counting
- for loop
- while loop
- Scanner

## Time Complexity

O(n + k)

where `n` is the number of elements and `k` is the range of values.

## Space Complexity

O(k)

## Sample Input

Enter number of elements: 7

4 2 7 2 1 5 4

## Sample Output

Sorted array:

1 2 2 4 4 5 7

## How to Run

Compile:

javac CountingSort.java

Run:

java CountingSort

## Learning Outcome

This program helps in understanding frequency counting, arrays and non-comparison-based sorting techniques in Java.

## Author

T.Nandhini
