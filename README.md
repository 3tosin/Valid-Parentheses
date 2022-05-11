# Valid-Parentheses
Given a string s containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.

An input string is valid if:
i) Open brackets must be closed by the same type of brackets.
ii) Open brackets must be closed in the correct order.

Explanation:
To solve the problem of the valid parentheses it will be helpful to use a **stack data structure**. we are comparing the first input with the last input

 Step 1: if s is empty return true, if the length of s is less than 2 return false.
 Step 2: An hash map that pairs the parentheses and helps to determine if the opening parentheses matches the closing parentheses
 step 3: declaration of an empty array stk
