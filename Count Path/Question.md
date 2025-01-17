    Count all possible paths from top left to bottom right.

    The task is to count all the possible paths from top left to bottom right 
    of a m X n matrix with the constraints that from each cell you can either 
    move only to right or down.
 
    Example 1:
    Input: m = 2, n = 2
    Output: 2 
    Explanation: Two possible ways are RD and DR.

    Example 2:
    Input: m = 3, R = 3
    Output: 6
    Explanation: Six possible ways are RRDD, DDRR, RDDR, DRRD, RDRD, DRDR.
    
    Expected Time Complexity: O(m*n)
    Expected Auxiliary Space: O(m*n)

    Constraints:
    1 <= m <=100
    1 <= n <=100
