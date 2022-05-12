# Valid-Parentheses
Given a string s containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.

An input string is valid if:
i) Open brackets must be closed by the same type of brackets.
ii) Open brackets must be closed in the correct order.

Explanation:
To solve the problem of the valid parentheses it will be helpful to use a **stack data structure**. we are comparing the first input with the last input

 if s is empty return true, if the length of s is less than 2 return false.
 the hash map pairs the parentheses and helps to determine if the opening parentheses matches the closing parentheses.
 Each bracket is pushed into the array br and compared to the hash map. if the opening parentheses corresponds to the closing parentheses true is returned else return false
 
 if(stk.length > 0){
        return false; in a case where there is for example "((" brackets return false.
        
 The algorithm is O(n) and it takes O(n) memory
