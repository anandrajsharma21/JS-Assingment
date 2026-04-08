#JavaScript Assignment 4
Course
Fundamentals of Web Design (CSE 106)

#Description
This repository contains solutions to Assignment 4 using basic JavaScript concepts. All problems are solved using:

prompt() for input
alert() for output
loops, conditions, and functions
File Structure
 → Digit Gatekeeper
 → Roll-Seed Lock
 → Mirror Corridor
 → Fare Calculator
 → Skipping Numbers
 → Contest Score Judge
 

#Q1 – Digit Gatekeeper
Loop from L to R

Check:

divisible by K
no digit 0
sum of digits is prime
Count valid numbers

Time Complexity: O(N × d)

#Q2 – Roll-Seed Lock
Perform 3 transformations on number

Use conditional logic (even/odd)

Check:

number is 3-digit
middle digit equals seed
Time Complexity: O(1)

#Q3 – Mirror Corridor
Try values of X from 0 to 100000

Check:

N + X is palindrome
divisible by K
Return smallest X

Time Complexity: O(100000 × d)

#Q4 – Fare Calculator
Apply fare rules step by step:

base + distance cost
late penalty
distance bonus
seed adjustment
Round to nearest multiple of 5

Time Complexity: O(1)

#Q5 – Skipping Numbers
Increment m from 1 onwards
Add numbers except multiples of (seed + 2)
Stop when sum ≥ N
Time Complexity: O(m)

#Q6 – Contest Score Judge
Compute score = 3a + b − 2c

Apply constraints:

no negative score
penalty if total attempts > 50
Decide PASS / FAIL

Time Complexity: O(1)

How to Run
Open browser console OR attach file to HTML
Run each .js file separately
Enter inputs via prompt
Output will be shown using alert
By
Anand Raj Sharma course: Btech(M&C)/009
