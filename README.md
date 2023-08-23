# Email_Validation_Project

This Project validates an email address entered by the user using a series of checks and conditions.

1). Length Check: This line checks if the length of the entered email address is at least 6 characters.

2). First Character Check: This part of the code verifies that the first character of the email address is an alphabet letter.

3). @ Symbol Check: This section checks if the email address contains exactly one "@" symbol.

4). Dot Position Check: Here, the code checks whether the last four characters are a dot ('.') or the last three characters are a dot ('.'). This is presumably to verify the common structure of email addresses where the domain ends with a top-level domain like ".com" or ".org".

5). Character Validation Loop: This loop iterates through each character of the email address. It performs several checks:

-> It identifies if there's any whitespace character in the email (denoted by i.isspace()), which is not allowed.
-> It checks if any alphabet character is in uppercase (denoted by i==i.upper()), which could be a violation of standard email format.
-> It allows digits, underscores, periods, and "@" symbols.
-> It marks other characters as invalid.

6). Final Validation and Output: After looping through each character and checking various conditions, the code checks the values of k, j, and d variables. If any of these variables are set to 1, it implies that certain invalid conditions were met, and the code outputs "Wrong Email 5". Otherwise, if all conditions are met, it outputs "Right Email".

<-->  This code aims to provide a basic level of validation for an email address. However, it's important to note that email validation can be much more complex due to the various formatting rules and domain-specific checks involved. Additionally, this code doesn't handle edge cases and internationalized email addresses, which might have special characters or non-ASCII characters.



-> Tech Stack Used - Python

-> Software Used - Visual Studio Code
