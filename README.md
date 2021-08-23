# Valid-Expression-GFG

Given a string S, composed of different combinations of '(' , ')', '{', '}', '[', ']'. The task is to verify the validity of the arrangement.


Note: Ignore the precedence of brackets.



Example 1:



Input:


S = ()[]{}


Output: 1


Explanation: The arrangement is valid.
 

Example 2:



Input:


S = ())({}


Output: 0


Explanation: Arrangement is not valid.
 

Your Task:  


You dont need to read input or print anything. Complete the function valid() which takes S as input and returns a boolean value denoting whether the arrangement is valid or not.


Expected Time Complexity: O(N) where N is the length of S.


Expected Auxiliary Space: O(N) 


Constraints:

1 <= N <= 104
