NAME:- ANSH PRATAP SINGH

PRN: 25070123143

AIM:- STUDY OF WHILE LOOP IN PYTHON

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
THEORY: In Python, a loop is used to execute a block of code repeatedly. The while loop is one of the fundamental looping constructs that allows a set of statements to run as long as a specified condition remains True.
The while loop is mainly used when the number of iterations is not known in advance and depends on a condition.

DEFINITION: A while loop repeatedly executes a block of code as long as the given condition evaluates to True. If the condition becomes False, the loop stops executing.

Working of While Loop:

Initialization – A variable is initialized before the loop starts.

Condition Check – The condition is evaluated.

Execution – If the condition is true, the statements inside the loop are executed.

Updation – The variable is updated to eventually make the condition false.

The loop repeats until the condition becomes false.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: To Print Numbers from 1 to 5 Using While Loop

Start

Initialize i = 1.

Repeat while i ≤ 5

--->a. Display i

--->b. Increment i = i + 1

End While Loop

Stop

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: To Print Numbers from 1 to n Using While Loop

Start

Input a number n.

Initialize i = 1.

Repeat while i ≤ n

--->a. Display i

--->b. Increment i = i + 1

End While Loop

Stop

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: To Find the Factorial of a Number Using While Loop

Start

Input a non-negative integer n.

Check if n < 0

--->If true, display “Factorial is not defined for negative numbers.”

--->Go to Step 9.

Else if n == 0

--->Display “The factorial of 0 is 1.”

--->Go to Step 9.

Else

--->Initialize fact = 1

--->Initialize i = 1

Repeat while i ≤ n

--->fact = fact × i

--->i = i + 1

End While Loop

Display “The factorial of n is fact.”

Stop

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: To Generate Fibonacci Series Using While Loop

Start

Input the number of terms no_of_terms.

Initialize variables:

--->a = 0

--->b = 1

--->count = 0

Check if no_of_terms ≤ 0

--->If true, display “Please enter a positive integer.”

--->Go to Step 10.

Else if no_of_terms == 1

--->Display “Fibonacci sequence up to 1 term:”

--->Display a

--->Go to Step 9.

Else

--->Display “Fibonacci sequence:”

Repeat while count < no_of_terms

--->Display a

--->nth = a + b

--->a = b

--->b = nth

--->count = count + 1

End While Loop

Stop

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: To Generate Fibonacci Series Up to a Given Limit

Start

Input the limit value limit.

Initialize variables:

--->a = 0

--->b = 1

Repeat while a ≤ limit

--->Display a

--->Update values as follows:

------>temp = a + b

------>a = b

------>b = temp

End While Loop

Stop

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: To Reverse a Number Using While Loop

Start

Input a number num.

Initialize rev = 0.

Repeat while num > 0

--->a. Find the last digit:

--->digit = num % 10

--->b. Update reversed number:

--->rev = (rev × 10) + digit

--->c. Remove last digit from original number:

--->num = num // 10

End While Loop

Display “Reversed number is: rev”.

Stop

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: To Check Palindrome Number and Palindrome String Using While Loop

Part A: Palindrome Number

Start

Input an integer original_num.

Assign num = original_num.

Initialize reversed_num = 0.

Repeat while num > 0

--->a. digit = num % 10

--->b. reversed_num = (reversed_num × 10) + digit

--->c. num = num // 10

End While Loop

If original_num == reversed_num

--->Display “original_num is a palindrome number.”

Else

--->Display “original_num is not a palindrome number.”

Proceed to Part B.

Part B: Palindrome String

Input a string original_string.

Convert the string to lowercase and remove non-alphanumeric characters.

Store it in cleaned_string.

Initialize:

--->reversed_string = ""

--->index = length of cleaned_string − 1

Repeat while index ≥ 0

--->a. Append character at position index to reversed_string

--->b. Decrement index by 1

End While Loop

If cleaned_string == reversed_string

--->Display “original_string is a palindrome string.”

Else

--->Display “original_string is not a palindrome string.”

Stop

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: To Check Whether a String is Palindrome Using String Slicing

Start

Input a string st.

Reverse the string using slicing method:

--->rev = reverse of st (using st[::-1]).

If st == rev

--->Display “st is a palindrome string.”

Else

--->Display “st is not a palindrome string.”

Stop

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: To Count the Number of Digits in a Number Using While Loop

Start

Input an integer num.

Initialize count = 0.

If num == 0

--->Set count = 1

--->Go to Step 9.

Else

--->Convert number to positive value:

------>num = |num| (absolute value)

Repeat while num > 0

--->a. num = num // 10

--->b. count = count + 1

End While Loop

Display “The number of digits is: count”.

Stop

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: To Search an Element in a List Using While Loop

Start

Initialize the list
--->nums = [10, 20, 30, 40, 50]

Input the element to search as key.

Initialize i = 0.

Repeat while i < length of nums

--->a. If nums[i] == key

------>Display “Element found at index i”

------>Exit the loop using break

------>b. Increment i = i + 1

If loop completes without finding the element

--->Display “Element not found”

Stop

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Algorithm: To Print Odd Numbers from 1 to 10 Using While Loop and Continue Statement

Start

Initialize num = 1.

Repeat while num ≤ 10

--->a. If num % 2 == 0 (number is even)

------>Increment num = num + 1

------>Use continue to skip remaining statements and move to next iteration

--->b. Else

------>Display num

--->c. Increment num = num + 1

End While Loop

Stop

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Conclusion

In this experiment, the concept of the while loop in Python was successfully studied and implemented through various programs. Different problem statements such as factorial calculation, Fibonacci series generation (by number of terms and by limit), reversing a number, checking palindrome (number and string), counting digits, linear search, and printing odd numbers were solved using the while loop.

The experiment demonstrated how the while loop works based on a condition and continues execution until the condition becomes false. It also highlighted the importance of proper initialization, condition checking, and updation to avoid infinite loops. Additionally, the use of control statements like break and continue was understood for controlling loop execution.
