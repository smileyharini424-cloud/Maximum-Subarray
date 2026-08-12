# Maximum Subarray

## Explanation

The Maximum Subarray problem asks us to find the contiguous subarray that has the largest sum.

For the input:

```text
[-2, 1, -3, 4, -1, 2, 1, -5, 4]
```

The subarray:

```text
[4, -1, 2, 1]
```

has the maximum sum:

```text
4 + (-1) + 2 + 1 = 6
```

Therefore the output is `6`.

## Problem Statement

Given an integer array `nums`, find the contiguous subarray with the largest sum and return its sum.

## Features

* Finds the maximum subarray sum
* Uses Kadane's Algorithm
* Traverses the array only once
* Uses constant extra space
* Efficient solution

## How It Works

The program maintains two variables:

```text
currentSum
maxSum
```

`currentSum` stores the best sum ending at the current position.

`maxSum` stores the largest sum found so far.

For every element, the program decides whether to:

* Start a new subarray with the current element
* Add the current element to the existing subarray

Then `maxSum` is updated whenever a larger sum is found.

## Technologies Used

* Arrays
* Loops
* Conditional logic
* Methods
* Kadane's Algorithm

## Data Structure Used

The program uses an integer array to store the input values.

## Methods Used

### maxSubArray()

Finds and returns the maximum subarray sum.

### main()

Provides sample input, calls the method, and displays the result.

## Program Flow

```text
Start
↓
Read array
↓
Initialize currentSum
↓
Initialize maxSum
↓
Traverse array
↓
Calculate currentSum
↓
Update maxSum
↓
Continue until array ends
↓
Return maxSum
↓
End
```

## Sample Input

```text
nums = [-2, 1, -3, 4, -1, 2, 1, -5, 4]
```

## Sample Output

```text
Maximum Subarray Sum: 6
```

## Time Complexity

```text
O(n)
```

The array is traversed once.

## Space Complexity

```text
O(1)
```

Only a few variables are used.

## Key Learning

This problem teaches **Kadane's Algorithm**, which is an efficient way to find the maximum sum of a contiguous subarray.

## File Location

```text
Arrays/MaximumSubarray.java
```

## Repository Structure

```text
Maximum-Subarray/
├── README.md
└── Arrays/
    └── MaximumSubarray.java
```

## Author

**V.Harini**
