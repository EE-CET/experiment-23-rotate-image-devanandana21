# Experiment 23: Rotate Image

## Problem Statement

You are given a $n \times n$ 2-D matrix representing an image. Rotate the image by **90 degrees (clockwise)**.

**Constraint:** You must rotate the matrix **inplace**, meaning you should modify the 2D matrix directly without allocating another 2D matrix.

## Input Format

* The first line will contain two integers $n$ and $n$ (representing the dimensions).
* The next $n$ lines contain $n$ integers each, representing the matrix.

## Output Format

Print the matrix that is rotated by 90 degrees in the clockwise direction.

### Example 1

**Input:**

```text
2 2
1 2
2 3
```

**Output:**

```text
2 1
3 2
```

**Explanation:**
Original:
1 2
2 3

Rotated 90 deg clockwise:
2 1
3 2
