# Explanation for the 2x2 version

Let's suppose we have the matrix 2x2 describing the times of T and W for Z1 and Z2. Let then name the elements of Z1's row as `x1` and `x2`, analogically for Z2 `x3` and `x4`.

Then, the total makespan is the minimum from the following two subspans:
1. `x1+max(x2,x3)+x4`
2. `x3+max(x1,x4)+x2`

