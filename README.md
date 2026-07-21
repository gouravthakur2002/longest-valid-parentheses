# longest-valid-parentheses

I solved this problem using a stack. The stack stores the indices of parentheses, with -1 pushed initially as a base index. For every '(', I push its index onto the stack. For every ')', I pop the stack. If the stack becomes empty, I push the current index as the new base. Otherwise, I calculate the length of the current valid substring and update the maximum length.

Complexity

Time Complexity: O(n)

Space Complexity: O(n)
