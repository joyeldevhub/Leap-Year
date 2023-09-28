# Leap-Year
Using Java Script

## Explanation
The code you provided is a JavaScript function called isLeap(year) that checks if a given year is a leap year or not. A leap year is a year that has an extra day, February 29th, and occurs every four years, with some exceptions.

Here's an explanation of how the code works:

The function isLeap(year) takes one argument, which is the year you want to check.

Inside the function, the code uses a series of nested if statements to determine if the year is a leap year according to the rules of the Gregorian calendar:

The first if statement checks if the year is divisible by 4. If it is, it proceeds to the next level of checking.

The second if statement checks if the year is divisible by 100. If it is, it goes to the next level of checking. If it's not divisible by 100, the function immediately returns "Not leap year" because most years divisible by 4 are leap years, except for those divisible by 100.

The third if statement checks if the year is divisible by 400. If it is, the function returns "Leap year" because years divisible by 400 are always leap years.

If the year is divisible by 4 and 100 but not by 400, the function returns "Not leap year" because these years do not follow the leap year rule.

If the year is not divisible by 4 in the initial check, the function immediately returns "Not leap year" because it doesn't meet the basic leap year condition.

Finally, the function returns either "Leap year" or "Not leap year" based on the results of the nested checks.
