# Valid-Parentheses

Given a string s containing just the characters '(', ')', '{', '}', '[' and ']', determine if the input string is valid.

An input string is valid if:

    Open brackets must be closed by the same type of brackets.
    Open brackets must be closed in the correct order.

Example 1:

Input: s = "()"
Output: true

Example 2:

Input: s = "()[]{}"
Output: true

Example 3:

Input: s = "(]"
Output: false

 
Constraints:

    1 <= s.length <= 104
    s consists of parentheses only '()[]{}'.
    
Solution:

 The solution involves the use of special data structures called stacks. In computer science, a stack is an abstract data type that serves as a collection of elements, with two main principal operations:

    Push, which adds an element to the collection, and
    Pop, which removes the most recently added element that was not yet removed.

The order in which elements come off a stack gives rise to its alternative name, LIFO (last in, first out).
