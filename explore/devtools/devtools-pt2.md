# Part 2 Answers
1. The bug is that when we acquire the values of num1 and num2 directly from the user's input, it is stored as a string rather than a number. Since it is not converted to a number befre calculateSum is called, the two values are concatenated and returned.
2. To solve this issue, we can use the Number() constructor, which can take the initial string values we provide and convert it to a number. Then, when we pass in num1 and num2 into calculateSum(), the correct sum will be calculated. These changes are shown in the fix.jpg file.
